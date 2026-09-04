# Maquette Nord Composites

Maquette de demonstration realisee par Collet Marketing dans le cadre d'une proposition
de refonte du site de Nord Composites. Il s'agit d'une page unique, sans back-office.

## Publier sur GitHub Pages

1. Creer un depot, par exemple `nord-composites-maquette`.
2. Deposer le contenu de ce dossier a la racine du depot (`index.html`, `assets/`,
   `robots.txt`, `.nojekyll`).
3. Dans le depot : Settings, puis Pages.
4. Source : `Deploy from a branch`. Branche : `main`, dossier : `/ (root)`. Enregistrer.
5. L'adresse est disponible en une a deux minutes :
   `https://<votre-compte>.github.io/nord-composites-maquette/`

## A savoir avant de publier

- Sur un compte gratuit, une page GitHub Pages est publique. N'importe qui disposant
  de l'adresse peut la consulter. Un `noindex` et un `robots.txt` sont deja en place
  pour eviter que la page ne remonte dans les moteurs de recherche, mais ce n'est pas
  une protection d'acces.
- Les visuels sectoriels sont des photos d'illustration. Les photos des sites de
  production, le logo et la video appartiennent a Nord Composites et ne sont utilises
  ici que pour la presentation commerciale.
- Les contenus techniques (normes, gammes, chiffres de production) proviennent du site
  actuel de Nord Composites et doivent etre valides par leur service technique avant
  toute mise en ligne definitive.

## Structure

    index.html     la page complete, styles et scripts inclus
    assets/        photos des secteurs, des sites de production et de l'equipe
    robots.txt     blocage de l'indexation
    .nojekyll      desactive le traitement Jekyll de GitHub Pages

## Modifier la palette

Les couleurs sont centralisees dans le bloc `:root` en haut du `<style>` de `index.html`.
`--bleu` correspond au bleu de marque Nord Composites (#0095DB, legerement assombri pour
la lisibilite du texte blanc sur les boutons).
