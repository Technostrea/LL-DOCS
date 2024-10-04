---
sidebar_position: 3
sidebar_label: Architecture Globale
---

# Architecture Globale

L’architecture de EasyRent est conçue pour être scalable, sécurisée et maintenable. Elle est composée des éléments suivants :

## Front-End

- Framework : Angular pour une interface utilisateur dynamique et réactive.
- État : NgRx pour la gestion de l’état de l’application.
- Communication : HTTPClient pour les requêtes vers l’API back-end.

## Back-End

- Serveur : Laravel pour la logique métier et la gestion des requêtes.
- Authentification : JSON Web Tokens (JWT) pour sécuriser les endpoints.
- ORM : Eloquent pour interagir avec la base de données.

## Base de Données

- SGBD : PostgreSQL pour une gestion robuste des données relationnelles.
- Schéma : Tables pour les utilisateurs, les biens, les annonces, les messages, etc.

## Outil de Synchronisation pour Agences

- API : Endpoints sécurisés pour la synchronisation des données.
- Protocole : Support des formats JSON et XML pour la compatibilité.
- TODO à compléter ...

## Infrastructure

- Hébergement : Serveurs cloud pour assurer la disponibilité et la scalabilité.
- Sécurité : Certificats SSL, pare-feu et protocoles de sécurité standard.

## Schéma de l’Architecture (Illustration)

Un schéma illustrant les interactions entre les composants front-end, back-end, base de données et outil de synchronisation serait inséré ici.
