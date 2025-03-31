## Statistiques descriptives et inférentielles
### Définitions
#### Descriptives
Décrire les données que nous avons collectées qui composent l'échantillon.
#### Inférence statistique
Faire des généralisations sur un ensemble plus large, la population.
### Description des échantillons
- Quelle est sa tendance centrale ?
- Quelle est sa dispersion ou variabilité ? Combien de bruit contient les données ?
- Quelle est la forme de la distribution ? Est-elle symétrique ?
![[Pasted image 20250325223922.png]]
### Tendance centrale de la distribution
Mesures de la tendance centrale de la distribution.
#### Moyenne
Additionner les données et diviser par le nombre d'observations.
##### Exemples
![[Pasted image 20250325224211.png]]
![[Pasted image 20250325224223.png]]
#### Médiane
Un nombre égal d'observations plus grandes et plus petites que la médiane. Trier les données et considérer la valeur de l'observation centrale.
##### Exemples
![[Pasted image 20250325224444.png]]
### Moyenne versus médiane
La moyenne et la médiane sont proches pour des distributions symétriques :
![[Pasted image 20250325224610.png]]
La moyenne se déplace dans la direction de l'asymétrie d'une distribution :
![[Pasted image 20250325224639.png]]
### Valeurs aberrantes
Une valeur qui ne correspond pas au reste.
#### Exemples
![[Pasted image 20250325224927.png]]
==La médiane est résistante aux valeurs aberrantes==!
### Résumé en 5 nombres
- Médiane.
- Minimum, Maximum.
- Quartiles : observation centrale au-dessus et en dessous de la médiane.
![[Pasted image 20250325225030.png]]
### Trouver les quartiles
- Données : 7, 23, 75, 82, 34, 91, 10.
- Trier, on obtient 7, 10, 23, 34, 75, 82, 91.
- Trouver la médiane, on obtient 34.
- Observations en dessous de la médiane : 7, 10, 23.
- Premier quartile Q1 = 10.
- Observations au-dessus de la médiane : 75, 82, 91.
- Troisième quartile Q3 = 82.
#### Autre exemple
- Données : 7, 8, 22, 38, 48, 62.
- Médiane = (22+38)/2 = 30.
- Premier Quartile : 7, 8, 22.
- Q1 = 8.
- Troisième Quartile : 38, 48, 62.
- Q3 = 48.
### Mesurer la dispersion
Quelle est la variabilité des données?
- Étendue = Maximum-Minimum.
- Étendue Interquartile (IQR) : Q3-Q1.
- Écart-Type (s) : Racine carrée de la moyenne des distances quadratiques à la moyenne.
#### Écart-type de l'échantillon
![[Pasted image 20250325225545.png]]
##### 5 étapes faciles
- Calculer la moyenne x̄.
- L’élever au carré.
- Calculer la somme des x².
- Trouver la différence (somme des xi² ) − nx̄².
- Diviser par n − 1.
- Prendre la racine carrée.
##### Exemple : 7, 8, 3
![[Pasted image 20250325225756.png]]
#### IQR versus *s*
- L’IQR, comme la médiane, ne dépend pas des observations les plus grandes (ou les plus petites).
- L’IQR est résistant aux valeurs aberrantes.
- *s* dépend de toutes les données et peut être sensible aux observations éloignées (valeurs aberrantes).
![[Pasted image 20250325225915.png]]
Les aberrantes apparaissent en dessous du Q1 et en haut du Q3 après une distance de 1.5 X IQR.
### Variables
#### Variables
L'aspect qui diffère d'un sujet à un autre, d'un individu à un autre, par exemple l'orientation politique, l'âge, le sexe, le revenu, etc.
#### Données
La valeur des variables, par exemple : *Conservateur*, *19*, *Homme*, *15 000$*, etc.
### Deux types de variables
Il y a **quatre sous-types**.
#### Quantitatives ou numériques
Nombres, mesures : âge, taille, distance parcourue, heures de sommeil, revenu, etc.
##### Continues vs discrètes
![[Pasted image 20250325230303.png]]
#### Catégorielles
Classifier chaque observation : nationalité, langue maternelle, satisfaction du cours, niveau d'études, etc.
##### Nominales versus ordinales
![[Pasted image 20250325230321.png]]
### Boxplot
![[Pasted image 20250325230350.png]]
![[Pasted image 20250325230649.png]]
==Chaque point est une observation réelle==.
![[Pasted image 20250325230711.png]]
### Comparaison entre groupes
Boxplot côte à côte pour comparer deux ensembles de données ou plus :
- Ont-ils le même centre ? La même forme ? La même dispersion ?
- La différence entre les médianes est-elle beaucoup plus grande que la variabilité des données ?
#### Exemple : résultats de tests pulmonaires avant et après traitement
![[Pasted image 20250325230844.png]]
### L'histogramme
#### Exemple : heures de sommeil
![[Pasted image 20250325230912.png]]
![[Pasted image 20250325231046.png]]
![[Pasted image 20250325231110.png]]
![[Pasted image 20250325231139.png]]
### Visualiser les données catégorielles
- Donner une image claire de ce que contiennent les données.
- Souligner les différences/similitudes.
- Les barplot sont généralement les meilleurs.
#### Donc
![[Pasted image 20250325231406.png]]
##### Barplot-> Exemple : orientation politique
![[Pasted image 20250325231451.png]]
![[Pasted image 20250325231457.png]]
![[Pasted image 20250325231511.png]]
### Loi uniforme
![[Pasted image 20250325234743.png]]
![[Pasted image 20250325234754.png]]
### Loi normale
![[Pasted image 20250325235715.png]]

#UNIGE #Intro-stat 