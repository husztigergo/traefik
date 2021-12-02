# Traefik reverse proxy
#### Requirements : docker, docker-compose, apache2-utils
#### If you want a traefik dashboard, run the htpasswd command to generate a new password for traefik dashboard authentication. "_htpasswd -nb youruser yourpassword_"
#### In the treafik.toml config file, edit the "_email_" to yours and if you generated a password, add it at "_users = ["admin:password"]_" section.
#### Add your domain names and more services if you want. The acme.json file stores your certificates for you and traefik will attempt to renew these when they about to expire.
#### Hit "_docker-compose up -d_"
