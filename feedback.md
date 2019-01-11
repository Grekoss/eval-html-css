# Feedback du prof

## Test Menu

### Enoncé

- 5 liens
- Lien "Blog" actif
- Changement d'état au survol

### Notions

- [x] Création d'un élément `<nav>` pour la sémantique
- [x] Organisation des liens dans une liste (1x `<ul>` et 5x `<li>`)
- [x] Classe CSS spécifique pour le lien "actif"
- [x] Utilisation de la pseudo-classe `:hover` pour le survol

### Commentaires

- Il fallait bien penser à faire un effet lors du survol avec la souris (`:hover`)
- Graphiquement, la partie "Menu" ne colle pas parfaitement à la créa fournie

### Corrections

- Ajout de l'utilisation de la pseudo-classe `:hover`

## Test Articles

### Enoncé

- 4 Articles
- Les images de gauche prennent toute la hauteur de l'article
- 1 lien vers chaque catégorie liée
- Changement d'état de chaque lien "catégorie" au survol
- 2 liens vers les réseaux sociaux
- Changement d'état des liens "réseaux sociaux" au survol
- Afficher la date de publication en haut à droite
- Afficher la catégorie et les réseaux sociaux en bas, quelque soit la hauteur de l'article
- Alterner les triangles bordant le dessous des articles
- Afficher une ombre autour de l'article

### Notions

- [x] Utilisation des balises `<section>` et/ou `<article>`
- [x] Utilisation de `flex` pour afficher l'image de gauche en `stretch`
- [x] Design du bouton "catégorie" (background, uppercase)
- [x] Design du bouton "réseaux sociaux" (border-radius, background)
- [x] Utilisation de la pseudo-classe `:hover` pour le survol
- [x] Utilisation de `flex` en direction `column` + `space-between` pour positionner la date, le texte et les liens en bas, sinon avec des `position:absolute;`
- [x] Triangle rose ou bleu avec la pseudo-classe `:nth-child(even)` pour les "pairs" et `:nth-child(odd)` pour les "impairs", sinon, avec 2 classes CSS
- [x] Ombre avec la propriété `box-shadow`

### Commentaires

- Beaucoup de `flex` dans cette partie :wink:
- Il fallait bien penser à faire un effet lors du survol avec la souris (`:hover`)
- Pour être certain que la date soit en haut, le texte au milieu et les liens en bas, le plus simple est d'afficher en `flex` et de changer la direction en `column`. Peu importe la longueur du date, le résultat sera toujours correct
- Tu n'as pas dû voir l'ombre sur l'article :/
- Sinon RAS :ok_hand:

### Corrections

- Ajout de l'utilisation de la pseudo-classe `:hover` pour les catégories
- Utilisation de `flex` et `flex-direction: column` dans le container de l'article.
- Ajout du `box-shadow`, lors de l'évalution je n'avais pas fait attention à ce détail.

## Test Gabarit

### Enoncé

- Image en arrière-plan
- Le contenu ne colle pas les bords de la fenêtre
- Le logo est placé en haut à gauche
- Un bouton standard (suivant)
- Changement d'état du bouton standard au survol (précédent)

### Notions

- [x] Utilisation des 3 balises sémantiques principales `<header>`, `<main>` et `<footer>`
- [x] Propriétés CSS dans un fichier séparé du HTML + import avec `<link>`
- [x] Utilisation de la font `WeDrive`
- [x] Image en background et répétée sur le `<body>`
- [x] Un "container"/"wrapper" ou un `<main>` avec une propriété `max-width` + `margin:auto;`
- [x] Logo hors du flux avec `position:absolute;`
- [x] Bouton standard avec coins arrondis grâce à `border-radius`
- [x] Bouton standard avec les textes en majuscule grâce à `text-transform`
- [x] `background-color` change sur les boutons standards au survol avec la pseudo-classe `:hover`
- [x] Chargement des fichiers Javascript en bas de page

### Commentaires

- RAS :ok_hand:

## Test Footer

### Enoncé

- Barre horizontale de séparation
- A gauche :
  - le texte du copyright
  - le nom de l'agence
- A droite :
  - 4 liens

### Notions

- [x] Utilisation de `flex` ou `CSS Grid` sinon `float`, pour les 2 colonnes (gauche et droite)
- [x] `border-top` pour la barre horizontale
- [x] Utilisation du code HTML ou Unicode pour le &copy;
- [x] Création d'un élément `<nav>` pour la sémantique
- [x] Organisation des liens dans une liste (1x `<ul>` et 4x `<li>`)

### Commentaires

- Graphiquement, ça ne ressemble pas exactement à la créa
- Sinon RAS :ok_hand:

## Test Responsive

### Enoncé

- Rendre le site "Responsive"
- Optimiser l'affichage selon plusieurs breakpoints
- Sur des écrans plus petits, le contenu central colle les bords de la fenêtre

### Notions

- [x] Balise meta pour le viewport : `<meta name="viewport" content="width=device-width, initial-scale=1">`
- [x] Utilisation de 3 breakpoints ou plus (`@media (min-width:768px) { ... }`)
- [x] Définition des propriétés CSS en "Mobile First"
- [x] Optimisation de l'affichage pour mobile
- [x] Optimisation de l'affichage pour tablet
- [x] Optimisation de l'affichage pour desktop
- [x] Menu burger en mobile

### Commentaires

- Les 3 appareils à prendre en compte en Responsive, au minimum, ce sont mobile, tablet et desktop
- La version tablet n'était pas assez optimisée, dommage :(
- En mode mobile, voire tablet, on ne peut pas garder l'image à côté du texte dans les articles, car on n'a pas assez de pixels disponibles en largeur
- Le top pour la navigation en mode mobile, c'est de mettre en place un menu "Burger" et c'est beaucoup plus simple avec Bootstrap :wink:
- En mode "mobile", on va d'abord afficher les liens du footer, puis, en dessous, le copyright
- Sinon RAS :ok_hand:

### Correction

- Ajout du menu "Burger" avec Bootstrap pour le mode "mobile"
- Modification de la taille tablette qui était mal renseigné

## Général

- [x] Utilisation de balises HTML avec valeur sémantique
- [x] Précision des ciblages/selectors
- [x] Utilisation de préfixes (compatibilité avec anciens navigateurs)
- Qualité du code
  - [x] indentation et lisibilité du code
  - [x] Présence de commentaires dans le code
- Options
  - [x] Utilisation de transformations / animations

### Commentaires

- Très bonne évaluation, bravo :clap:
- Ok, tu n'as pas tout réalisé, mais ça ressemble globalement à la créa. Si tu as le temps, essaie de terminer cette éval avec les indications de ce feedback

### Correction

- Mise en place d'une rotation du logo sur `:hover`
- Utilisation de préfixes pour différent navigateurs ainsi que pour les anciennes versions