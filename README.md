# Bataille-Navale

Le code est structuré en plusieurs classes et fonctions réparties dans un seul fichier. Pour être lisible et clair, voici une son organisation:



Module navire.py : Contient la classe Navire pour représenter un navire
Module plateau.py : Contient la classe Plateau pour gérer le plateau de jeu
Module joueur.py : Contient la classe Joueur pour gérer les joueurs et leurs actions
Module interface.py : Contient la classe ApplicationBatailleNavale pour gérer l'interface utilisateur avec Tkinter
Fichier principal main.py : Pour initialiser l'application et démarrer le jeu






Le module "navire" représente un navire dans le jeu de la bataille navale
    - `nom` : Nom du navire
    - `taille` : Taille du navire
    - `positions` : Liste des positions du navire sur le plateau
    - `positions_touchees` : Ensemble des positions touchées du navire







Le module "plateau" représente le plateau de jeu.
    - `taille` : Taille du plateau 10x10
    - `grille` : Représentation de la grille du plateau
    - `navires` : Liste des navires sur le plateau






Le module "joueur" représente un joueur dans le jeu
    - `nom` : Nom du joueur
    - `plateau` : Plateau associé au joueur
    - `est_humain` : Booléen indiquant si le joueur est humain






Le module "interface" est la classe principale pour l'interface utilisateur du jeu de bataille navale elle gère la création des grilles, les interactions utilisateur et le déroulement du jeu.






    
