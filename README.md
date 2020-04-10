## Introduction

This repository contains notebooks used during livestrea. The first family is about learning an AI to learn chess. It is accessible inside the chess directory

## Comprehension de la librairie python-chess

C'est la premiere etape, qui consiste a savoir representer nos parties d'echcs graca a python.
La seconde etape sera de representer les parties d'echecs pour entrainer une IA correctement :)

## Comment comparer deux positions entre elle?
## -> En associant une valeur numerique a chaque position!!
Le but est de savoir quelle est la meilleur position entre deux position. Pour cela la mchine peut comparer deux "valeurs"associees a la position


## Est ce que j'ai tout les elements pour entrainer mon IA?

- [x] representer la position d'une partie d'echecs sous forme de matrice numpy 
- [x] la liste de tout les coups possibles pour une partie d'echecs (case a to case b etc..)
- [x] connaitre la liste des coups valides pour une position existante (`list(board.legal_moves)`)
- [x] Definition d'un mini modele qui prevoit valeur et une probabilite pour chaque coup (je fais ca maintenant)
