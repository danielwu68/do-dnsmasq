# do-dnsmasq 
A tiny project contains scripts to quickly start *dnsmasq* for my DNS spoofing purposes.

## Setup
- Download and install [Docker Desktop](https://www.docker.com/products/docker-desktop "Docker Desktop") for your OS
- Grant `Docker Desktop` access to this folder
  - Open Docker Desktop - Preferences - Resources - FILE SHARING
  - click on `+` to add the current folder

## Running
- ./doRun - start the `dnsmasq` container
  - environment variables:
    - UI_PORT - web based UI listenering port, default 5380
    - UI_USER - web based UI username
    - UI_PASS - web based UI password
- ./doKill - kill the `dnsmasq` container

## Configuration
- ./data/etc/dnsmasq.conf - dnsmasq configuration
  - see also [docker-dnsmasq](https://github.com/jpillora/docker-dnsmasq "docker-dnsmasq")
  - see also [dnsmasq](http://manpages.ubuntu.com/manpages/bionic/man8/dnsmasq.8.html "dnsmasq")