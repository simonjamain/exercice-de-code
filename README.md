# exercice de code

## exercice 1 : récupération et affichage des scores

Pour cet exercice j'ai choisi de faire faire un maximum le travail par l'API de l'open data.

Le gros du code est la génération de la requête à l'api, qui ramène tous les résultats nécessaires un seul "record".

J'ai choisit de fixer avec un paramètre le nombres de candidats, il y a une methode qui peut marcher dynamiquement mais qui est très dépendante de la manière un peu bizarre dont sont définits les facets et j'ai choisit de ne pas m'y fier (il y a aussi notamment une autre methode pas très propre qui analyserai les noms des colonnes).

## exercice 2 : analyse d'un canvas

Pour cet exercice tout est fait en une seule boucle grâce à la mise à jour incrémentale de la moyenne, la méthode est testée grâce à l'exercice 1