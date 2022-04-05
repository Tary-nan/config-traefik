# Traefik

## À faire sous Linux

    sudo mkdir -p /srv/docker/traefik/conf
    sudo touch /srv/docker/traefik/conf/acme.json
    sudo touch /srv/docker/traefik/conf/traefik.toml
    sudo chmod 0600 /srv/docker/traefik/conf/acme.json

## Lancer 

    docker-compose up -d --build

## Arrêter

    docker-compose down
# config-traefik
