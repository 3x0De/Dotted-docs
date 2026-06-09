## API

Le backend de `Dotted` est une API développée avec FastAPI (Python).

Elle agit comme couche centrale entre le frontend et la base de données PostgreSQL.

## Rôle

- Communiquer avec la base de données

## Architecture interne

L’API est structurée de manière modulaire :

- **Routes** : définition des endpoints HTTP
- **Database** : accès et requêtes PostgreSQL

## Endpoints (exemples)

| Endpoints                   | Utilisation                    |
| --------------------------- | ------------------------------ |
| `GET /con`                  | vérifier une connection        |
| `POST /initProj`            | Initaliser une page            |
| `GET /Cont/{IDPAGE}`        | récupérer une page             |
| `POST /Modif/Cont/{IDPAGE}` | Modifier le contenu d'une page |
