# ARCHITECTURE

## Vue d’ensemble

`Dotted` est une application web composée de trois parties principales :

- un frontend web
- une API backend
- une base de données

## Frontend

| Plateforme | Technos                 |
| ---------- | ----------------------- |
| Web        | `Vite` + `React` + `Ts` |

## Architecture globale

    Utilisateur
        ↓
    Frontend
        ↓ HTTP
    Backend (FastAPI)
        ↓ SQL
    PostgreSQL

## Client

La page web est une application web développée avec Vite et React.

Rôle :

- Interface utilisateur
- Gestion de l’état de l’application
- Communication avec l’API via HTTP

## Backend

Le backend est une API développée avec FastAPI (Python).

Rôle :

- Communication avec la base de données

## Base de données

PostgreSQL est utilisé pour la persistance des données.

Rôle :

- stockage des utilisateurs
- stockage des pages / contenus
- accès via requêtes SQL
