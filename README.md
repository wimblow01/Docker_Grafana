# Un conteneur pour grafana

Ce projet réalisé en binôme a pour but de développer sur un serveur Linux un dashboard Grafana proposant des graphiques sur la vaccination de la Covid-19 dans le monde.

## Mysql
Pour commencer nous avons traité les données mises à notre disposition:
* suppression des colonnes qui ne nous semblaient pas "utilent" pour les graph que l'on voulait faire permettant ainsi d'alléger le fichier
    * iso_code : code du pays
    * id_vac : id de l'entrée dans la database
    * source_name : la source des données (ministère de la santé, agence gouvernementale, ... ) 
    * source_website : le site internet où l'on trouve l'information
* le remplacement des valeurs NAN par des 0 pour une meilleure intégration 




## Grafana




## Création du docker-compose
