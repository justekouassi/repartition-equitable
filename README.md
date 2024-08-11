# Problème de répartition équitable de bonus

Dans le cadre de l'évaluation des performances de ses élèves, un enseignant souhaite ajuster les moyennes afin de garantir que tous les élèves valident la matière enseignée. Le tableau ci-dessous présente les moyennes actuelles des élèves, notées sur 20 :

|N°|Noms|Moyennes|
|:-:|:-:|:-:|
|1|Juste|19|
|2|Souley|15|
|3|Ange|13|
|4|David|9|
|5|Aya|8|
|6|Kouakou|4|

Dans cet établissement, la moyenne minimale requise pour valider une matière est fixée à 8 sur 20. Or, Kouakou, ayant obtenu une moyenne de 4, n’atteint pas ce seuil. Soucieux de la réussite de tous ses élèves, l'enseignant envisage d'ajouter un bonus de +4 à la moyenne de Kouakou pour le ramener à 8, le seuil de validation.

Cependant, cette décision suscite des mécontentements parmi les autres élèves, qui estiment mériter un ajustement similaire pour maintenir l'équité des résultats. Ces élèves souhaitent ainsi recevoir un bonus proportionnel tout en conservant les écarts existants entre leurs moyennes. Néanmoins, l'application d'un bonus de +4 à la moyenne de Juste, qui est actuellement de 19, entraînerait une moyenne de 23, ce qui excède le maximum autorisé de 20, rendant la situation incohérente.

Le défi consiste donc à redistribuer les bonus de manière équitable, en permettant à chaque élève de valider la matière tout en respectant les contraintes suivantes :
- La moyenne de validation doit être comprise entre 8 et 20.
- Les moyennes actuelles des élèves varient entre 4 et 19.
- La plage de bonus applicables est donc comprise entre +1 et +4.
- La difficulté : faire en sorte que [4, 19] + [1, 4] -> [8, 20]

Cette situation illustre un problème plus général de répartition équitable de ressources dans un groupe tout en respectant des limites prédéfinies.

