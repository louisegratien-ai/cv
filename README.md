# CV – Louise Gratien

Mon CV de développeuse web, codé à la main en HTML/CSS (sans framework), pour ma recherche d'alternance.

## Ce que montre le projet

- **Mobile first** : la version de base est pensée pour le téléphone, une media query passe en mise en page « ordinateur »
- **Impression A4** : `@page` et `@media print` pour exporter un PDF d'une seule page, couleurs comprises
- **Lisible par les ATS** : HTML sémantique, et la déco est dessinée en CSS (pseudo-éléments) plutôt qu'écrite dans le texte
- **CSS** : Grid et Flexbox, variables (3 couleurs), pseudo-éléments, `radial-gradient` pour les grilles de points, `clip-path` pour le triangle, animation du curseur

## Structure

```
index.html      Le contenu du CV
css/style.css   Le style : mobile, ordinateur, impression
```

## Exporter en PDF

Dans Chrome : Ctrl+P → « Enregistrer au format PDF », marges par défaut, échelle 100 %, cocher « Graphiques d'arrière-plan », décocher « En-têtes et pieds de page ».
