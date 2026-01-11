# eLearning Platform - DyanGo

[![Django](https://img.shields.io/badge/Django-5.0+-green?logo=django)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Plateforme d'apprentissage en ligne moderne construite avec **Django** et le template **eLEARNING** de HTML Codex.

## Aperçu

![Page d'accueil](screenshots/home.png)
*(Ajoute ici une belle capture d'écran de la page d'accueil une fois le projet lancé)*

Fonctionnalités principales :
- Design responsive moderne et professionnel
- Carousel animé + sections wow effects
- Pages : Accueil, À propos, Cours, Formateurs, Témoignages, Contact
- Inscription (page register prête à être développée)
- Gestion des fichiers statiques (CSS, JS, images) avec Django

## Technologies utilisées

- **Backend** : Django 5.0+ (Python 3.10+)
- **Frontend** : HTML5, CSS3, Bootstrap 5, Font Awesome, Animate.css, Owl Carousel, WOW.js
- **Base de données** : SQLite (par défaut – facile à changer pour PostgreSQL)
- **Gestion des fichiers statiques** : Django staticfiles

## Prérequis

- Python 3.10 ou supérieur
- pip
- virtualenv (recommandé)

## Installation rapide

```bash
# 1. Cloner le projet
git clone https://github.com/ton-username/elearning-platform.git
cd elearning-platform

# 2. Créer et activer l'environnement virtuel
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows

# 3. Installer les dépendances
pip install -r requirements.txt

# 4. Appliquer les migrations (si tu as ajouté des modèles plus tard)
python manage.py migrate

# 5. Lancer le serveur
python manage.py runserver
