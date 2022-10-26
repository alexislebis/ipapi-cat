# ipapi-cat
Ce repo concerne le problème du chat vu lors du TP2 de IPAPI.

## Description du problème
* Un nombre infini d’étagères sont arrangées les unes au dessus des autres en quinconce ;
* Le passe temps de votre chat est de sauter d’étagère en étagère jusqu’à arriver à celle qui lui plaît le plus ;
* Physiquement, toutefois, il ne peut sauter que jusqu’à 3 étagères maximum d’un coup. S’il se trouve sur l’étagère 1, il pourra sauter soit sur la 2, soit sur la 4 ;
* Évidemment, il ne peut pas sauter sur la 3 directement, puisqu’elle est au dessus de sa tête. L’illustration à gauche résume tout cela.

## Questions

### Q1
À partir de la position de départ de votre chat (depart), et de l’étagère d’arrivée (arrivee) et **affichez** une solution possible (si elle existe). Autrement dit, le numéro des étagères par lequel votre chat pourrait passer pour aller à son étagère objectif. Retournez le nombre d’étagères qu’il emprunte.

Paramètres :
* `depart`, un entier ;
* `arrivee`, un entier ;

Sorties : 
* Le nombre d'étagères empruntées par le chat


### Q2
Vous avez réussi ? Très bien. Maintenant, sachant que votre chat est un peu comme vous (fainéant :p), vous savez qu’il va essayer de prendre le chemin le plus court. Idem, affichez le chemin que votre chat pourrait prendre, et retournez le nombre d’étagères qu’il emprunte.

Paramètres :
* `depart`, un entier ;
* `arrivee`, un entier ;

Sorties : 
* Le nombre d'étagères empruntées par le chat

Original idea from https://www.codewars.com/kata/62c93765cef6f10030dfa92b
