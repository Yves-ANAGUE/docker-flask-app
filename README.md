# 🐳 Docker Flask App

Une petite application Flask déployée dans un conteneur Docker.

## 🔥 Fonctionnement

L'application Flask affiche simplement un message :  
**"Bonjour à tous, Ceci est une simple application conteneurisée avec Docker par mon_nom!"** sur `http://localhost:5000`.

## 📦 DockerHub

L’image Docker de cette application est disponible ici :  
👉 https://hub.docker.com/r/yvesanague/mon_nom-flask-app

## 🧪 Lancer le projet en local

```bash
docker build -t mon_nom-flask-app .
docker run -d -p 5000:5000 mon_nom-flask-app
