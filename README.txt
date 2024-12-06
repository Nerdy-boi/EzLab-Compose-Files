William's Docker Compose Files


Dependencies: docker, tailscale

before installing tailscale, on distros that use systemd, edit /etc/systemd/resolved.conf and set the line #DNSStubListener to "no"

install tailscale with the handy bash script from their own site, or from your package manager from choice

once Docker is installed. set the variables in config.env and run "sudo docker compose up -d" 



After this, go through each of the services and configure. as there is no nice way to automate this that i have found