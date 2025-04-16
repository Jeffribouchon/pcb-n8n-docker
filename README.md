# n8n - Automatisation avec Docker

Ce projet permet de lancer **n8n** (outil d'automatisation de workflows) via **Docker Compose**, avec des volumes persistants et une configuration prête à être utilisée sur un réseau local.

---

## Fonctionnalités

- Installation de n8n via Docker
- Volumes pour la persistance des données
- Authentification basique activée
- Accessible depuis d'autres machines du réseau local
- Prêt pour une extension vers reverse proxy (Traefik, Caddy...)

---

## Prérequis

- Docker & Docker Compose installés
- Ports ouverts sur la machine hôte (`5678`)
- Réseau local fonctionnel

---

## Lancer n8n

1. Clonez le projet ou copiez les fichiers
2. Lancez :

```bash
docker compose up -d
