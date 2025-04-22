## Estimateurs
### Statistiques descriptives et inférentielles
- Statistiques descriptives : décrire les données que nous avons collectées qui composent l’échantillon.
- Inférence statistique : faire des généralisations sur un ensemble plus large, la population.
![[Pasted image 20250409142220.png]]
#### Exemple
- Supposons que Stephen Curry ait marqué en moyenne 30.1 points lors de 79 matches de basketball.
- Qu’est-ce qui est aléatoire ?
- Qu’est-ce qui est inconnu ?
- X = points marqués dans un seul match
	![[Pasted image 20250409142254.png]]
- Qu’est-ce que µ ? Et σ ?
### Statistiques vs. paramètres
- Paramètre : une caractéristique de la population. Typiquement inconnue en raison du grand nombre d’individus dans la population et/ou de l’impossibilité de mesurer tous les résultats possibles.
- Statistique : une quantité qui est calculée à partir des données que nous avons collectées de la population (échantillon).
![[Pasted image 20250409142715.png]]
### Distribution d'échantillonnage
- Les données sont des variables aléatoires.
- Les statistiques sont des fonctions des données. Elles sont donc aussi des variables aléatoires.
- La distribution des statistiques dépend des paramètres de la distribution des données.
#### Exemple : Moyenne de l’échantillon
![[Pasted image 20250409143307.png]]
#### X̄ en tant que variable aléatoire
![[Pasted image 20250409143344.png]]
##### Espérance
![[Pasted image 20250409143430.png]]
##### Écart-type
![[Pasted image 20250409143447.png]]
##### Erreur standard de X̄
![[Pasted image 20250409144634.png]]
### Exemple : observations normales et indépendantes
![[Pasted image 20250409144904.png]]
### Distribution
![[Pasted image 20250409145054.png]]
### Standardisation
![[Pasted image 20250409145251.png]]
#### Exemple : Nombre moyen de voitures dans les foyers américains
![[Pasted image 20250409145510.png]]
### Échantillon
- Jeu de données de l’échantillon : {X1 , . . . , Xn }.
- Taille de l’échantillon : n.
- Ordre de l’échantillon : n ≪ N (c’est-à-dire, n est (généralement) grand mais beaucoup plus petit que N).
#### Objectif
- À partir des valeurs de l’échantillon, {X1 , . . . , Xn }, où n est la taille de l’échantillon, nous essayons de tirer des conclusions sur les paramètres d’intérêt.
- L’échantillon idéal doit être représentatif et non biaisé.
- Choisir l’échantillon de manière aléatoire.
#### Échantillon aléatoire simple
##### {X1 , . . . , Xn } est un échantillon aléatoire simple si :
- Un membre particulier de la population est choisi, cela n’affecte pas les chances qu’un autre membre soit choisi.
- Chaque membre de la population a la même probabilité d’être choisi.
##### En d’autres termes...
- {X1 , . . . , Xn } sont indépendants.
- {X1 , . . . , Xn } sont identiquement distribués (c’est-à-dire qu’ils ont la même fonction de masse ou fonction de densité de probabilité).
### Estimation
![[Pasted image 20250409145815.png]]
### Propriétés
![[Pasted image 20250409145912.png]]
### Espérance et écart-type
![[Pasted image 20250409145929.png]]
### Remarque
![[Pasted image 20250409150057.png]]
### Théorème central limite (TCL)
![[Pasted image 20250409152749.png]]
#### Quand l'utiliser?
![[Pasted image 20250409152833.png]]
![[Pasted image 20250409153350.png]]
### Proportion d'échantillon
![[Pasted image 20250409153512.png]]
#### Distribution d'échantillonage
![[Pasted image 20250409153813.png]]
#### Laissez n augmenter : n=10=>100, p=0.5
![[Pasted image 20250409154331.png]]
![[Pasted image 20250409154413.png]]
#### TCL
![[Pasted image 20250409154654.png]]
##### Quand l'utiliser
![[Pasted image 20250409155232.png]]

#UNIGE #Intro-stat 