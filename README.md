# 🐳 Docker Flask App

Une petite application Flask déployée dans un conteneur Docker.

## 🔥 Fonctionnement

L'application Flask affiche simplement un message :  
**"Bonjour à tous, Docker fonctionne parfaitement !"** sur `http://localhost:5000`.

## 📦 DockerHub

L’image Docker de cette application est disponible ici :  
👉 https://hub.docker.com/r/ton_dockerhub_id/mon_nom-flask-app

## 🧪 Lancer le projet en local

```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app
