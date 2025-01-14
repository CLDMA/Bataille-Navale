# Bataille Navale

## Description

Le jeu bataille Navale est un jeu classique de bataille navale codé en Python avec une interface graphique construite avec Tkinter. Le projet est structuré en plusieurs modules, chacun gérant des fonctionnalités spécifiques pour qu'il puisse être lisible et clair.

## Structure du Projet

Le code est organisé en plusieurs modules et un fichier principal comme suit :

- **`navire.py`** : Contient la classe `Navire`, représentant un navire dans le jeu
- **`plateau.py`** : Contient la classe `Plateau`, gérant le plateau de jeu
- **`joueur.py`** : Contient la classe `Joueur`, gérant les joueurs et leurs actions
- **`interface.py`** : Contient la classe `ApplicationBatailleNavale`, gérant l'interface utilisateur et les interactions avec Tkinter
- **`main.py`** : Initialise l'application et démarre le jeu

## Détails des Modules

### navire.py

Ce module définit la classe `Navire`, qui représente un navire dans le jeu

- **Attributs** :
  - `nom` : Nom du navire
  - `taille` : Taille du navire
  - `positions` : Liste des positions du navire sur le plateau
  - `positions_touchees` : Ensemble des positions du navire qui ont été touchées

### plateau.py

Ce module définit la classe `Plateau`, qui gère le plateau de jeu

- **Attributs** :
  - `taille` : Taille du plateau (10x10)
  - `grille` : Représentation de la grille du plateau
  - `navires` : Liste des navires placés sur le plateau

### joueur.py

Ce module définit la classe `Joueur`, qui représente un joueur dans le jeu

- **Attributs** :
  - `nom` : Nom du joueur
  - `plateau` : Plateau de jeu associé au joueur
  - `est_humain` : Booléen indiquant si le joueur est humain

### interface.py

Ce module contient la classe `ApplicationBatailleNavale`, qui est la classe principale pour l'interface utilisateur du jeu. Elle gère la création des grilles, les interactions avec l'utilisateur et le déroulement du jeu via Tkinter
