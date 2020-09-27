# Tarot confiné
Pour jouer au tarot, comme en vrai, avec ses amis en réseau.
On peut jouer à 3, 4 ou à 5, avec appel du roi ou avec un mort.

## Aspect technique
Le code est testé avec Python 3.7.7, on a besoin des modules pysimplegui, pillow et numpy.

## Préparation de la partie

- Dans le menu Serveur, on peut soit créer une partie, soit joindre une partie existante.
Quand on crée une partie, on peut choisir le port (12800 par défaut). Si on souhaite jouer sur internet, il faut connaître son IP externe, activer la redirection de ports sur son routeur et éventuellement déactiver le pare feu sur le port utilisé.
Si on veut simplement tester le soft, on peut demander de joueur tout seul.

- Quand on joint une partie, il faut indiquer l'adresse du serveur et le port (donnés par celui qui a créé la partie).

Dans les deux cas, il faut indiquer son nom, que les autres joueurs verront, on peut modifier ce nom en cours de partie.

## La partie

Ensuite le jeu démarre. Chaque joueur se voit proposer une ou des actions possibles quand c'est son tour.

Bon jeu !
