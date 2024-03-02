#Projet Docker - Exercice 2 (Joomla)

#Objectif :
L'objectif de cet exercice est de dockeriser une application Joomla en utilisant Docker Compose. J'ai créé une composition de trois containers : un serveur Web (nginx / apache), un container PHP et un container pour la base de données (mariadb). L'objectif final est de fournir une application Joomla entièrement fonctionnelle qui peut être déployée avec un simple docker-compose up.

#Étapes clés :
Clonage du repository : J'ai commencé par cloner le repository contenant les fichiers nécessaires pour l'exercice.

#Téléchargement de Joomla : J'ai téléchargé la dernière version de Joomla depuis leur site officiel.

#Configuration de Docker Compose : J'ai utilisé un fichier docker-compose pour définir les services nécessaires, y compris le serveur Web, PHP et la base de données MariaDB. J'ai également configuré les volumes pour partager les fichiers nécessaires avec les containers.

#Installation de Joomla : Après avoir démarré les containers avec docker-compose up, j'ai accédé à la page d'installation de Joomla via http://localhost:8081 et suivi les instructions pour installer Joomla.

#Sauvegarde de la base de données : J'ai assuré la sauvegarde correcte de la base de données afin que d'autres utilisateurs puissent déployer l'application avec un simple docker-compose up.

#Points importants :
J'ai suivi les meilleures pratiques de Docker pour assurer la portabilité, la reproductibilité et la sécurité de l'application.

J'ai documenté chaque étape du processus dans le README.md pour faciliter la compréhension et la reproduction du projet.

#Livrables :
J'ai préparé une archive contenant les fichiers nécessaires pour le déploiement de l'application Joomla, y compris le fichier docker-compose, les fichiers Joomla et la sauvegarde de la base de données.
