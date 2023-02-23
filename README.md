# GameEDGL

## Description

**Conception, Implémentation et Test** d'un **moteur de jeu 2D**. \
Architectures en moteurs indépendants avec système d'événements: 
- Moteur Physique
- Moteur Graphique
- Moteur de son
- Moteur "IA"
- Kernel

Implémentation d'une couche Gameplay au dessus du moteur de jeu : **Space Invaders** (en très beau !)


## Bug connu à ce jour
- certaine configuration du son sous linux 

## EQUIPE

31

GAZAIX Damien
MUSARDO Léo-Paul
ABU RABIA Heba
GUILIANI Maxime
PAPAZIAN Maxime

## Compilation

- se placer à la racine du projet
- ./gradlew run

## Tests

- se placer à la racine du projet
- ./gradlew test
- le fichier generé est dans app/build/reports/tests/test/index.html



## Generer jar (a priori deja fait)

- se placer à la racine du projet
- ./gradlew jar
- le fichier generé se trouve dans app/builds/libs/app.jar


## Generer Javadoc (a priori deja fait)

- ./gradlew javadoc
le fichier est dans app/build/docs/javadoc/index.html
