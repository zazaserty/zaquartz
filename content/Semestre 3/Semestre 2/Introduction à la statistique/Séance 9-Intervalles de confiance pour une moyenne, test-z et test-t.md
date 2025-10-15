## Intervalles de confiance pour une moyenne, test-z et test-t
### Niveau de signification
![[Pasted image 20250430142712.png]]
![[Pasted image 20250430143106.png]]
### Exemple : âge des véhicules
- Dans une enquête menée auprès de 30 adultes, l’âge moyen du véhicule principal d’une personne est de 5.6 ans.
- En supposant que l’écart-type de la population est de 0.8 an.
- Trouvez la meilleure estimation ponctuelle de la moyenne de la population et un intervalle de confiance à 90% pour cette moyenne.
![[Pasted image 20250430143604.png]]
### Étapes pour calculer un intervalle de confiance pour µ avec σ connu
![[Pasted image 20250430143824.png]]
### Marge d'erreur et taille d'échantillon
![[Pasted image 20250430144738.png]]
#### Exemple : quelle est la taille de l'échantillon
- Le président d’une université demande au professeur de statistiques d’estimer l’âge moyen des étudiants de l’université.
- En supposant que l’écart-type de la population est de 3 ans, quelle taille d’échantillon est nécessaire pour obtenir un intervalle de confiance à 99% pour l’âge moyen des étudiants avec une marge d’erreur E = 1 ?
![[Pasted image 20250430144905.png]]
### Intervalle de confiance pour la moyenne µ de la population avec σ inconnue
- Taille de l’échantillon grande (n > 30), population IID.
- Taille de l’échantillon petite (n < 30), population IID normale.
#### Grande taille d'échantillon, population IID
![[Pasted image 20250430145401.png]]
#### Petite taille d'échantillon, population IID normale
![[Pasted image 20250430145430.png]]
![[Pasted image 20250430145457.png]]
##### Exemple : âge des véhicules
![[Pasted image 20250430145629.png]]
![[Pasted image 20250430145744.png]]
![[Pasted image 20250430145923.png]]
### Étapes pour calculer un intervalle de confiance pour µ avec σ inconnu et n ≤ 30
![[Pasted image 20250430145944.png]]
### Test d'hypothèse
![[Pasted image 20250430152009.png]]
### Hypothèse nulle et alternative
![[Pasted image 20250430153042.png]]
![[Pasted image 20250430153249.png]]
#### Exemple : tester sur la taille des étudiants
![[Pasted image 20250430153355.png]]
#### Exemple : tester un nouveau régime
![[Pasted image 20250430154054.png]]
#### Statistique de test
- Un test de signification est basé sur une statistique de test qui montre si les données fournissent ou non des preuves contre l’hypothèse nulle.
- Quand H0 est vrai, on s’attend à ce que l’estimation prenne une valeur proche de celle spécifiée par H0.
- Des valeurs de l’estimation éloignées de celle spécifiée par H0 fournissent des preuves contre H0 . L’hypothèse alternative détermine dans quelle(s) direction(s) comptent les écarts contre H0.
#### Statistique de test pour la moyenne de la population
![[Pasted image 20250430153740.png]]
![[Pasted image 20250430154028.png]]
#### P-valeur
![[Pasted image 20250430154120.png]]
#### Décision
![[Pasted image 20250430154518.png]]
#### Exemple->Test-Z : taille moyenne différente de 1.75m?
![[Pasted image 20250430154705.png]]
#### Exemple->Test-Z : le régime fait-il perdre du poids
![[Pasted image 20250430154803.png]]
#### Graphique de la p-valeur
![[Pasted image 20250430155307.png]]
#### P-valeur
- La p-valeur est la probabilité, en supposant que H0 soit vrai, que la statistique de test prenne une valeur au moins aussi extrême que celle effectivement observée.
- Plus la p-valeur est petite, plus les preuves contre H0 fournies par les données sont fortes.
- Si α=0.05, nous exigeons que les données fournissent des preuves suffisamment solides contre l’hypothèse nulle pour que son rejet se produise au maximum 5 % du temps lorsque H0 est vrai.
### Statistique de test pour la moyenne de la population
![[Pasted image 20250430155410.png]]
#### Décision basée sur la valeur critique
![[Pasted image 20250430155647.png]]
#### Exemple : test-t
- On considère l’âge des étudiants inscrits au bachelor en relations internationales.
- On considère que la distribution de l’aĝe des étudiants est distribuée normalement.
- On considère un échantillon de 20 étudiants pour lequel on mesure leur âge.
- La moyenne de l’échantillon est de X̄ = 21.42 et l’erreur standard de l’échantillon est de s = 2.91.
- Vous chercher à tester si l’âge moyen des étudiants est supérieur à 18 ans à un niveau de significativé de α = 0.05.
- Les hypothèses sont donc :
	- H0 : µ = 18.
	- Hα : µ > 18.
![[Pasted image 20250430155813.png]]
### Étapes pour effectuer un test d'hypothèse
- Étape 1 : Formuler l’hypothèse nulle (H0 ) et l’hypothèse alternative (Hα ).
- Étape 2 : Calculer la valeur de la statistique de test zobs ou tobs.
- Étape 3 : Comparer la statistique de test à la valeur critique ou trouver la p-valeur pour les données observées et comparer la p-valeur avec le niveau de signification désiré α.
### Variance
![[Pasted image 20250502135557.png]]

#UNIGE #Intro-stat 