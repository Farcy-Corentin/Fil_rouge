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
|3.2.1| Qui renvoie le délai moyen entre la date de commande et la date de facturation | > 5 hours | in progress | [ ]créer procédure
|3.3| Gérer les vues | > 5 hours |  in progress | [ ] vue jointure Produits - Fournisseurs


# Construire la maquette de l'application - Time :
| Mission 4     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|4.1| Diagramme de cas d'utilisation d'une commande sur le site par un client particulier | > 5 hours | in progress | [ ]diagramme commande [ ]panier
|4.2| Réaliser la maquette de la page de connexion du site | > 5 hours | in progress | [ ]maquette connexion

# Développer une application web - Time :
| Mission 5     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|5.1| Réalisez un site e-commerce pour les clients | > 5 hours | in progress | [ ]consulter le catalogue [ ]saisir de nouvelles commandes [ ]visualiser les anciennes commande
|5.2| Développer des pages web statiques (HTML/CSS) 10 jours | > 5 hours | in progress | [ ]index [ ]formulaire d'inscription [ ]catalogue [ ]panier [ ]interface administrateur
|5.3| Création d'un formulaire d'inscription pour le client | [ ]formulaire inscription
|5.3.1| Vérification de la saisie utilisateur | > 5 jours | in progress | [ ]script vérification formulaire

# Développer des composants web d'accès aux données - Time :
| Mission 6     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|6.1| Gestion du CRUD | > 5 hours | in progress | [ ]formulaire ajout produit [ ]formulaire update produit [ ]formulaire delete produit
|6.1.2| Affichage panneaux administrateur | > 5 hours | in progress | [ ]créer interface administration
|6.1.3| Mise en place du Framework MVC | > 5 hours | in progress | [ ]création des controler [ ]creation model [ ]création des vues [ ]tests unitaires

# Mettre en œuvre une solution de gestion de contenu ou d'ecommerce - Time :

Dans le cadre de sa stratégie S.E.O., la société Village Green veut développer du marketing de contenu autour des produits qu'elle commercialise via un blog en Wordpress (articles sur les nouveaux produits, tests, vulgarisation technique, vie de l'entreprise etc.).

| Mission 7     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|7.1| Réaliser un thème responsive qui reprend les grandes lignes de la charte graphique du site e-commerce | > 5 hours | in progress | [ ]index [ ]blog [ ]formulaire d'inscription
|7.2| Rôle utilisateur | > 5 hours | in progress | [ ]privilèges employés
|7.3| Configuration plugin S.E.O. | > 5 hours | in progress | [ ]choix plugin S.E.O. [ ]configuation plugin S.E.O.
|7.4| La sécurité devra bien sûr être prise en compte | > 5 hours | in progress | [ ]création compte admin [ ]mise en place sauvegarde [ ]configuration de plugin de sécurité
|7.5| Test des fonctionnalité du blog | > 5 hours | in progress | [ ]publier un article [ ]valider articles

# Publication de l'application - Time :
| Mission 8     | Taches                                    | Time required | Current Status | Finished |
|---------------|----------------                           |--------------- |----------------|-----------|
|8.1| hébergement projet fil rouge (e-commerce,wordpress) sur le compte dev.amorce.org | > 5 hours | in progress | [ ]hébergement e-commerce [ ]hébergement blog
|8.2| Tester pour voir les erreurs et les corrigées | > 5 hours | in progress | [ ]voir les erreurs [ ]corriger les erreurs