# Installation

## Prérequis

- Node.js
- npm
- Docker
- Docker Compose

## Clones

```bash
git clone https://github.com/3x0De/Dotted-web.git
git clone https://github.com/3x0De/Dotted-back.git
```

## Dépendences

#### Web

```bash
cd Dotted-web
npm install
```

#### API

```bash
cd Dotted-back
docker compose up --build
```

## Lancement

#### Page web

```bash
npm run dev
```

#### API

```bash
docker compose up
```

## Accès

- App web : http://localhost:5173
- Backend : http://localhost:8000
- Base de donnée :

```bash
docker exec -it postgres_db psql -U postgres -d app_db
```

## Notes

- Les dépendances frontend (Vite, React, Sass, @dnd-kit) sont définies dans `package.json`
- Les dépendances backend (FastAPI, uvicorn, psycopg) sont gérées par Docker
- Aucune installation globale autre que Node et Docker n’est nécessaire
