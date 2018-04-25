Descriptif du jeu prévu (le jeu pourra évoluer d’ici l’étape finale) : principe du jeu, gameplay, règles d’adaptivité et structure du jeu prévue : scènes, gameobjects et scripts (en indiquant leur rôle et leurs fonctionnalités).

# <center>Projet Unity</center>

<center> <img src="Deckstop_icons/icon.png" alt="game_icon" height="200" width="200">
</center>

<center>
  Groupe 30: <br>
  Seleshi Mahelet, Bachelor GSEM<br>
  Poggio Enzo, Master Informatique pour sciences humaines <br>
  Mail: [Mahelet.Seleshi,Enzo.Poggio]@etu.unige.ch
</center>

## Notre proposition

Pour répondre aux exigences des consignes, nous souhaitons réaliser un Rogue-Like 2D avec le moteur de jeu Unity qui sera destiné à apprendre à additionné des chiffres (1 à 9). Nous adressons donc notre jeu à des enfants devant apprendre à calculer rapidement.

### But du jeu

Notre je prends place dans un univers post-apocalyptique où apparemment notre protagoniste est chassé par des Zombies. Pour aider à leur échapper le joueurs doit faire l'addition des deux tuiles spéciales sur la grille pour trouver la bonne sortie; puis trouver le chemin vers la bonne sortie qui évite au plus les Zombies et qui permet de ramasser le plus de nourriture.

### Gameplay

La nourriture sera notre vie. On commence une partie avec un capital de 100 de nourriture. On peut en perdre en se faisant attaquer par les zombies (-10 ou -20) ou bien en se déplaçant (-1) ou bien encore en prenant une mauvaise sortie (int(food/2) + 1). Le joueur pourra regagner de la vie s'il ramasse certain pick up: des sodas (+20) ou des pommes (+10).

Si le protagoniste n'a plus de nourriture il meurt et c'est la fin du jeu. La partie est perdue. Au bout d'un certain nombre de niveau (une vingtaine) le jeux se finira . La partie est gagnée!

Ce rogue est un tour par tour, c'est-à-dire que tant que vous n'effectuez pas votre action les ennemies n'effectue pas la leur. Le joueur à deux types d'action: se déplacer dans une direction cardinal et casser un mur qui gène le passage.

### Nos règles d’adaptivité

La difficulté sera progressive est constante elle se base uniquement sur le nombre d'ennemies qui vont spawn au début de chaque salle.

<center> <img src="img/difficulty.png" height=70% width=400%>
</center>

### Ressources utilisés

Nous allons utiliser un assortiment d'assets et de tutoriels proposés sur l'Asset Store de unity:

-   [2D Roguelike tutorial](https://unity3d.com/fr/learn/tutorials/s/2d-roguelike-tutorial)
-   [Tutoriels Vidéos](https://www.youtube.com/watch?v=Fdcnt2-Jf4w&list=PLX2vGYjWbI0SKsNH5Rkpxvxr1dPE0Lw8F)

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
