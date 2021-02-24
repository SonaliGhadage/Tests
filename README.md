## Objective

L'objectif de l’exercice est de parser des logs de issus du serveur plan de Mappy pour en sortir des informations. Le log est constitué d'un timestamp puis d'une url qu'a reçu un serveur de plan. Les logs sont déjà rangés par ordre chronologique de timestamp (c'est garanti).
Une tuile de plan correspond à une url de la forme : /map/1.0/slab/photo/256/16/32798/22739
Dans notre cas, "photo" correspond à ce qu'on appelle le viewmode, cela va déterminer le mode d'affichage du plan. Parmi les valeurs possibles du viewmode, on retrouve : photo, standard, standard_hd (hd = haute définition), traffic, traffic_hd, etc.
L’objectif de l'exercice de sortir le nombre de viewmodes identiques qui se suivent dans les lignes avec le nombre d’occurrences. Les urls qui ne correspondent pas à une tuile doivent être ignorées.

## Solution

#### Langage de programmation - Python3
#### Framework utilisé pour écrire un code - Google Colab Notebook

#### La description :

Le code est écrit avec des commentaires pour une meilleure compréhension. Il suffit d'exécuter les cellules étape par étape pour obtenir le résultat final.

Note : Pas besoin d'installer une bibliothèque supplémentaire. Le code est écrit en utilisant des bibliothèques python de base qui sont facilement disponibles.


Les résultats sont stockés dans le fichier : parsed_logs_file.tsv

