# Aperçu

![Preview](https://ibb.co/D54GJyV "Touhou-Triple-Triad-Preview")

# Etapes d'installation

## Linux

* Il vous suffit d'extraire l'archive en faisant depuis votre terminal:

**tar zxvf "Touhou Triple Triad.tar.gz"**

* Vous aurez un dossier "touhou_triple_triad", ouvrez le puis ensuite lancer le script "touhou_triple_triad.sh" depuis votre terminal en faisant:

**./touhou_triple_triad.sh**

Si jamais il y a un problème de permission, faites:

**chmod u+x touhou_triple_triad.sh**

Puis ensuite:

**./touhou_triple_triad.sh**

Cette commande permet d'accorder la permission d'exécuter le script.

Bonne partie à vous et n'oubliez pas de donner votre avis sur le jeu ^^ et d'apporter votre soutien aux créateurs.

## Windows

* Il vous suffit d'extraire l'archive grâce à un logiciel d'archivage, Winrar est par exemple assez simple d'utilisation

* Une fois extrait, vous aurez un dossier "Touhou Triple Triad", ouvrez-le et pour lancer le jeu, faites double clic sur touhou_triple_triad.exe 

Bonne partie à vous et n'oubliez pas de donner votre avis sur le jeu ^^ et d'apporter votre soutien aux créateurs.

# Règles du jeu

## Règle générale

La règle générale répresente le principe le plus basique du jeu Touhou Triple Triad(basé sur le concept de Triple Triad que nous avons modifié à notre sauce ^^).
Chaque joueur possède 8 cartes et chacun son tour ils doivent poser une carte sur le plateau 4x4 et ce jusqu'à l'avoir totalement rempli.
Chaque joueur possède une couleur attribuée, les cartes du joueur 1 sont de couleur bleue, ceux du joueur 2 sont de couleur rouge et pour chaque carte de sa couleur sur le plateau chaque joueur gagne un point.
On peut changer la couleur d'une carte adverse en posant une carte qui lui sera adjacente(en haut, à droite, en bas, à gauche) et si en fonction du côté où on lui est adjacent, le point de carte concerné(celui de la carte posée) est supérieur au sien(celui de la carte adjacente)(dans cette ordre "1-2-3-4-5-6-7-8-9-A"), ainsi le joueur qui a posé la carte gagne un point et l'autre joueur en perd un.
A la fin de la partie, le joueur avec le plus de point gagne la partie, il y a égalité si le nombre de points est le même.

## Règle "inverse"

Elle se repose sur les mêmes principes que la règle générale à la différence que l'ordre de valeur des points est inversé("A-9-8-7-6-5-4-3-2-1") non pas dès le début de la partie mais dans les 4 derniers tours de jeu(quand au moins 12 cartes sont posées sur le plateau).
**NB: La règle générale et la règle "inverse" ne peuvent être appliqués en même temps.**

## Règle "+"

Cette règle apporte un nouveau moyen pour changer la couleur d'une carte adverse.
Il suffit que lorsqu'un joueur pose une carte, il se trouve au moins deux cartes adjacentes(en haut, à droite, en bas, à gauche) dont la somme des points concernés(celui de la carte posée et celui des deux cartes adjacentes) face à face pour un côté est égale à celle de l'autre.
On peut ainsi changer la couleur de 1 à 4 cartes adverses adjacentes dont la somme de chaque côté est la même(ou la même avec la somme d'un côté avec une carte que vous possédez) ou la même deux à deux.

## Règle "identique" 

Cette règle apporte un nouveau moyen pour changer la couleur d'une carte adverse.
Il suffit que lorsqu'un joueur pose une carte, il se trouve au moins deux cartes adjacentes(en haut, à droite, en bas, à gauche) dont les points concernés(celui de la carte posée et celui des deux cartes adjacentes) face à face soient égaux.
On peut ainsi changer la couleur de 1 à 4 cartes adverses adjacentes.

## Règle "open"

Cette règle permet à chacun des joueurs de pouvoir voir les cartes de son adversaire du début à la fin de la partie.
Règle "semi-open": 
Cette règle permet de cacher au hasard à chaque joueur 4 cartes de son adversaire et ce jusqu'à ce qu'au moins 8 cartes soient posées sur le plateau.
**NB: La règle "open" et la règle "semi-open" ne peuvent être appliqués en même temps.**

# Dédicace

Un grand merci à Zuda pour son aide incroyable sur ce projet d'apprentissage autant sur le plan pédagogique que humain et moral.Gros pathead à toi ^^.