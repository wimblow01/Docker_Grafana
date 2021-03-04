# Un conteneur pour grafana

Ce projet réalisé en binôme a pour but de développer sur un serveur Linux un dashboard Grafana proposant des graphiques sur la vaccination de la Covid-19 dans le monde.

## Traitement des données
Pour commencer nous avons traité les données mises à notre disposition:
* Suppression des colonnes qui ne nous semblaient pas "utilent" pour les graph que l'on voulait faire permettant ainsi d'alléger le fichier
    * iso_code : code du pays
    * id_vac : id de l'entrée dans la database
    * source_name : la source des données (ministère de la santé, agence gouvernementale, ... ) 
    * source_website : le site internet où l'on trouve l'information
* Le remplacement des valeurs NAN par des 0 pour une meilleure intégration 
* Convertion du fichier .csv et .sql


## Instalation 

Dans un premier temps, installer Docker Desktop [lien](https://www.docker.com/products/docker-desktop)

Les installations de Grafana et MySql  se fait via Docker.


## Création du docker-compose

Pour faciliter la mise en place des containers , nous avons utilisé un fichier [docker-compose](/docker-compose.yml) qui contiendra les information nécessaires à leur création.

Ce fichier peut être lancer dans l'invit de commande avec 
![docker-compose](image/lancement du compose.PNG)
