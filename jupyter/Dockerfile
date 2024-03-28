# Utilisation de l'image de base Jupyter Notebook officielle
FROM jupyter/datascience-notebook

# Installation des packages nécessaires pour se connecter à PostgreSQL
USER root
RUN pip install psycopg2-binary sqlalchemy

# Copie des notebooks ou scripts si nécessaire
 COPY . /home/maatalla/work
