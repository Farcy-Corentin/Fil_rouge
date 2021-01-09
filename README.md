# Village Green

***

L'entreprise Village Green distribue du matériel musical. Elle a une activité de grossiste. 

## Problématique

***

Développer la vente aux particuliers. 
Faire évoluer le système de gestion des commandes et de facturation de l'entreprise.

Actuellement, l'organisation utilise un système qui ne donne pas entière satisfaction. L'informatisation de la totalité du processus depuis la publication du catalogue, de la commande jusqu'au paiement a pour objectif de fluidifier le workflow de l'entreprise.

La société souhaite avoir un site e-commerce permettant aux clients de visualiser l'ensemble du catalogue et de passer des commandes en ligne.

## Travaille à réaliser

***

### 1 - Mettre en place une base de données 5 jours

***

1.1 - Elaborer le dictionnaire de données

1.2 - Créer la base de données

1.2.1 - Réaliser le MCD du site e-commerce ✅

1.2.2 - Ecrire le script de création de la base de donnée

1.2.4 - Créations de plusieurs profils de connexion et décliner les autorisations nécessaires

Profil visiteur : lecture sur le catalogue
Profil client : lecture sur toute la base (insertion et mise à jour dans commande et client)
Profil gestion : lecture/écriture dans la base
Profil administrateur (ou développeur) : comme gestion + création et suppression d'objet

1.2.5 - Alimenter la base de tests

1.2.6 - Création des procédures pour assurer les sauvegardes de la base de données

1.2.7 - Test de la restauration

### 2 - Manipuler la base de données 5 jours

***

2.1 - Formaliser des requêtes à l'aide du langage SQL

2.1.1 - Pour chacune des interrogations demandées, créez un script contenant la ou les requêtes nécessaires

2.1.2 - Exportation des tables principales vers des tableaux d'un tableur et le contenu du résultat de vos requêtes

Requêtes à prévoir :

2.1.3 - chiffre d'affaires hors taxes généré pour l'ensemble et par fournisseur

2.1.4 - liste des produits commandés pour une année sélectionnée (référence et nom du produit, quantité commandée, fournisseur)

2.1.5 - liste des commandes pour un client (date de commande, référence client, montant, état de la commande)

2.1.6 - répartition du chiffre d'affaires hors taxes par type de client

2.1.7 - lister les commandes en cours de livraison


### 2.2 - Programmer des procédures stockées sur le SGBD 2 jours

***

Création des procédures stockées :

2.2.1 - qui renvoie le délai moyen entre la date de commande et la date de facturation

2.3 - Gérer les vues

2.3.1 - Créez une vue correspondant à la jointure Produits - Fournisseurs

### 3 - Construire la maquette de l'application 5 jours

*** 

3.1 - Représentez le diagramme de cas d'utilisation d'une commande sur le site par un client particulier. La notion de panier doit y apparaître

3.2 - Réalisez la maquette de la page de connexion du site

### 4 - Développer une application web 

***

Réalisez un site e-commerce pour les clients particuliers qui permet de :

4.0.1 - consulter le catalogue

4.0.2 - saisir de nouvelles commandes

4.0.3 - visualiser les anciennes commandes

### 4.1 - Développer des pages web statiques (HTML/CSS) 10 jours 

***

4.1.1 - Réaliser une page d'accueil pour votre projet ✅

Le site sera divisé en deux parties :

4.1.2 - Front-office : contient la partie publique du site (dont la page d'accueil) et un accès à la liste de produits et accès au formulaire d'inscription

4.1.3 - Back-office : c'est la partie privée du site, réservée à l'administrateur, elle permet de gérer les produits et les commandes

### 4.2 - Intégrer des scripts clients (Javascript) 2 jours

***

4.2.1 - Création d'un formulaire d'inscription pour le client.

4.2.2 - Vérification de la saisie utilisateur

### 4.3 - Développer des composants web d'accès aux données 10 jours

***

4.3.1 - gestion du CRUD

4.3.2 - Affichage liste des éléments, l'ajout, la modification et la suppression

4.3.3 - Mise en place du Framework MVC

### 6 - Mettre en œuvre une solution de gestion de contenu ou d'ecommerce 27

*** 

Dans le cadre de sa stratégie S.E.O., la société Village Green veut développer du marketing de contenu autour des produits qu'elle commercialise via un blog en Wordpress (articles sur les nouveaux produits, tests, vulgarisation technique, vie de l'entreprise etc.).

6.1 - Réalisez un thème responsive qui reprend les grandes lignes de la charte graphique du site e-commerce.

6.2 - Les employés pourront écrire des articles sans les publier. Il n'y aura qu'un seul administrateur, lequel se chargera, entre autres tâches, de valider les articles.

6.3 - Un plugin S.E.O. devra être configuré.

6.4 - La sécurité devra bien sûr être prise en compte.

6.5 - Publier le résultat de votre travail sur le serveur. Le site publié doit s'exécuter sans erreur.
