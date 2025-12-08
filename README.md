# Déploiement et lancement de l'application web Flutter

Ce projet contient une application web Flutter servie par un serveur Express.

## Prérequis
- Node.js installé
- Les fichiers générés par Flutter (`index.html`, `main.dart.js`, etc.) doivent être présents dans le dossier `web`.

## Installation
1. Ouvrez un terminal dans le dossier `web`.
2. Installez les dépendances (si besoin) :
   ```powershell
   npm install express
   ```

## Lancement du serveur
1. Dans le terminal, lancez le serveur :
   ```powershell
   node server.js
   ```
2. Le serveur démarre sur le port 60000. Accédez à l'application via :
   - http://localhost:60000
   - ou http://127.0.0.1:60000

## Dépannage
- Si l'application n'est pas accessible, vérifiez :
  - Que le serveur affiche bien "Server running..." dans le terminal
  - Que les fichiers Flutter sont présents dans le dossier
  - Que le port 60000 n'est pas bloqué ou utilisé

## Personnalisation
- Pour changer le port, modifiez la variable `PORT` dans `server.js`.
- Pour servir un autre dossier, adaptez le chemin dans `express.static()`.

---

Pour toute question, contactez le développeur du projet.