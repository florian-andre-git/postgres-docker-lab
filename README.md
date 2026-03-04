# postgres-devops-lab

Lab PostgreSQL reproductible en local avec **Docker Compose** (volume persistant + healthcheck) et **pgAdmin** (optionnel).

## Prérequis
- Docker + Docker Compose (plugin `docker compose`)
- Port `5432` libre (PostgreSQL)
- Port `8080` libre (pgAdmin)

## Démarrage rapide

```bash
docker compose up -d
docker compose ps
