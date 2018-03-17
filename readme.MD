# Local Docker setup

You can either uncomment the Traefik service in `wordpress/docker-compose.yml` and run with a single site mapped to port `80` or you can start an independent reverse proxy found in `traefik` that will listen for the labels.

