Installation de Laravel
=======================

Introduction
------------

Laravel est un framework PHP robuste et moderne pour le développement d'applications web.

Pré-requis
-----------

Assurez-vous d'avoir les éléments suivants installés sur votre machine :

- PHP >= 7.3
- Composer
- Un serveur web tel qu'Apache ou Nginx

Installation
------------

Suivez les étapes ci-dessous pour installer Laravel :

1. **Installer Composer**

   Si Composer n'est pas déjà installé, vous pouvez le télécharger depuis [getcomposer.org](https://getcomposer.org).

2. **Créer un nouveau projet Laravel**

   Exécutez la commande suivante pour créer un nouveau projet Laravel :

   .. code-block:: bash

      composer create-project --prefer-dist laravel/laravel nom-du-projet

3. **Configurer le serveur web**

   Configurez votre serveur web pour qu'il pointe vers le répertoire `public` de votre nouveau projet Laravel.

Vérification
------------

Accédez à votre projet via l'URL configurée sur votre serveur web. Vous devriez voir la page d'accueil de Laravel.

