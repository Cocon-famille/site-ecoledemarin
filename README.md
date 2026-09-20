# site-ecoledemarin

Charte de marque officielle de l'École de Marin — un document imprimable en 9 pages A4 (couverture, mission, logo, interdits, couleurs, typographie, ton de voix, papeterie, diplôme).

Implémenté en HTML/CSS statique, sans dépendance ni étape de build, pour un déploiement direct sur Vercel.

## Structure

- `index.html` — les 9 pages du document
- `styles.css` — mise en page, typographie et styles d'impression

## Aperçu

Ouvrir `index.html` dans un navigateur. Chaque page est au format A4 (210mm × 297mm) ; l'impression du navigateur (`Cmd/Ctrl+P`) produit directement le PDF final grâce aux règles `@page`.

## À faire

La case « Version dessinée » du logo (page 3) attend le vrai dessin de Marin — remplacer le `.image-slot` dans `index.html` par une balise `<img>` une fois le scan disponible.
