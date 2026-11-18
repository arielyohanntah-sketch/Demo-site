# T&A Rénovation — Site web

Site vitrine statique (HTML/CSS/Bootstrap) pour l'agence de rénovation **T&A Rénovation**.

## Structure du projet

```
.
├── index.html            # Redirection vers pages/index.html
├── README.md
├── assets/
│   └── images/           # Toutes les images du site
└── pages/
    ├── index.html        # Accueil
    ├── a-propos.html     # À propos
    ├── prestations.html  # Prestations
    ├── projets.html      # Projets
    ├── contact.html      # Contact
    ├── projet-cuisine.html
    ├── projet-salle-de-bain.html
    └── projet-interieur.html
```

## Utilisation

Aucune compilation n'est nécessaire. Ouvrez simplement `index.html` (ou `pages/index.html`) dans un navigateur.

Les dépendances (Bootstrap, Bootstrap Icons, Google Fonts) sont chargées via CDN.

## Notes

- Les images sont regroupées dans `assets/images/`.
- Les pages HTML sont dans `pages/`.
- `index.html` à la racine redirige automatiquement vers `pages/index.html`.
