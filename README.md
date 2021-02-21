Petit dépôt ayant pour objectif de tester l'api de Kaggle.
L'objectif est de développer en local puis téléverser les notebooks ou scripts nécessitant de lourds calculs sur Kaggle afin de les y exécuter et enfin de télécharger les résultats.
Pour cela il faut que le dépôt suive la même arborescence que celle de Kaggle.

Problème :
En récupérant un notebook avec la commande `kaggle kernels pull` les sorties des cellules ne sont pas présentes.
Alors qu'en le téléchargeant depuis l'interface web elle sont incluses dans le fichier récupéré.