---
description: Guide de déploiement du Portfolio
---

# Comment déployer votre Portfolio en ligne

Ce guide vous explique comment mettre votre site en ligne gratuitement.

## 1. Préparation du code
Avant de déployer, assurez-vous de mettre à jour votre URL finale dans `index.html` :
- Remplacez toutes les occurrences de `https://votre-site.com` par votre future URL (ex: `https://hozalice.github.io`).

## 2. Déploiement via Netlify (Recommandé - Simple)
1. Créez un compte sur [Netlify](https://app.netlify.com/).
2. Glissez votre dossier `Portefolio` sur l'interface de déploiement manuel.
3. Allez dans `Domain Settings` pour personnaliser votre URL.

## 3. Déploiement via GitHub Pages
1. Créez un repo public sur GitHub.
2. Poussez votre code :
   ```bash
   git init
   git add .
   git commit -m "Initial deploy"
   git remote add origin https://github.com/[votre-utilisateur]/[votre-repo].git
   git push -u origin main
   ```
3. Dans GitHub : `Settings` > `Pages` > branche `main` > `Save`.

## 4. Maintenance
À chaque modification de votre code local, n'oubliez pas de "Push" sur GitHub ou de reglisser le dossier sur Netlify pour que le site en ligne se mette à jour.
