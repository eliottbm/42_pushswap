# 📊​ Push Swap

![42_pushswap](https://github.com/user-attachments/assets/d207d4b5-af7a-41f8-80a9-13b5c1c907c5)

## Présentation
Push Swap est un projet d’algorithmie de l’École 42, dont l’objectif est de développer un programme capable de trier une pile d’entiers en un minimum de coups, avec un ensemble d’opérations limitées.
Il met l’accent sur la conception et l’implémentation d’algorithmes de tri, ainsi que sur l’analyse de leur complexité et leur optimisation.

## Utilisation
```
make
# Compile l'exécutable 'push_swap'

make bonus
# Compile l'exécutable 'checker'

ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker $ARG
# ARG: liste de nombres à trier
# Retourne 'OK' si le tri a réussi
# Retourne 'KO' si le tri a échoué
# Retourne 'Error' si l'entrée est invalide (caractère non numérique, doublon)

make runtest ELM=100 RUN=50 MAX=700
# ELM: nombre d’éléments à trier
# RUN: nombre de tests à exécuter
# MAX: nombre maximum de coups autorisés
# Le script affiche alors les résultats des différents tests (moyenne, minimum, maximum, taux de réussite)
```
