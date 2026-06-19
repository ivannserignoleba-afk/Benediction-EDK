# Salon de coiffure Daloa

Site web pour les salons de coiffure femmes et hommes à Daloa.

## Fonctionnalités

- Formulaire d'inscription pour les coiffeurs et coiffeuses
- Affichage des salons inscrits
- API Node.js/Express pour enregistrer et lire les salons
- Page d'administration pour supprimer des salons

## Lancer le projet

1. Installer les dépendances :

```powershell
npm install
```

2. Démarrer le serveur :

```powershell
npm start
```

3. Ouvrir dans le navigateur :

- `http://localhost:3000/`
- `http://localhost:3000/admin.html`

## Structure du projet

- `index.html` : page publique d'inscription
- `admin.html` : page d'administration
- `server.js` : API Express
- `styles.css` : styles du site
- `script.js` : logique de formulaire côté client
- `admin.js` : administration côté client
- `salons.json` : stockage local des salons
