## Indépendance et variables aléatoires
### Règles de probabilité
#### Probabilité conditionnelle de A sachant B
![[Pasted image 20250226142058.png]]
##### Et de B sachant A
![[Pasted image 20250226142117.png]]
#### Règle de multiplication
![[Pasted image 20250226142130.png]]
#### Règle générale d'addition
![[Pasted image 20250226142413.png]]
#### Probabilité totale
![[Pasted image 20250226142436.png]]
#### Règle du complément
![[Pasted image 20250226142449.png]]
#### Exemple
![[Pasted image 20250226142557.png]]
Utilisez la règle générale de l’addition :
![[Pasted image 20250226142821.png]]
#### Exemple 2
Considérons un dé équilibré. Quelle est la probabilité de lancer un nombre pair ou un 3 ?
![[Pasted image 20250226143005.png]]
### Indépendance
A et B sont des événements indépendants si:
![[Pasted image 20250226143140.png]]
#### Remarques
![[Pasted image 20250226143214.png]]
- Probabilité jointe de deux événements indépendants:
	- ![[Pasted image 20250226143243.png]]
#### Indépendance: *Roi* et *Coeur*
![[Pasted image 20250226143740.png]]
##### Une autre façon de vérifier l'indépendance
![[Pasted image 20250226144051.png]]
#### Indépendance: *Figure* et *Roi*
![[Pasted image 20250226144324.png]]
##### Une autre façon de vérifier l'indépendance
![[Pasted image 20250226144418.png]]
### Événements mutuellement exclusifs vs événements indépendants
![[Pasted image 20250226144820.png]]
### Règles de base
- *Non* → 1 – Probabilité.
- *Ou* et Événements mutuellement exclusifs → Additionner.
- *Et* et Indépendance → Multiplier
### Événements successifs
![[Pasted image 20250226145220.png]]
- A= *Lancer Face 6 fois*
	![[Pasted image 20250226145328.png]]
- B= *Obtenir FPFPPF*
	![[Pasted image 20250226145351.png]]
### Échantillonnage sans remplacement
**Un bocal contient 6 billes bleues et 6 billes rouges. Vous en tirez 3**:
	![[Pasted image 20250226145729.png]]
	![[Pasted image 20250226151720.png]]
**Tirer deux cartes d'un jeux standard**:
- A = *Première carte est un Roi*.
- B = *Deuxième carte est un Roi.*
![[Pasted image 20250226152031.png]]
### Variables aléatoires
Une variable aléatoire est une variable dont la valeur dépend de l’issue d’un
phénomène aléatoire. Chaque issue correspond à un nombre ou à un état/condition :
![[Pasted image 20250226152315.png]]
Nommons la variable aléatoire *X*:
![[Pasted image 20250226152338.png]]
#### Lancer une pièce équilibrée 3 fois
Résultats possibles:
![[Pasted image 20250226152556.png]]
*X*= Nombre de faces (*F*).
##### FMP: Fonction de masse de probabilité
![[Pasted image 20250226152731.png]]
##### **Plus généralement**
*X* prend des valeurs: 
![[Pasted image 20250226152859.png]]
![[Pasted image 20250226152943.png]]
###### **Remarques**
![[Pasted image 20250226153012.png]]
###### **Résultats**
![[Pasted image 20250226153115.png]]
![[Pasted image 20250226153124.png]]
![[Pasted image 20250226153325.png]]
#### Événement *A*= {*X*=*k*}
![[Pasted image 20250226153409.png]]
##### Entretien d'embauche
On choisi 5 personnes au hasard dans une salle de 100 personnes. Parmi ces 100 personnes, 50 personnes étudient à Genève et 50 personnes étudient à Lausanne.

*X* = nombre de personnes sélectionnées qui étudient à Genève.

On obtient la distribution de probabilité suivante (nous verrons comment obtenir ces chiffres par la suite) :
![[Pasted image 20250226153529.png]]
###### **Quelle est la probabilité que un ou deux personnes sélectionnées étudient à Genève?**
![[Pasted image 20250226153606.png]]
###### **Quelle est la probabilité qu'==*au moins 2*== personnes selectionnées étudient à Genève**?
![[Pasted image 20250226153745.png]]
### Notation Sigma
Une abréviation pour écrire de longues sommes:
![[Pasted image 20250226154100.png]]
### Formule fondamentale de la probabilité
- *X*= variable aléatoire.
- *A*= un ensemble des valeurs possibles de *X* (un événement).
![[Pasted image 20250226154257.png]]
#### Exemple de l'entretien d'embauche
![[Pasted image 20250226154328.png]]
#### Exemple
- Supposons que nous avons la distribution suivante:
	![[Pasted image 20250226154401.png]]
- Nous voulons calculer la probabilité suivante:
	![[Pasted image 20250226154423.png]]
	![[Pasted image 20250226154434.png]]
### Espérance
![[Pasted image 20250226154458.png]]
#### Interprétation
- Une moyenne pondérée par les probabilités.
- La moyenne à long terme de X.
- La valeur juste d’un pari.
- Le point d’équilibre pour un histogramme ou un diagramme en barres de probabilité.
#### Comment calculer E(*X*)
![[Pasted image 20250226155126.png]]
#### E(*X*)
![[Pasted image 20250226155151.png]]

#UNIGE #Intro-stat 