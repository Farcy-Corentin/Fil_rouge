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

# Mettre en place une base de données - Time :
| Mission 1     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |---------------|----------------|-----------|
|1.1| Elaborer le dictionnaire des données          | > 5 hours  |  | in progress | - [x] ok?
|1.2| Créer la base de données                      | > 5 hours  |  | in progress | [x] <br/>[ ] item2<br/>[ ] item2<br/>[ ] item2
|1.2.1| Realiser le MCD                             | > 5 hours  |  | in progress | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul>
|1.2.2| Ecrire le script de creation BDD            | > 5 hours  |  | in progress | <ul><li>[x] item1</li><li>[ ] item2</li></ul>
|1.2.4| Création plusieurs profils de connexion / autorisation * | > 5 hours  |  | in progress | [x] item1<br/>[ ] item2<br/>[ ] item2<br/>[ ] item2
|1.2.5| Alimenter la base (Faker)                   | > 5 hours  |  | in progress | [x] item1<br/>[ ] item2<br/>[ ] item2<br/>[ ] item2
|1.2.6| Création des procédures                     | > 5 hours  |  | in progress | [x] item1<br/>[ ] item2<br/>[ ] item2<br/>[ ] item2
|1.2.6| Test de la restauration                     | > 5 hours  |  | in progress | [x] Vérification fonctionnement <br/>[ ] Effectuer des données effacées<br/>[ ] Ajout d'un script (cron)<br/>[ ] Rapport de vérification
```
*
- Profil visiteur : 
    - Lecture sur le catalogue
- Profil client : 
    - lecture sur toute la base (insert, update des commandes et client)
- Profil gestion :
    - lecture, criture dans la base
- Profil utilisateur/developpeur
    - Gestion + création + suppression
```

# Manipuler la base de données - Time :
| Mission 2     | Taches                                    | Time required | Current Status | Finished | 
|---------------|----------------                           |--------------- |----------------|-----------|
|2.1| Formaliser des requetes SQL          | > 5 hours  |  | in progress | [ ] Creation des requetes (INSERT, UPDATE, DELETE)
|2.1.1| Pour chacune des interrogations demandées, créez un script contenant la ou les requêtes nécessaires | > 5 hours  |   in progress | [ ] créer un script contenant la ou les requêtes nécessaires
|2.1.2| Exportation des tables principales vers des tableaux d'un tableur et le contenu du résultat de vos requêtes | > 5 hours  |  in progress | [ ] exporter la base en .csv <br/>[ ] le résultat des requête dans un tableau excel
|2.1.3| chiffre d'affaires hors taxes généré pour l'ensemble et par fournisseur | > 5 hours  |  in progress | [ ] HT global<br/>[ ] par fournisseur</li></ul>
|2.1.4| liste des produits commandés pour une année sélectionnée  | > 5 hours  |  in progress | [ ] référence <br/>[ ] nom du produit<br/>[ ] Quantité<br/>[ ] fournisseur
|2.1.5| liste des commandes pour un client | > 5 hours  | in progress | [ ] Date<br/>[ ] réference<br/>[ ] montant <br/>[ ] Etat commande
|2.1.6| répartition du chiffre d'affaires hors taxes par type de client | > 5 hours  |  in progress | 
|2.1.7| lister les commandes en cours de livraison | > 5 hours  | in progress | [ ] toutes les commandes <br/>[ ] commandes crées<br/>[ ] commandes terminer <br/>[ ] Rapport de vérification


# Programmer des procédures stockées sur le SGBD - Time :
| Mission 3     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|3.2.1| Qui renvoie le délai moyen entre la date de commande et la date de facturation | > 5 hours | in progress | []créer procédure
|3.3| Gérer les vues | > 5 hours |  in progress | [] vue jointure Produits - Fournisseurs


# Construire la maquette de l'application - Time :
| Mission 4     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|4.1| Diagramme de cas d'utilisation d'une commande sur le site par un client particulier | > 5 hours | in progress | []diagramme commande []panier
|4.2| Réaliser la maquette de la page de connexion du site | > 5 hours | in progress | []maquette connexion

# Développer une application web - Time :
| Mission 5     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|5.1| Réalisez un site e-commerce pour les clients | > 5 hours | in progress | []consulter le catalogue []saisir de nouvelles commandes []visualiser les anciennes commande
|5.2| Développer des pages web statiques (HTML/CSS) 10 jours | > 5 hours | []index []formulaire d'inscription []catalogue []panier []interface administrateur

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
