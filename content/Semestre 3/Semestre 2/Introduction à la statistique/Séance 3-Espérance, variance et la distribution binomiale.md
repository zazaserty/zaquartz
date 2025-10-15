## Espérance
### Interprétations :
- Une moyenne pondérée par les probabilités.
- La moyenne à long terme de X.
- La valeur juste d’un pari.
- Le point d’équilibre pour un histogramme ou un diagramme en barres de probabilité.
	![[Pasted image 20250305142648.png]]
### Formule
![[Pasted image 20250305141905.png]]
#### Calcul
![[Pasted image 20250305142552.png]]
C’est une moyenne pondérée des valeurs de X , où les poids correspondent aux probabilités associées à ces valeurs.
### Exemple: pari équitable
Vous payez 100 CHF pour un pari:
- Si vous gagnez, vous recevez 210 CHF, et si vous perdez, vous recevez 0 CHF.
- X = votre gain/perte->
	- X = 110 CHF, si vous gagnez.
	- X = −100 CHF, si vous perdez.
- Supposons que les probabilités de gagner/perdre sont:
	![[Pasted image 20250305142930.png]]
#### Ce pari est-il équitable?
La fonction de masse de probabilité (FMP) de X est :
	![[Pasted image 20250305143019.png]]
Pour vérifier si le pari est équitable ou non, calculez l’espérance de votre gain/perte :
	![[Pasted image 20250305143036.png]]
##### Donc?
Ce n’est pas un pari équitable, puisque l’espérance n’est pas nulle... mais devriez-vous jouer ?
- Oui, puisqu'on a l'avantage. Si on joue un grand nombre de fois (1000 fois par **exemple**) on gagnera 15.5 CHF.
### Un autre exemple: *Qui veut gagner des millions?*
- Quitter = 100 000 CHF.
- Bonne réponse X = 250 000 CHF.
- Mauvaise réponse X = 32 000 CHF.
#### Deux cas
##### Choisir au hasard parmi les 4 réponses possibles
![[Pasted image 20250305143356.png]]
##### Utiliser l'option 50-50, et choisir au hasard entre 2 réponses
![[Pasted image 20250305143424.png]]
##### Mais
On va jouer qu'une fois, dans ce cas l’espérance n'est peut-être pas la meilleure manière de décider quoi faire. En plus ce modèle ne prends pas en compte le risque, il y a des gens que même avec une espérance plus faible vont prendre ce pari pour s'assurer (avec un risque plus faible) qu'ils gagnent une certaine quantité d'argent.
### Ajout d'une constante
![[Pasted image 20250305143737.png]]
On a un pari et X est la quantité gagnée et 10 CHF nous sont donnés en plus. Donc a=10 CHF, c'est une constante dont on est sûrs du sort.
#### Fonctions d'une variable aléatoire
![[Pasted image 20250305143903.png]]
==Il est impossible d'obtenir par exemple un 18== puisque c'est une moyenne pondérée-> il faut faire attention aux résultat qu'on obtient.
##### Doubler la valeur de X
![[Pasted image 20250305143917.png]]
##### Multiplication par une constante
![[Pasted image 20250305144258.png]]
### Propriétés de ==E==(*X*)
![[Pasted image 20250305144355.png]]
Soit *X* et *Y* des variables aléatoires et a1, a2, b1 et b2 des constantes:
![[Pasted image 20250305144427.png]]
### Exemple: *dé bleu* et *dé vert*
Deux dés équilibrés sont lancés, un bleu et un vert.
![[Pasted image 20250305144709.png]]
Déterminez l'espérance de *Y* et l'univers pour chaque dé bleu ou vert est:
![[Pasted image 20250305144831.png]]
![[Pasted image 20250305144844.png]]
![[Pasted image 20250305144939.png]]
## Mesurer la variabilité
La variance = Mesure de l’étendue de la FMP.
La variance = Espérance de la distance au carré de l’espérance.
![[Pasted image 20250305145805.png]]
### Remarque
![[Pasted image 20250305145826.png]]
### Comment calculer Var(*X*)
![[Pasted image 20250305145905.png]]
==La variance ne peut jamais être négative, tout comme une probabilité.== Si on a une variable aléatoire avec un seul valeur elle peut être 1 néanmoins.
## Écart type
![[Pasted image 20250305151814.png]]
L'écart type est bien plus facile à interpreter que la variance.
### Propriétés
![[Pasted image 20250305152117.png]]
### Événements indépendants
Si *A* et *B* sont *indépendants*:
![[Pasted image 20250305152326.png]]
![[Pasted image 20250305152340.png]]
#### Lancers de pièces équilibrées
![[Pasted image 20250305152912.png]]
#### Et compter les piles
![[Pasted image 20250305152949.png]]
4 possibilités pourr X=1.
##### Univers
![[Pasted image 20250305153038.png]]
==(1/2)²=1/4== = P(X=1).
###### **Si on jette la pièce 4 fois**
![[Pasted image 20250305153414.png]]
#### En général
![[Pasted image 20250305153610.png]]
##### Comment comptons-nous ces combinaisons?
### Principe fondamental du comptage
![[Pasted image 20250305153813.png]]
#### Choisir un ordre
![[Pasted image 20250305153835.png]]
![[Pasted image 20250305153922.png]]
#### Comptage des séquences
![[Pasted image 20250305154031.png]]
#### Exemple: séquence (sans ordre)
![[Pasted image 20250305154326.png]]
Pourquoi entre 2? Parce que l'ordre n'a pas d'importance et donc la moitié des équipes est la même que l'autre.
#### k **parmi** n
![[Pasted image 20250305154430.png]]
#### Probabilité d'obtenir 6 faces sur 10 lancers
![[Pasted image 20250305154903.png]]
![[Pasted image 20250305154954.png]]
#### Suite d'événements indépendants
![[Pasted image 20250305155242.png]]
#### Autres probabilités
![[Pasted image 20250305155211.png]]
#### Expérience binomiale
![[Pasted image 20250305155401.png]]
#### Exemple: votation d'une loi
![[Pasted image 20250305155422.png]]
#### Probabilité binomiale
![[Pasted image 20250305155558.png]]
#### Distribution binomiale
![[Pasted image 20250305160001.png]]

#UNIGE #Intro-stat 