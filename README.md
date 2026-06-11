# Dotted ![Dotted](assets/Dotted_full.svg)

## Let’s make point

Dotted est un logiciel de prise de
note comme l’ont pû être Notion ou
Obsidian, mais plus spécifique au
besoins de sa créatrice.

#### FEATURES

- Interface web
  - Blocks élémentaires
  - Gestion des pages
  - Gestion des utilisateurs
- API

#### ARCHITECTURE

##### Web

Interface web développée avec [Vite](https://vite.dev/) + [React](https://fr.react.dev/) + [TypeScript](https://www.typescriptlang.org/) + [Sass](https://sass-lang.com/).

##### Backend

API développée avec [FastAPI](https://fastapi.tiangolo.com/) ([Python](https://www.python.org/)).

##### Base de données

[PostgreSQL](https://www.postgresql.org/) pour la persistance des données.

##### Infrastructure

L’ensemble est conteneurisé avec [Docker](https://www.docker.com/) pour le développement et la production.

#### INSTALLATION RAPIDE

Ouvrez un terminal a la racine de ce repo

```bash
make Init # Pour la premère instalation
make
```

#### Repos

- [App web](https://github.com/3x0De/Dotted-web)
- [Backend](https://github.com/3x0De/Dotted-back)

#### Configuration globale

Frontend: http://localhost:5173  
Backend: http://localhost:8000

#### Documentation

- [Charte graphique](https://github.com/3x0De/Dotted-docs/blob/main/Charte.pdf)
- [Installation](https://github.com/3x0De/Dotted-docs/blob/main/INSTALLATION.md)
- [Architecture](https://github.com/3x0De/Dotted-docs/blob/main/ARCHITECTURE.md)
- [Developement](https://github.com/3x0De/Dotted-docs/blob/main/DEVELOPMENT.md)
- [Deployment](https://github.com/3x0De/Dotted-docs/blob/main/DEVELOPEMENT.md)
- [Changelog](https://github.com/3x0De/Dotted-docs/blob/main/CHANGELOG.md)
  - [Web](https://github.com/3x0De/Dotted-web/blob/main/CHANGELOG.md)
  - [Backend](https://github.com/3x0De/Dotted-back/blob/main/CHANGELOG.md)
- [Licence](https://github.com/3x0De/Dotted-docs/blob/main/LICENSE)
- [FAQ](https://github.com/3x0De/Dotted-docs/blob/main/FAQ.md)
