Dofus Pedia est une encyclopédie de Dofus, le jeu de rôle massivement multijoueur en ligne (MMORPG) de Ankama. Elle est développée par moi, fan de Dofus, pour les fans de Dofus. Elle est disponible en ligne à l'adresse (à venir). Elle est également disponible en version mobile (responsive), pour Android et iOS. Elle est développée en React et Node.js.

# TODO

## Revoir l'interface l'ergonomie du formulaire d'ajout de mob (select different)

## Classes /!\ FAIRE UN SEUL COMPOSANT DYNAMIQUE QUI GERE TOUTES LES CLASSES /!\

- dans le router path="/classes/:name" (name = nom de la classe)
- dans le composant, faire un fetch sur l'API pour récupérer les infos de la classe

# TO CHANGE

## Clarifier le formulaire pour ajouter un mob

# Installation

## Prérequis

- Un environnement local (WAMP, MAMP, XAMPP, etc.)
- Node.js

## Installation

- Cloner le projet
- Installer les dépendances avec `npm install`
- Créer un fichier `.env` à la racine du dossier server et y ajouter les variables d'environnement suivantes:

```js
LOCAL_PORT = 3000;
TOKEN_SECRET = // Insérer une chaîne de caractères, peut-être générée avec https://www.random.org/strings/
  DB_HOST = localhost;
DB_USER = root;
DB_PWD = DB_NAME = dofus_wiki;
```

- Importer la base de données `dofus_wiki.sql` dans votre environnement local
- Lancer le serveur avec `npm run dev`
- Lancer le client avec `npm start`
- Ouvrir le navigateur à l'adresse `http://localhost:3000`

# Technologies

- React
- Node.js
- Express
- Axios
- React Router

# Auteur

- **Alexis-YOVO** - _Développeur Web Full Stack_

# Crédits

- **Ankama** - _Informations, images et ressources_

Ce projet est réalisé dans le cadre de ma formation de développeur web full stack. Il s'agit de mon projet final.
# Dofus-Encyclop-die
