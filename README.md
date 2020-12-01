### Projet masterclass GIT

## S'entrainer aux projets collaboratifs sur GIT

- mettez vous en groupe (au moins 2)
- faites ou refaites un exo ou amusez-vous (le contenu du dev c'est pas le principal aujourd'hui)

Les contraintes :
- pas de commit sur la branche master
- chacun bosse sur sa branche
- faites des petits commits réguliers
- mergez vos dev dans master et mettez les à dispo des autres (vous allez devoir pull/push réguilièrement)
- refaites une branche
- recommencez

## CLI

```
//Récupérer le projet initial
git clone /adresse du projet

//Créer une nouvelle branche
git branch newbranch
//Aller sur ma branche
git checkout newbranch

//Faire mes modifications, les ajouter sur ma branche
git add
git commit
git push
 
//Passer sur la branche master et me mettre à jour
git checkout master
git pull
//Merge ma branche et ajouter les modifications
git merge master newbranch
git push
//Eventuellement supprimer sa branche
git branch -D newbranch

Recommencer et rester calme !!

```
