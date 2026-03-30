# Newsletter Fondamentale Automatique

Workflow n8n qui agrège automatiquement les actualités d'un canal Telegram et les envoie par email via Gmail.

## Ce que fait ce workflow

1. Scrape le contenu public d'un canal Telegram via HTTP
2. Formate et synthétise les informations
3. Envoie la newsletter par **Gmail** avec la date du jour en objet

## Stack

- [n8n](https://n8n.io) — orchestration du workflow
- HTTP Request — scraping du canal Telegram public
- Gmail (OAuth2) — envoi de la newsletter

## Installation

1. Importer `workflow.json` dans votre instance n8n
2. Configurer les credentials :
   - **Gmail** : compte OAuth2
3. Adapter l'URL du canal Telegram et l'adresse email destinataire
4. Planifier l'exécution (ex : chaque matin)

## Auteur

[Jared](https://github.com/99Jared9) — Consultant automatisation & IA
