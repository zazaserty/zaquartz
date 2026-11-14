## Régression linéaire
### Introduction : pourquoi la régression
#### Rappel : deux variables numériques
![[Pasted image 20261029173758.png]]
#### Promesses et périls de la statistique
![[Pasted image 20261029173812.png]]
#### De la corrélation à la régression
![[Pasted image 20261029173832.png]]
#### Les données
![[Pasted image 20261029173853.png]]
#### Le modèle estimé
![[Pasted image 20261029174354.png]]
#### La droite estimée : constante et pente
![[Pasted image 20261029174415.png]]
#### Valeurs prédites et résidus
![[Pasted image 20261029174441.png]]
#### L’erreur standard du coefficient
![[Pasted image 20261029174509.png]]
#### Les tests t et F
![[Pasted image 20261029175726.png]]
#### L’intervalle de confiance
![[Pasted image 20261029180014.png]]
#### Lire la valeur p
- Définition : la valeur p est la probabilité d’obtenir une statistique t au moins aussi éloignée de 0 que celle observée si H0 était vraie, c’est-à-dire si la pente était nulle.
- Lecture traditionnelle, par le seuil conventionnel : si p<0.05, on rejette H0 et le coefficient est dit « statistiquement significatif » au seuil de 5%.
    - Limite : p=0.04 et p=0.06 disent presque la même chose, de part et d’autre d’une frontière arbitraire.
- Lecture alternative, recommandée par certains statisticiens ([Wasserstein et al. 2019](https://moodle.unige.ch/pluginfile.php/2860475/mod_resource/content/1/MADI-chapitre5-diapositives.html#/références)) : la valeur p mesure la compatibilité des données avec H0. Plus p est petite, moins les données sont compatibles avec une pente nulle.
    - On rapporte p telle quelle, avec l’estimation et son intervalle de confiance, et on discute la taille de l’effet en unités concrètes.
- La valeur p ne mesure ni la probabilité que H0 soit vraie ni la taille de l’effet.
#### Exemple : la démocratie selon la richesse
La thèse de la modernisation ([Lipset 1959](https://moodle.unige.ch/pluginfile.php/2860475/mod_resource/content/1/MADI-chapitre5-diapositives.html#/références)) : plus un pays est riche, plus il est démocratique.
- Hypothèse de recherche, H1:β1>0 : la pente est positive, la démocratie augmente avec la richesse.
- Hypothèse nulle, H0:β1=0 : la pente est nulle, la démocratie ne varie pas avec la richesse.
- Les données :
    - variable dépendante : le niveau de démocratie, l’indice de V-Dem, de 0 à 1 ;
    - variable indépendante : la richesse, le PIB par habitant en milliers de dollars (`pib_hab1000`) ;
    - les analyses utilisent le fichier `democratie_conflit.rds`, présenté en section 5.1 : 145 pays.
#### Exploration univariée
![[Pasted image 20261112161916.png]]
#### La relation bivariée
![[Pasted image 20261112161929.png]]
#### Estimer le modèle
![[Pasted image 20261112161943.png]]
#### Interpréter les coefficients
Modèle estimé : démocratie prédite = 0.416 + 0.008 × PIB par habitant (en milliers de dollars).
- La constante ou l’intercept (β^0 = 0.416) : le niveau de démocratie prédit pour un pays avec un PIB par habitant de 0 dollar. Aucun pays n’a un PIB par habitant de 0, le plus pauvre est à 670 dollars. En général, on ne l’interprète pas.
- La pente (β^1 = 0.008) : 1 000 dollars par habitant de plus sont associés en moyenne à une hausse du niveau de démocratie de 0.008 point, avec un intervalle à 95% de 0.006 à 0.011.
    - Pour 10 000 dollars de plus, +0.08 point, sur une échelle de 0 à 1. La lecture est la même pour un pays pauvre et pour un pays riche.
- Retour à l’hypothèse : la pente est positive, l’intervalle exclut largement zéro, p<0.001. Les données sont très peu compatibles avec une pente nulle : l’hypothèse de recherche est vérifiée, la démocratie augmente avec la richesse.
- Pas de preuve de causalité :
    - D’autres variables, liées à la fois à la richesse et à la démocratie, peuvent expliquer l’association : il faut intégrer des variables de contrôle, section 5.4.
    - La richesse peut favoriser la démocratie, et inversement (causalité réciproque).
#### Qualité de l’ajustement : R2
![[Pasted image 20261112162034.png]]
#### R2 ajusté : préférable pour comparer des modèles
![[Pasted image 20261112162140.png]]
#### Précision du modèle : erreur résiduelle σ^
![[Pasted image 20261112162152.png]]
#### Le logarithme (1) : symétriser la distribution
![[Pasted image 20261112162437.png]]
#### Le logarithme (2) : un effet proportionnel, non additif
![[Pasted image 20261112162448.png]]
#### Dollars ou logarithme : les deux modèles côte à côte
![[Pasted image 20261112164653.png]]
#### Variable indépendante catégorielle : le codage dichotomique
![[Pasted image 20261112164703.png]]
#### Exemple : la démocratie selon le conflit
![[Pasted image 20261112164712.png]]
#### Changer la catégorie de référence
![[Pasted image 20261112164733.png]]
#### Les hypothèses du modèle
![[Pasted image 20261112164748.png]]
### De l’association à la causalité
#### Analyser une relation : deux questions de plus
![[Pasted image 20261112171744.png]]
#### Trois conditions pour conclure à une relation causale
![[Pasted image 20261112171752.png]]
#### On ne prouve pas une cause, on réfute
Le tabac et le cancer du poumon, un lien tenu pour causal :
- une association forte et régulière, dans toutes les populations étudiées ;
- la séquence : le cancer vient après des années de tabac ;
- aucune explication alternative n’a résisté, et une théorie biologique explique le mécanisme.

La preuve anecdotique « mon grand-père fume deux paquets par jour et, à 90 ans, il se porte bien » ne réfute rien :
- Une cause, en sciences sociales comme en médecine, est probabiliste : tous les fumeurs n’auront pas de cancer, mais une plus grande proportion d’entre eux en aura.
- Une anecdote ne compte que si elle met en défaut l’une des trois conditions.

En fin de compte, on ne prouve jamais qu’une variable en cause une autre : on réfute des hypothèses causales en montrant qu’au moins une des trois conditions ne tient pas.
- Les données peuvent contredire l’association ou révéler une explication alternative.
- La séquence temporelle, elle, se juge par la théorie ou par le design.
#### Les types de relations multivariées
![[Pasted image 20261112171825.png]]
### La régression linéaire multiple
#### Pourquoi la régression multiple ?
![[Pasted image 20261112171859.png]]
#### Les variables de contrôle
![[Pasted image 20261112171911.png]]
#### La richesse et le conflit ensemble
![[Pasted image 20261112173600.png]]
#### Quatre modèles côte à côte
![[Pasted image 20261112173609.png]]
#### Quatre modèles côte à côte
![[Pasted image 20261112173621.png]]
#### Lire le modèle complet
- La richesse (β^ = 0.006, p<0.001) : effet positif et statistiquement significatif sur le niveau de démocratie.
    - À conflit, région, population et dépenses militaires constants, une hausse du PIB par habitant de 1 000 dollars est associée à une hausse du niveau de démocratie de 0.006 point.
    - Le coefficient s’atténue un peu de m0 à m5 : l’effet de la richesse résiste à tous les contrôles.
- Les dépenses militaires (β^ = -0.040, p<0.001) : effet négatif et statistiquement significatif.
    - À richesse, conflit, région et population constants, une hausse d’un point de pourcentage des dépenses militaires en part du PIB est associée à une baisse du niveau de démocratie de 0.040 point.
- La région, par rapport à l’Europe, la catégorie de référence, les autres variables étant tenues constantes :
    - l’Asie-Océanie (β^ = -0.151, p = 0.002) : niveau de démocratie inférieur de 0.151 point.
    - l’Afrique (β^ = -0.122, p = 0.018) : inférieur de 0.122 point.
    - les Amériques (β^ = -0.018, p = 0.725) : pas de différence statistiquement significative.
- Le conflit (β^ = -0.067, p = 0.109) : l’écart n’est plus statistiquement significatif.
    - Ce que le conflit seul expliquait dans m2 (-0.221) tenait pour l’essentiel à la richesse et à la région.
- La taille de la population (β^ = 0.004, p = 0.721) : aucun effet discernable.
#### Comparer des modèles : R2 ajusté, AIC et BIC
![[Pasted image 20261112173650.png]]


#UNIGE #MADI 