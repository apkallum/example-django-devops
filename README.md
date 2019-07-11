# example-django-devops 

This is an automated Django/Postgres/Ngnix setup, built using Docker and docker-compose. 

## Quickstart

1. Install Docker and docker-compose on a Linux VPS
2. Add your Linux user to the docker group, to avoid using sudo
3. Clone this repo to `/opt/monadical/`
4. Replace the value of the environment variables `SERVERNAME` and `EXTRANAMES` in docker-compose.yml with your domain name.
5. Run ./bin/start
