# docker-adblock_blocklist_updater

## Docker Hub
[rossbannerman/adblock_blocklist_updater](https://hub.docker.com/r/rossbannerman/adblock_blocklist_updater/)

## Adblock Blocklist Updater
Container that clones [notracking/hosts-blocklists](https://github.com/notracking/hosts-blocklists), fetches updates daily and restarts dnsmasq. Used by [rossbannerman/docker-adblock](https://github.com/rossbannerman/docker-adblock). 

## Usage
`docker run -d --name adblock_blocklist_updater rossbannerman/adblock_blocklist_updater:latest`
