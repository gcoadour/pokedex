## Prérequis:
- Avoir un IDE d’installer (ex: [vscode](https://code.visualstudio.com/download) )

- Avoir un compte Github. Créer un nouveau repo **PUBLIC** et le cloner sur son poste

- Installer la dernière version de [nodeJs](https://nodejs.org/en)

- Installer angular CLI (utiliser la dernière version: 19)

```npm install -g @angular/cli```

<ins>  Rappel: </ins> 
Pour créer un nouveau projet

```ng new <mon_projet>```

## Description:
Dans le cadre de ce test, vous allez devoir créer un Pokedex. 
Celui-ci aura comme fonctionnalitées:
- La recherche d’un Pokemon par nom avec de l’autocomplétion
- Un bouton permettant de lancer la recherche
- Le résultat affiche l’image du Pokemon ainsi que la liste de ses compétences (abilities)
- D’être responsive

Intégrer la maquette suivante: 
￼![](https://github.com//gcoadour/pokedex/raw/master/img/maquette.png)

Attention: Pour cela vous aurez comme contrainte devoir utiliser les composants Angular Material (https://material.angular.io/guide/getting-started) 
ET la programmation réactive (Observable et/ou Signal).

:warning: Ne PAS se servir d’une IA (ex: copilot/chatgtp/mistral/etc) :warning:

## Accès à l’API:

Le site http://pokeapi.co/ propose une API contenant de nombreuses informations sur les pokemon. 
En particulier, l'API offre la liste des pokemon (api/v2/pokedex/1) ainsi que des informations détaillées pour chacun d'entre eux (api/v2/pokemon/54 ou api/v2/pokemon/psyduck). 
Nous allons utiliser cette API comme source d'information pour notre pokédex.

## Pour aller plus loin :rocket: :
- Afficher les évolutions du Pokemon via l’api: /api/v2/pokemon-species/<nom-pokemon> . Dans le résultat, la propriété evolution_chain comporte cette donnée
- Faire en sorte que les évolutions soient selectionnable et lors du clique sur celles-ci , ouvrir la page du Pokemon.

## Fin du projet:
Pousser votre code sur votre repo public GitHub	
