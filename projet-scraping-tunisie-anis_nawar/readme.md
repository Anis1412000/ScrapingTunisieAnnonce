Projet Scraping Tunisie Annonce
Description
Ce projet consiste en une solution de scraping conçue pour extraire les annonces immobilières du site tunisie-annonce.com. Les données collectées sont stockées dans une base de données PostgreSQL, avec une exportation disponible sous le nom scrapping.sql, ainsi que dans un fichier JSON (data/annonces.json). En outre, ces données sont accessibles via une API REST développée avec FastAPI.

Fonctionnalités
Scraping : Extraction des informations clés des annonces, telles que le titre, le prix, le type de bien, la localisation, la superficie, la description, le contact, la date de publication, et le lien.
Stockage :
Base de données PostgreSQL (scrapping.sql)
Fichier JSON (data/annonces.json)
API : Une interface REST permettant de consulter les annonces ou de relancer le processus de scraping.
Prérequis
Python
PostgreSQL
Git
Dépendances
Pour connaître la liste complète des dépendances nécessaires, veuillez consulter le fichier requirements.txt.