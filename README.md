# Documentation

Configuration
-> Installer Docker & Docker compose
-> Création d'un nom de domaine avec DuckDns 
  - https://www.duckdns.org/ 

 Étapes
- > Vérification la version Docker (voir si l'installation à bien été effectuée)
- > Git clone le repository tp3-6309487 ou Fork ce repository
- > Rentrez dans le dossier tp3-6309487 ou le nom de votre nouvelle repository
- > Créer un fichier .env grâce au .env.example fourni
- > Créer les containers avec la commande
  - sudo docker compose up -d
    - (-d) detached - pour garder l'acès au terminal lors de la création des containers

- > Fermer les containers avec la commande
  - sudo docker compose down


AND TADAA YOU SUCCESSFULLY CREATED 3 SERVICES AND 1 REVERSE PROXY WITH MY COMPOSE.YAML
- Plex
- Portainer
- Jellyfin
- Traefik




