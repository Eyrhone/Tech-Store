![output-onlinepngtools (1)](https://github.com/Eyrhone/Tech-Store/assets/141184936/6a7ec65b-abee-4bfa-b1f9-639dbbee2b2e)
# Cahier des charges - Projet Tech Store eCommerce

## 1. Introduction
Le projet consiste à développer une plateforme eCommerce pour une boutique de produits technologiques. Le système permettra aux utilisateurs de naviguer à travers une variété de produits, de passer des commandes, de gérer leur panier, de suivre le statut des commandes, et plus encore. Les technologies clés utilisées incluent C# .NET 8, React, et MongoDB.

## 2. Technologies Utilisées

**Backend :**
- Langage de programmation : C# .NET 8
- Framework de développement : ASP.NET Core
- ORM : Entity Framework Core
- Base de données : MongoDB (NoSQL)
- Infrastructure : Microservices
- Messaging Queue : Apache Kafka
- Stockage de fichiers : SFTP, NAS, Amazon S3

**Frontend :**
- Framework JavaScript : React
- Langages : HTML, CSS/SCSS
- Conception : eCommerce Template - Tech Store (Community) sur Figma
- Tests : Jest, React Testing Library

**API :**
- Architecture : RESTful
- Outils : Postman, OpenAPI (Swagger)

**Tests :**
- Unitaires : Xunit
- Mutation : Stryker.NET
- PACT : Tests de contrat
- BDD : SpecFlow

**Gestion de Configuration et DevOps :**
- Contrôle de version : Git (Trunk-based)
- Orchestration de conteneurs : Kubernetes
- Conteneurisation : Docker
- Qualité de code : SonarQube
- Métriques et monitoring : Grafana, Zabbix, Prometheus

## 3. Bonnes Pratiques et Méthodologies

- Architecture : Clean Architecture, DDD
- Programmation : Orientée Objet
- Design Pattern et Principes : SOLID
- Méthodologie de Gestion de Projet : Agile (SCRUM)

## 4. Fonctionnalités du Système
Le système devra permettre aux utilisateurs de :

- Consulter les produits disponibles
- Ajouter des produits au panier
- Gérer le panier (mise à jour, suppression, etc.)
- Créer et gérer un compte client
- Gérer les adresses clients
- Utiliser une Wishlist
- Se connecter à un compte client
- Rechercher des produits
- S'inscrire/désinscrire à la newsletter
- Passer des commandes
- Gérer les retours produits
- Suivre le statut des commandes
- Utiliser un formulaire de contact
- Simuler des paiements de commandes
- Consulter une FAQ
- Ajouter des avis sur les produits

## 5. Définition des Objets Métiers

- Produits
- Types de produits
- Panier
- Client
- Wishlist
- Historique d'envoi de newsletters
- Commande
- Retours
- Type de statut de commande
- Contact
- Paiement
- Types de paiements
- FAQ
- Marques
- Avis
- Tags
- Adresse client
- Type de réductions
- Code promotionnel
