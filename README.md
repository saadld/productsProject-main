# productsProject-main

Ce projet est un backend pour gérer des produits.

Configuration

##Fichier .env

Vous devez ajouter un fichier .env à la racine du projet avec le contenu suivant :

```plaintext
MONGODB_URI=mongodb://localhost:27017/produits
JWT_SECRET=fdjmqlkdjfmljmjreaz

##Base de données

Créez une base de données nommée produits dans MongoDB. Ensuite, ajoutez les documents nécessaires dans la collection products

##Installation et lancement

Pour installer les dépendances du projet et lancer le serveur backend, exécutez les commandes suivantes :
npm install
node app.js

Le serveur backend sera lancé sur le port 5000.
