# Prérequis pour tester rabbitmq et le projet sentiment analysis

## Cloner le repository

## Démarrer les containers

- Dans un invite de commandes, se placer dans le répertoire
  `sa-architecture`
- Créer le réseau pour les containers
  `docker network create applications-networks`
- Exécuter la commande
  `docker-compose up -d`
- Vérification
  `docker-compose ps`

## Créer la table

- Avec les identfiants dans le docker-compose, se connecter à la BDD
- Exécuter le contenu du fichier **sa-ddl.sql**
