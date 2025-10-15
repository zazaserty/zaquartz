## Concepts clés en probabilité
### Modélisation des phénomènes aléatoires
![[Pasted image 20250219143411.png]]
#### Résultats
Résultats possibles d'une expérience.
#### Population
Ensemble de tous les résultats possibles (noté *S*).
#### Événement
Ensemble de résultats (par exemple, *A* dans l'illustration).
#### Exemple: lance d'un dé équilibré
![[Pasted image 20250219143444.png]]
Si le dé est **équilibré**, alors la probabilité d’obtenir chaque face est la même, c’est-à-dire:
- Probabilité (un) = Probabilité (deux) = Probabilité (trois) = Probabilité (quatre) = Probabilité (cinq) = Probabilité (six) 
- ou, en d’autres termes->
	![[Pasted image 20250219143532.png]]
#### Exemple: lancer d'une pièce équilibrée
![[Pasted image 20250219143634.png]]
### Probabilité
Si tous les résultats sont équiprobables, c’est-à-dire qu’ils ont la même probabilité de se produire:
![[Pasted image 20250219143706.png]]
==Ceci ne marche qu'avec des résultats équiprobables==
#### Exemple: lancer d'un dé équilibré
- Quelle est la probabilité d’obtenir un 5 ?
- Quelle est la probabilité que le dé tombe sur un nombre impair ?

Nous pouvons utiliser la définition classique de la probabilité, car ==tous les nombres d’un dé ont la même probabilité d’apparaître==, puisque c’est un dé équilibré.
##### Étapes
- Déterminer l’univers, qui sont les résultats possibles d’un tirage de dé :
	![[Pasted image 20250219143949.png]]
- Déterminer les événements qui nous intéressent :
	![[Pasted image 20250219143957.png]]
- Calculer la probabilité en utilisant la définition :
	![[Pasted image 20250219144006.png]]
#### Exemple: lancer une pièce équilibrée trois fois
##### Probabilité d’obtenir 3 faces :
![[Pasted image 20250219144055.png]]
Résultats :
![[Pasted image 20250219144113.png]]
##### Probabilité d'obtenir 2 faces
![[Pasted image 20250219144313.png]]
Résultats :
![[Pasted image 20250219144330.png]]
##### Probabilité d'obtenir au moins 2 faces
![[Pasted image 20250219144354.png]]
Résultats :
![[Pasted image 20250219144410.png]]
#### Propriétés des probabilités
1. Pour tout événement A:
	![[Pasted image 20250219144446.png]]
2. Un événement qui a une probabilité de 1 est appelé **certain**.
3. Un événement qui a une probabilité de 0 est appelé **impossible** (du point de vue probable ça n'arrive jamais).
### Complément/Événements opposés
![[Pasted image 20250219144658.png]]
==La P de A+la P que A n'arrive pas est toujours = 1==
#### Exemple : lancer un dé équilibré
![[Pasted image 20250219144812.png]]
### Événements mutuellement exclusifs
Lorsque les événements A et B (notés par A ∩ B) ne peuvent pas se produire simultanément (noté par A ∩ B = ∅), alors ils sont appelés événements mutuellement exclusifs. Leur somme peut-être inférieure/égale à 1.
#### Exemples
- Élections :
	![[Pasted image 20250219145053.png]]
- Lancer une pièce :
	![[Pasted image 20250219145108.png]]
- Lancer un dé équilibré :
	![[Pasted image 20250219145126.png]]
#### Illustration par Venn
Si A et B ne peuvent pas se produire simultanément :
![[Pasted image 20250219145317.png]]
==A et B n’ont aucun élément en commun==!
### Ensembles
![[Pasted image 20250219145409.png]]
==On ne peut pas faire P=A+B si A et B se croisent comme dans le premier ensemble, puisqu'on compterait la partie complémentaire deux fois==.
### Probabilité conditionnelle
Lancez un dé équilibré et quelqu’un nous dit que le résultat du dé est un nombre impair.
- Quelle est la probabilité que le résultat soit un cinq étant donné que le résultat du dé est un nombre impair ?
- Et la probabilité d’obtenir un 6 étant donné que le résultat du dé est un nombre impair ?

Probabilité conditionnelle de l’événement B étant donné que l’événement A est survenu :
	![[Pasted image 20250219151853.png]]

Probabilité conditionnelle de l’événement B étant donné que l’événement A
est survenu. Si les résultats sont équiprobables :
	![[Pasted image 20250219152326.png]]

Probabilité conditionnelle de l’événement B étant donné que l’événement A
est survenu :
	![[Pasted image 20250219152555.png]]
#### Exemple
Quelle est la probabilité que le résultat d’un lancer de dé équilibré soit cinq
étant donné que le résultat est un nombre impair ?
![[Pasted image 20250219152736.png]]
#### Autre exemple
Si vous savez qu’une famille a deux enfants et que l’un d’eux est un garçon, quelle est la probabilité que l’autre enfant soit également un garçon ?
- Population = ensemble des paires possibles d’enfants
	![[Pasted image 20250219152903.png]]
- La probabilité que les deux enfants soient des garçons étant donné qu’il y a au moins un garçon est:
	![[Pasted image 20250219152926.png]]

![[Pasted image 20250219153017.png]]
#### En général
- P(A|B) = probabilité conditionnelle de A sachant B.
- P(B|A) = probabilité conditionnelle de B sachant A.
##### Exemple
![[Pasted image 20250219153118.png]]
### Probabilité jointe
P(A et B) = probabilité jointe de A et B la probabilité que les événements A et B se produisent ensemble (A ∩ B).
![[Pasted image 20250219152650.png]]
### Règles de probabilité
#### Probabilité conditionnelle de A sachant B
![[Pasted image 20250219153417.png]]
#### Probabilité conditionnelle de B sachant A
![[Pasted image 20250219153436.png]]
#### Règle de multiplication
![[Pasted image 20250219153453.png]]
#### Règle générale d'addition
![[Pasted image 20250219153508.png]]
#### Probabilité totale
![[Pasted image 20250219153533.png]]
#### Règle du complément
![[Pasted image 20250219153907.png]]
### Deux types de questions
![[Pasted image 20250219154512.png]]
### Exemple test covid
- 1 % des étudiants ont le COVID.
- Le test de dépistage est précis à 99 %. (Ainsi, il y a 1 % de chance que le test ne soit pas précis).
- Léa (une étudiante) est testée positive au COVID.

Quelle est la probabilité que Léa ait effectivement le COVID étant donné qu’elle a été testée positive ?
![[Pasted image 20250219154930.png]]
![[Pasted image 20250219154951.png]]
![[Pasted image 20250219155131.png]]
![[Pasted image 20250219155533.png]]

#UNIGE #Intro-stat 