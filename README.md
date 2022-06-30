[English Readme](https://github.com/gary-deshayes/projet-angular-finance/blob/develop/README.EN.md)

# Projet Finance Angular

Application web permettant de recenser toutes les dernières vidéos YouTube basée sur le domaine de la finance. 

Cette application a une partie tutoriel qui liste les tutoriels en rapport avec la finance. Une partie actualités économiques vous montrera 
les derniers sujets sur l'économie. Et une partie playlist vous permet de visionner vos vidéos préférées, modifier des playlists ou bien en créer.

## Technologies

- Angular 7
- SCSS
- Bootstrap

#### API Utilisées
- 1forge
- Youtube
- Investing

#### Widget Utilisé
- Tradingview 

## Lancement du projet
1. Avoir npm d'installé sur l'ordinateur [Lien npm](https://www.npmjs.com/get-npm)
2. npm install (installe toutes les dépendances)
3. npm install -g @angular/cli (installe la CLI Angular (nécessaire pour serve --open))
4. ng serve --open

## Modification du scss

Tous les fichiers .scss sont importés dans le 'src > app > style.scss'. Pour le compiler, la commande est la suivante :

> sass --watch src/styles.scss:src/assets/css/styles.css
