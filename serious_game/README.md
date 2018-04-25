# Projet Unity

<p align="center"> <img src="Deckstop_icons/icon.png" alt="game_icon" height="200" width="200">
</p>

## Les consignes

Le projet Unity consiste à développer un environnement multimédia en 2D ou 3D interactif de type jeu vidéo.

Le but est de proposer un prototype d'environnement d'apprentissage basé sur les mécanismes de jeu.

### Les contraintes

-   Le jeu doit avoir une vocation éducative, pour les enfants, pour les adultes, pour les personnes âgées dans tous les domaines: culture, sciences...
-   Le jeu doit être adaptatif, c'est à dire que son fonctionnement doit s'adapter aux performances du joueur et devenir plus facile si le joueur a du mal ou plus compliqué si le joueur a trop de facilité.
-   L'outil de développement à utiliser est Unity  Il s'agit d'un moteur de jeu multi-plateforme.

### Le rendu final

Le rendu du projet consiste en un rapport exposant le but de l'application et sa structure ainsi que le projet Unity développé.
Puis, le projet donnera lieu à une courte présentation par groupe qui sera organisée pendant la session d'examen.

## Notre proposition

Pour répondre aux exigences des consignes imposer nous souhaitons réaliser un Rogue-Like 2D avec le moteur de jeu Unity qui sera destiné à apprendre à additionné des chiffres.

### Ressources utilisés

Nous allons utiliser un assortiment d'assets et de tutoriels proposés sur l'Asset Store de unity:

-   [2D Roguelike tutorial](https://unity3d.com/fr/learn/tutorials/s/2d-roguelike-tutorial)
-   [Tutoriels Vidéos](https://www.youtube.com/watch?v=Fdcnt2-Jf4w&list=PLX2vGYjWbI0SKsNH5Rkpxvxr1dPE0Lw8F)

### But du jeu

Notre je prends place dans un univers post-apocalyptique où apparemment notre protagoniste est chassé par des Zombies. Pour aider à leur échapper le joueurs doit faire l'addition des deux tuiles spéciales sur la grille pour trouver la bonne sorti; puis trouver le chemin vers la bonne sorti qui évite au plus les Zombies et qui permet de ramasser le plus de nourriture.

La nourriture sera notre vie. On peut en perdre en se faisant attaquer par les zombies (-10) ou bine en se déplaçant (-1) ou bien encore en prenant une mauvaise sortie (int(food/2) + 1). Si le protagoniste n'a plus de nourriture il meurt et c'est la fin du jeu (La partie est perdu).

Au bout d'un certain nombre de niveau le jeux se finira (Environ 20 à décider). La partie sera gagner!

## ToDo:

| What to do ?                                               | Who done this ? | When was it done ? | Remarques                                                  |
| ---------------------------------------------------------- | :-------------: | :----------------: | ---------------------------------------------------------- |
| [Project Introduction](https://youtu.be/Fdcnt2-Jf4w)       |       Enzo      |     2018.04.12     | Il suffit de télécharger le repo github pour y avoir accès |
| [Animations](https://youtu.be/mmyr2l9dxoU)                 |       Enzo      |     2018.04.12     | RAS                                                        |
| [Tile Prefabs](https://youtu.be/3xqUo--8d0s)               |                 |                    |                                                            |
| [Board Manager](https://youtu.be/bvvaqAbpPjc)              |                 |                    |                                                            |
| [Game Manager](https://youtu.be/7NYXBUWmFvU)               |                 |                    |                                                            |
| [Moving Objects](https://youtu.be/fURWEzpNPL8)             |                 |                    |                                                            |
| [Walls](https://youtu.be/MEA4Qqpcwpg)                      |                 |                    |                                                            |
| [Player Animator Controller](https://youtu.be/iT8TSgPAykI) |                 |                    |                                                            |
| [Player Script](https://youtu.be/zyX3hxtblKY)              |                 |                    |                                                            |
| [Enemy Script](https://youtu.be/C6G8ra9ncwA)               |                 |                    |                                                            |
| [Enemy Animator Controller](https://youtu.be/36D2pACY0XI)  |                 |                    |                                                            |
| [UI & Levels](https://youtu.be/FIa7qxGaRZo)                |                 |                    |                                                            |
| [Audio](https://youtu.be/n7cdYMSlVxA)                      |                 |                    |                                                            |
| [Mobile Controls](https://youtu.be/YaL4JlUwOww)            |                 |                    |                                                            |

### Special Todo:

| What to do ?                                             | Who done this ? | When was it done ? | Remarques                                                               |
| -------------------------------------------------------- | :-------------: | :----------------: | ----------------------------------------------------------------------- |
| Créer des nouveaux sprits pour les additions             |       Enzo      |     2018.04.12     | _ Les couleurs sont bizarres il faut revoir comment l'image est sauvé _ |
| Ajouter des tuiles spéciales de nombres (floor, prefabs) |                 |                    |                                                                         |
| Ajouter des tuiles spéciales de nombres (exit, prefabs)  |                 |                    |                                                                         |
| Créer script pour additions                              |                 |                    |                                                                         |
| Ajouter nos tuiles spéciales à la grille de jeu (script) |                 |                    |                                                                         |
| Connaître nos tuiles spéciales sur la grille (script)    |                 |                    |                                                                         |
| ... _ truc manquant à venir _                            |                 |                    |                                                                         |
