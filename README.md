# forum

Bonjour à tous

Développement des modules.

Module 1: Authentification et connexion
1*Config de la base de données : fjeed
--aller dans le dossier du projet et copier le fichier .env.example
--renommer la copie en .env et modifier les parametres suivants :
	DB_DATABASE=fjeed
	DB_USERNAME=root
	DB_PASSWORD=password
--aller dans le terminal pour taper la commande
	*php artisan //pour voir la liste des commandes de laravel
	*php artisan key:generate // pour générer la clé de l'application
	*composer update //pour mettre à jour la liste de commandes
--aller dans xampp et créer votre fjeed
--ensuite aller dans votre terminal, taperla commande
	*composer require laravel/ui // ce composant est nécessaire pour créer un user authentificator
	*php artisan ui vue --auth //pour créer la table user
	*php artisan migrate // pour créer une migration de la table user dans la base de données.*

--Autres mises à jour
	npm install -g npm
	npm run dev

	*Jusqu'ici l'authentification (inscription et connexion fonctionnent). donc créez dans votre xampp la base de données fjeed et tapez la commande php artisan migrate sur votre terminal pour que les tables migrent dans vos servers*