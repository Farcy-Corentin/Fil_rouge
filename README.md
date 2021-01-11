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

# Mettre en place une base de données - 5 days :
| Mission 1     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |---------------|----------------|-----------|
|1.1| Elaborer le dictionnaire des données          | > 5 hours  | in progress | [ ] dictionnaire de données
|1.2| Créer la base de données                      | > 1 jours  | in progress |
|1.2.1| Realiser le MCD                             | > 1 jours  | in progress | [ ] MCD <br/> [ ] MPD
|1.2.2| Ecrire le script de creation BDD            | > 1 jours  | in progress | [ ] scrip création de la BDD
|1.2.4| Création plusieurs profils de connexion / autorisation * | > 5 hours  | in progress | [ ] profil visiteur <br/> [ ] profil client <br/> [ ] profil gestion <br/> [ ] profil administrateur
|1.2.5| Alimenter la base (Faker)                   | > 5 hours  | in progress | [ ] générer fausses données <br/> [ ] insérer données dans la BDD
|1.2.6| Création des procédures                     | > 5 hours  | in progress | [ ] procédure sauvegarde
|1.2.6| Test de la restauration                     | > 5 hours  | in progress | [ ] test procédure sauvegarde <br/>[ ] vérication sauvegarde <br/> [ ] restauration sauvegarde <br/>
```
*
- Profil visiteur : 
    - Lecture sur le catalogue
- Profil client : 
    - lecture sur toute la base (insert, update des commandes et client)
- Profil gestion :
    - lecture, criture dans la base
- Profil administrateur
    - Gestion + création + suppression
```

# Manipuler la base de données - 4 days :
| Mission 2     | Taches                                    | Time required | Current Status | Finished | 
|---------------|----------------                           |--------------- |----------------|-----------|
|2.1| Exportation des tables principales vers des tableaux d'un tableur et le contenu du résultat de vos requêtes | > 2 hours  |  in progress | [ ] exporter la base en .csv <br/>[ ] résultat des requête dans un tableau excel
|2.2| Pour chacune des interrogations demandées, créez un script contenant la ou les requêtes nécessaires | > 1 jour  |   in progress | [ ] requêtes 5.
|2.2.1| chiffre d'affaires hors taxes généré pour l'ensemble et par fournisseur | > 5 hours  |  in progress | [ ] chiffre d'affaire HT global<br/>[ ] chiffre d'affaire HT par fournisseur
|2.2.2| liste des produits commandés pour une année sélectionnée  | > 5 hours  |  in progress | [ ] procédure list_order_products
|2.2.3| liste des commandes pour un client | > 5 hours  | in progress | [ ] procédure list_order_customers
|2.2.4| répartition du chiffre d'affaires hors taxes par type de client | > 5 hours  |  in progress | procédure revenue_by_type_of_customer
|2.2.5| lister les commandes en cours de livraison | > 5 hours  | in progress | [ ] requête délai de livraison


# Programmer des procédures stockées sur le SGBD - 2 days :
| Mission 3     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|3.1| Qui renvoie le délai moyen entre la date de commande et la date de facturation | > 1 jours | in progress | [ ] créer procédure
|3.2| Gérer les vues | > 5 hours |  in progress | [ ] vue jointure Produits - Fournisseurs


# Construire la maquette de l'application - 4 days :
| Mission 4     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|4.1| Diagramme de cas d'utilisation d'une commande sur le site par un client particulier | > 2 days | in progress | [ ] diagramme commande <br/> [ ] panier
|4.2| Réaliser la maquette de la page de connexion du site | > 2 days | in progress | [ ] maquette connexion

# Développer une application web - 10 days :
| Mission 5     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|5.1| Réalisez un site e-commerce pour les clients | > 5 hours | in progress | [ ] consulter le catalogue <br/> [ ] saisir de nouvelles commandes <br/> [ ] visualiser les anciennes commande
|5.2| Développer des pages web statiques (HTML/CSS) 10 jours | > 7 days | in progress | [ ] index <br/> [ ] formulaire d'inscription <br/> [ ] catalogue <br> [ ] panier <br/> [ ] interface administrateur
|5.3| Création d'un formulaire d'inscription pour le client | > 5 hours [ ] formulaire inscription
|5.4| Vérification de la saisie utilisateur | > 2 days | in progress | [ ] script vérification formulaire

# Développer des composants web d'accès aux données - 18 days :
| Mission 6     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|6.1| Gestion du CRUD | > 8 days | in progress | [ ] formulaire ajout produit <br/> [ ]formulaire update produit <br/> [ ] formulaire delete produit
|6.1.2| Affichage panneaux administrateur | > 2 days | in progress | [ ] créer interface administration
|6.1.3| Mise en place du Framework MVC | > 8 days | in progress | [ ] création des controler <br/> [ ] creation model <br/> [ ] création des vues <br/> [ ] tests unitaires

# Mettre en œuvre une solution de gestion de contenu ou d'ecommerce - 14 days :

Dans le cadre de sa stratégie S.E.O., la société Village Green veut développer du marketing de contenu autour des produits qu'elle commercialise via un blog en Wordpress (articles sur les nouveaux produits, tests, vulgarisation technique, vie de l'entreprise etc.).

| Mission 7     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|7.1| Réaliser un thème responsive qui reprend les grandes lignes de la charte graphique du site e-commerce | > 10 days | in progress | [ ]index [ ]blog [ ]formulaire d'inscription
|7.2| Rôle utilisateur | > 1 days | in progress | [ ] privilèges employés
|7.3| Configuration plugin S.E.O. | > 1 days | in progress | [ ] choix plugin S.E.O. [ ] configuation plugin S.E.O.
|7.4| La sécurité devra bien sûr être prise en compte | > 1 days | in progress | [ ] création compte admin <br/> [ ] mise en place sauvegarde <br/> [ ] configuration de plugin de sécurité
|7.5| Test des fonctionnalité du blog | > 1 days | in progress | [ ] publier un article <br/> [ ] valider articles

# Publication de l'application - 2 days :
| Mission 8     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|8.1| hébergement projet fil rouge (e-commerce,wordpress) sur le compte dev.amorce.org | > 1 days | in progress | [ ] hébergement e-commerce <br/> [ ] hébergement blog
|8.2| Tester pour voir les erreurs et les corrigées | > 1 days | in progress | [ ] voir les erreurs <br/> [ ] corriger les erreurs