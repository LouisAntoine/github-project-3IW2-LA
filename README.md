# github-project-3IW2-LA

# A propos

Name : JOSEPH-ROTROU Louis-Antoine

Class : 3IW2

# Installation

Téléchargez le code sur votre machine grâce à [ce repo](https://github.com/LouisAntoine/github-project-3IW2-LA "my repo"), puis dirigez vous dans le dossier "tp design guide" afin de pouvoir lancer ce projet.

Afin de lancer le Sass de ce projet github, veuillez suivre les instructions ci-dessous :

Pour pouvoir utiliser les commandes npm, il faut avoir node d'installé sur votre machine. 
Pour verifier cela vous pouvez éxécuter la commande suivante :

```
$ node -v
$ npm -v
```
S'il n'y a aucun résultat, veuillez [installer node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm "node installation").

- Dans le terminal :
```
$ npm install node-sass

$ npm init
```
(génération de package.json)


- Dans package.json, définition d’un script de surveillance du dossier scss (dans le tableau « scripts »):
```
"scripts": {

"watch": "node-sass --watch scss -o scss"

}
```
# Lancement

- Lancement du script de surveillance dans le terminal :
```
$ npm run watch
```
