## Chapitre 3 — L’inférence causale (suite)
 
### L’auto-sélection biaise dans les deux sens

![[MADI_Ch3_Diapo_22.png]]

Un effet brut faible ou négatif peut masquer un effet bénéfique : les groupes diffèrent déjà avant le traitement. Si les missions vont aux conflits les plus difficiles, leur efficacité est sous-estimée ; si elles vont aux cas faciles, elle est surestimée.

### Le contrôle statistique et sa faille

![[MADI_Ch3_Diapo_23.png]]

![[MADI_Ch3_Exemple_Salaire.png]]

`u` regroupe les déterminants du salaire non intégrés au modèle (genre, secteur, âge, ancienneté…) et les erreurs de mesure.

- Avec assignation aléatoire, ces facteurs sont répartis de façon comparable entre les groupes, en moyenne.
- Sans expérience, il faut **postuler que ce qui reste dans `u` n’est pas lié à la formation** : c’est une hypothèse, pas une garantie.
- Le choix des contrôles et la bonne spécification du modèle comptent davantage que leur nombre.

### Les trois problèmes de la quasi-expérience

![[MADI_Ch3_Diapo_24.png]]

**Variable omise :** le facteur oublié doit être lié à la fois à la cause et à l’effet. Le contrôler signifie l’intégrer à l’analyse.

Deux questions distinctes : **qui reçoit le traitement ?** (assignation) et **quels cas observe-t-on ?** (échantillonnage). Pour étudier les causes de guerre, il faut aussi des cas sans guerre : retenir uniquement les conflits sélectionne sur le résultat.

### Les trois problèmes dans nos questions

![[MADI_Ch3_Diapo_25.png]]

Les problèmes peuvent se combiner : envoyer les missions dans les conflits les plus difficiles rend l’assignation non aléatoire ; la gravité du conflit peut aussi être une variable omise.

Aide et croissance : la faible croissance peut attirer l’aide. Une corrélation négative ne suffit donc pas à conclure que l’aide freine la croissance.

### Quatre questions à poser à toute recherche

![[MADI_Ch3_Diapo_26.png]]

L’**expérience idéale** précise ce que l’on voudrait faire varier et tenir constant ; elle permet de voir ce qui manque à l’étude réelle.

La **stratégie d’identification** explique l’attribution de la cause, au-delà d’une liste de contrôles.

- **Question non identifiée :** âge à l’entrée à l’école = âge actuel − durée de scolarisation. On ne peut faire varier l’un en maintenant les deux autres constants.
- **Expérience naturelle :** choc pétrolier → recettes supplémentaires des pays producteurs → hausse de l’aide. Cette variation extérieure à la situation des bénéficiaires sert à étudier l’effet de l’aide sur leur croissance. L’étude citée ne détecte pas d’effet.
- **Discrimination :** on manipule la perception de l’origine par le nom sur des CV autrement comparables. Le traitement correspond à l’identité perçue par l’employeur.

### L’analyse contrefactuelle

#### Le raisonnement contrefactuel

![[MADI_Ch3_Diapo_28.png]]

Le raisonnement causal engage une comparaison avec le monde sans la cause. Le conséquent peut être probabiliste : sans la mission, la reprise de la guerre aurait été **plus probable**, sans être certaine.

#### Du contrefactuel au contrefait

![[MADI_Ch3_Diapo_29.png]]

- **Condition nécessaire :** sans X, pas de Y. Elle implique un énoncé contrefactuel.
- **Condition suffisante :** si X, alors Y. Cela ne dit pas ce qui arrive en l’absence de X.

« Deux démocraties → paix » n’implique donc pas « absence de démocratie → guerre ». La théorie doit préciser ce qui se passerait sans la cause.

Un **contrefait observé** est un autre cas suffisamment semblable, sans la cause : la comparaison repose sur l’homogénéité des unités. Un **contrefait imaginé** reste à juger sur sa plausibilité.

- **Un seul cas :** construire un contrefait imaginé.
- **Quelques cas :** combiner comparaisons réelles et contrefaits imaginés.
- **Grand nombre de cas :** les unités sans la cause servent de comparaison statistique à celles qui la reçoivent.

#### Juger un contrefactuel : trois critères

![[MADI_Ch3_Diapo_30.png]]

- **Réécriture minimale :** limiter le nombre et l’ampleur des changements supposés.
- **Cotenabilité :** expliciter les changements que l’antécédent suppose ou entraîne et vérifier leur compatibilité. Imaginer l’URSS en supériorité stratégique à Cuba pourrait supprimer sa raison d’y installer des missiles : la crise étudiée disparaîtrait.
- **Conséquent :** préciser l’issue et la déduire d’une théorie appuyée sur les faits historiques. Une longue chaîne d’événements multiplie les hypothèses.

**Contingence / structure :** sans le déclencheur observé, un autre incident aurait-il conduit au même résultat ? C’est la limite illustrée par Pleiku.

### L’inférence causale : ce qu’il faut retenir

![[MADI_Ch3_Diapo_31.png]]

## Chapitre 4 — Données et tableaux croisés

Question de fond : **un tableau croisé permet-il une inférence causale ?**

### Pourquoi les méthodes quantitatives ?

#### Ce que sont les méthodes quantitatives

![[MADI_Ch4_Diapo_04.png]]

Le codage transforme des concepts en nombres : les données quantitatives reposent aussi sur des choix théoriques.

#### Les atouts du quantitatif

![[MADI_Ch4_Diapo_05.png]]

Chaque outil statistique repose sur des postulats : la validité de l’inférence dépend des conditions dans lesquelles on l’utilise.

### Les données

#### Données, population, échantillon

![[MADI_Ch4_Diapo_07.png]]

La population dépend de la question de recherche. L’inférence consiste à passer des cas observés à l’ensemble auquel on veut généraliser.

#### Échantillonner : aléatoire ou non ?

![[MADI_Ch4_Diapo_08.png]]

Le tirage aléatoire donne une probabilité connue et non nulle d’inclusion et permet de quantifier l’incertitude. Il est distinct de l’assignation aléatoire du traitement.

**Quotas :** on reproduit certaines proportions de la population (âge, sexe…). Cela ne fournit pas une probabilité connue d’inclusion pour chaque unité.

#### L’unité d’observation

![[MADI_Ch4_Diapo_09.png]]

Une dyade-année = une paire de pays observée pendant une année. La même paire revient donc plusieurs fois si l’étude couvre plusieurs années.

#### Trois articles, trois unités d’observation

![[MADI_Ch4_Diapo_10.png]]

Le nombre de lignes dépend de l’unité retenue. Compter les années d’une même dyade ou plusieurs épisodes d’un même pays comme des cas indépendants **surestime l’information disponible**.

#### Le fichier de données : une matrice

![[MADI_Ch4_Diapo_11.png]]

#### Le fichier de données dans R

![[MADI_Ch4_Diapo_12.png]]

`conflit` est dichotomique (0/1), même si R l’affiche sous le type numérique `dbl`. Il faut regarder le codage, en plus du format informatique.

#### Où trouver les données

![[MADI_Ch4_Diapo_13.png]]

#### Coder : transformer le monde en variables

![[MADI_Ch4_Diapo_14.png]]

Changer la définition, le seuil ou la source peut changer le résultat. Les choix de codage doivent être explicités et justifiés.

Exemple : l’Espagne de 1898 a un score de 7. Avec un seuil de démocratie à 6, la guerre hispano-américaine compte comme une guerre entre démocraties ; avec un seuil à 8, ce cas change de catégorie.

#### Variables et niveaux de mesure

![[MADI_Ch4_Diapo_15.png]]

Une **constante** prend la même valeur pour toutes les observations : elle n’offre aucune variation à expliquer.

Pour repérer le niveau de mesure :

1. Y a-t-il un **ordre** entre les valeurs ?
2. Les **distances** entre les valeurs sont-elles mesurables ?
3. Y a-t-il un **zéro absolu**, qui signifie l’absence de la caractéristique ?

Exemple : **0 °C** n’est pas une absence de température.

#UNIGE #MADI
