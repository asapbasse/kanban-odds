# Plateforme Kanban - Suivi des ODDS

## Description
Application de gestion de projet avec tableau Kanban en temps réel pour le suivi des Objectifs de Développement Durable (ODDS).

## Prérequis
- Docker avec containers PostgreSQL et pgAdmin (déjà en place)
- Node.js 18+
- PHP 8.1+
- Composer

## Structure
- `frontend/` : Application React avec Vite et TypeScript
- `backend/` : API Laravel avec PostgreSQL
- `docs/` : Documentation du projet
- `docker/` : Configurations Docker additionnelles si nécessaire

## Base de données
Le projet utilise les containers Docker existants :
- PostgreSQL sur le port 5432
- pgAdmin sur le port 5050

## Technologies
- Frontend : React + TypeScript + Tailwind CSS
- Backend : Laravel + PostgreSQL
- Temps réel : Pusher/Soketi
- Déploiement : Hostinger

## Planning
Projet sur 4 mois (16 semaines)

## Démarrage rapide
```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd backend
composer install
php artisan serve