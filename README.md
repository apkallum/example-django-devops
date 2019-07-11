# example-django-devops 

This is an automated Django/Postgres/Ngnix setup, built using Docker and docker-compose. 

## Quickstart

1. Install Docker and docker-compose on a Linux VPS
2. Add your Linux user to the docker group, to avoid using sudo
3. Clone this repo to `/opt/monadical/`
4. Create a `/data/db` and a `data/letsencrypt` directory (they are ignored by git)
5. Replace the value of the environment variables `SERVERNAME` and `EXTRANAMES` in docker-compose.yml with your domain name.
6. Run ./bin/start
