# Frontend Mentor - Solution Grille Bento

Il s'agit d'une solution pour le [défi Grille Bento sur Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Les défis de Frontend Mentor vous aident à améliorer vos compétences en codage en construisant des projets réalistes.

## Table des matières

- [Frontend Mentor - Solution Grille Bento](#frontend-mentor---solution-grille-bento)
  - [Table des matières](#table-des-matières)
  - [Aperçu](#aperçu)
    - [Le défi](#le-défi)
    - [Capture d'écran](#capture-décran)
    - [Liens](#liens)
  - [Mon processus](#mon-processus)
    - [Technologies utilisées](#technologies-utilisées)
    - [Ce que j'ai appris](#ce-que-jai-appris)
    - [Développement continu](#développement-continu)
    - [Ressources utiles](#ressources-utiles)
  - [Auteur](#auteur)

## Aperçu

### Le défi

Les utilisateurs doivent être capables de :

- Voir la mise en page optimale de l'interface en fonction de la taille de l'écran de leur appareil.

### Capture d'écran

![](https://github.com/integration2/tp2-claudielanglais/blob/main/assets/images/screencapture-127-0-0-1-5500-index-html-2026-03-05-19_38_29.png)
![](https://github.com/integration2/tp2-claudielanglais/blob/main/assets/images/screencapture-127-0-0-1-5500-index-html-2026-03-05-19_38_45.png)
![](https://github.com/integration2/tp2-claudielanglais/blob/main/assets/images/screencapture-127-0-0-1-5500-index-html-2026-03-05-19_39_03.png)

### Liens

- URL de la solution : [URL de la solution](https://www.frontendmentor.io/solutions/completed-responsive-page-using-css-grid-3D-0XXiW7L)
- URL du site en direct : [URL du site en direct](https://integration2.github.io/tp2-claudielanglais/)

## Mon processus

### Technologies utilisées

- Marquage HTML5 sémantique
- Propriétés CSS personnalisées
- Flexbox
- CSS Grid
- Workflow mobile-first 

### Ce que j'ai appris

```css
    .main {
        margin: 0 10rem 0 10rem;
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        grid-template-rows: repeat(10, 0.3fr);
    }

    .main__grid:nth-of-type(2) {
        background-image: url(../images/illustration-multiple-platforms.webp);
        background-repeat: no-repeat;
        background-size: 110%;
        padding-top: 5rem;
    }
```


### Développement continu

J'aimerai améliorer ma compréhention des rows et des columns ainsi que grid-area-template.

### Ressources utiles

- [The W3C](https://validator.w3.org/) - Cela m'a aidé pour pour écrire le HTML correctement.

## Auteur

- Site Web - [Claudie Langlais](https://github.com/claudielanglais)
- Frontend Mentor - [@claudielanglais](https://www.frontendmentor.io/profile/claudielanglais) 

