# Site professionnel de Thibault Liard

Site statique en HTML, CSS et JavaScript, conçu pour une page académique de maître de conférences.

## Fichiers

- `index.html` : contenu du site
- `styles.css` : mise en page et apparence
- `script.js` : menu mobile, thème sombre et année automatique

## Éléments à remplacer en priorité

1. L'adresse électronique `votre-adresse@unilim.fr`.
2. Les liens HAL, Google Scholar, ORCID et LinkedIn (`href="#"`).
3. Les trois publications d'exemple.
4. Les actualités d'exemple.
5. Le fichier `cv-thibault-liard.pdf`, à placer dans le même dossier.
6. Le monogramme `TL`, qui peut être remplacé par une photographie professionnelle.

## Publication sur GitHub Pages

1. Créer un dépôt GitHub, par exemple `thibault-liard.github.io`.
2. Déposer les quatre fichiers dans le dépôt.
3. Dans GitHub : Settings > Pages.
4. Choisir la branche `main` et le dossier `/root`.
5. Le site sera accessible à l'adresse indiquée par GitHub Pages.

## Prévisualisation locale

Ouvrir directement `index.html` dans un navigateur, ou lancer un petit serveur local :

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.
