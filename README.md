
# Hello Next.js (Hello World)

Projet minimal Next.js "Hello World".

Usage local

Installation et exécution (PowerShell) :

```powershell
cd C:\Users\khaal\workspace
npm install
npm run dev
```

Ouvrez http://localhost:3000 dans votre navigateur.

Déployer sur GitHub Pages (automatique)

Ce projet inclut une action GitHub qui :
- construit le site avec `next build`;
- exporte les fichiers statiques (`next export`) dans le dossier `out`;
- publie `out/` sur la branche `gh-pages` via `peaceiris/actions-gh-pages`.

La commande locale pour générer les fichiers exportés :

```powershell
npm run export
# les fichiers exportés se trouvent dans ./out
```

URL GitHub Pages (après premier déploiement): https://awik008.github.io/hello-next/

Notes
- Si vous préférez déployer sur Vercel ou Netlify, je peux configurer ça à la place.

