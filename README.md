# Problème de connexion à PostgreSQL 
## Démarrage 

1. Créer un répertoire .venv
2. Installer les répendances avec `pipenv install`
3. Activer l'environnement virtuel avec `pipenv shell`
4. Démarrer les conteneurs `docker compose up -d`
5. Exécuter lws migrations avec `python manage.py migrate`
6. Tenter une connexion à la base avec `python manage.py dbshell`
