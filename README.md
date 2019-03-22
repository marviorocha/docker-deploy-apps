# Deployment Apps, Rails, WordPress ... Like Docker

Hello, My name's Marvio Rocha, I'm a simple developer from Brazil than love  docker and docker-compose. This is a simple docker-compose script for build a production deployment with docker.

I make it with a person WordPress installer. But you can put other applications run join.

That was based on great tutorial the -> [Niels, Enabling HTTPS termination in Traefik](https://niels.nu/blog/2017/traefik-https-letsencrypt.html))
#### Prerequisites
Ubuntu 18.04 server or other distro based on Linux set up by following [I like the Ubuntu 18.04 in Digital Ocean](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04), including a sudo non-root user and a firewall.

Docker and docker-compose installed on your server

## How to it work


 1. First clone with:


`git clone https://github.com/marviorocha/docker-deploy-apps.git `

 2. Settings Traefik.toml file with your information
 3. Open your docker-compose.yml settings it.
 4. Open your shell make it:

`docker-compose -f docker-traefik.yml up -d --build
     docker-compose up -d --build `

My site: [marviorocha.com](https://www.marviorocha.com)
Thanks.
