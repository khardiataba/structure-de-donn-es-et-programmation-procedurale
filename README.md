# structure-de-donn-es-et-programmation-procedurale

*Dans le fichier nommé ALGORITHM distinct_elements_sum , nous avons un algorithme en pseudocode qui calcule
la somme des éléments distincts entre deux tableaux d'entiers.
Un élément est considéré comme distinct s’il est présent dans un seul des deux tableaux (A ou B, mais pas dans les deux).
    Fonctionnalités :
Lecture des tailles et contenus des deux tableaux.
Comparaison des éléments pour identifier ceux qui sont uniques à chaque tableau.
Calcul de la somme totale des éléments distincts.
Affichage du résultat final.
 Exemple :
Si A = [1, 2, 3] et B = [3, 4, 5], alors la somme des éléments distincts est 1 + 2 + 4 + 5 = 12.
_____________________________________________________________________________________________________________

*Dans le fichier nommé FUNCTION dot_product, nous avons une fonction dot_product écrite en pseudocode, 
permettant de calculer le produit scalaire de deux vecteurs d'entiers.
     Fonctionnement :
La fonction prend deux tableaux v1 et v2, ainsi qu’un entier taille représentant la dimension des vecteurs.
Elle multiplie chaque composante correspondante des deux vecteurs.
Elle additionne tous les produits obtenus.
Elle retourne le résultat final, c’est-à-dire le produit scalaire.
_____________________________________________________________________________________________________________

*Dans le fichier nommé test_orthogonal_with_procedure,nous avons un algorithme en pseudocode permettant 
de tester si plusieurs paires de vecteurs entiers sont orthogonaux à l’aide d’une procédure dot_product.
 Fonctionnement :
L'utilisateur saisit : La dimension des vecteurs puis Le nombre de paires à analyser.
Pour chaque paire : lecture des composantes des deux vecteurs,
Calcul du produit scalaire à l’aide de la procédure,
Vérification si ce produit est égal à 0 (=> vecteurs orthogonaux).
Deux vecteurs sont orthogonaux si leur produit scalaire est nul 
_____________________________________________________________________________________________________________
*Dans le fichier nommé test_orthogonal_with_function, on a un algorithme en pseudocode qui permet de tester si plusieurs 
paires de vecteurs sont orthogonaux en utilisant une fonction dot_product (produit scalaire).
 Objectif :
Vérifier si deux vecteurs sont orthogonaux, c’est-à-dire que leur produit scalaire est égal à zéro.
 Fonctionnement :
L'utilisateur entre :La dimension n des vecteurs, et le nombre de paires de vecteurs à tester.
Pour chaque paire: Saisie des composantes des vecteurs v1 et v2 et appel de la fonction dot_product(v1, v2, n),
Si le résultat est 0, les vecteurs sont orthogonaux,
Sinon, ils ne sont pas orthogonaux.
_______________________________________________________________________________________________________________
*Dans le fichier nommé PROCEDURE dot_product,nous avons une procédure qui nous permet de calculer le produit scalaire de
deux vecteurs d'entiers en pseudocode, et d’en retourner le résultat via un paramètre en sortie (VAR ps).
 Fonctionnement :
La procédure prend en paramètres d’entrée :
Deux tableaux v1 et v2 de même taille (représentant deux vecteurs),
Un entier taille (la dimension des vecteurs).
