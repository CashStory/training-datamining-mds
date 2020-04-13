

<img src="https://cashstory.com/_nuxt/img/8259e1b.png" alt="drawing" width="250" align='left'/>



<br>

<br> 

# Data mining training 

### Introduction générale - My Digital School Rennes





## Définition 

Le Data Mining c’est l’ensemble des algorithmes, méthodes et technologies inspirés de plusieurs autres disciplines, propres ou non au DM pouvant servir à **remplacer ou à aider l’expert humain** ou le décideur dans un domaine spécifique dans le cadre de prise de décision, et ce en **fouillant dans des bases** de données décisionnelles des corrélations, des associations, des comportements homogènes, des formules de lien entre  indicateurs, des spécification par rapport à une **thématique bien déterminée.**

## Enjeux

- Simplifier la production de données ou  informations structurées et porteuses de sens
- Créer du sens et des connaissances à partir de données non enrichies et non structurées
- Analyser des tendances sur la durée
- Permettre la création de modèles sur des historiques de données
- Analyse prédictive

## La pyramide DIKW

![Pyramid: Data – Information – Knowledge – Wisdom (DIKW)  ](https://www.researchgate.net/profile/Marcin_Gajzler/publication/302062058/figure/fig1/AS:460357551562752@1486769201067/Pyramid-Data-Information-Knowledge-Wisdom-DIKW.png)





## Les applications du data mining





<img src="https://github.com/CashStory/training-datamining-mds/blob/master/datamining-applications.PNG?raw=true" alt="drawing" width="1250" align='left'/>



- **<u>Analyse de données</u>** : Résumer et visualiser l’activité de l’entreprise à travers

  des **indicateurs** **pertinents**

- **<u>Segmentation</u>** : 

  - Aucune variable décisionnelle, information **quantitative**
    - Les variables d’entrées servent à créer des groupes homogènes
    - Les individus de chaque groupe se ressemblent le plus
    - Les groupes d’appartenances obtenus se distinguent le plus
  - Trouver les variables métiers influençant la répartition en groupes
  - Affecter les individus à leurs nouveaux groupes d’appartenance 
  - Plusieurs méthodes et techniques pour segmenter :
    - Partionnement : k-means
    - Hiérarchique : CAH
  - Trouver les **comportements** **typiques** des clients.

- **<u>Associativité</u>** : 

  - Analyse du chariot : recherche des articles les plus/moins associés
  - Médecine : les symptomes associés 

- **<u>Classification</u>** **:** 

  - La variable décisionnelle est **qualitative**
    - Un dossier de crédit peut être classifié : BON ou MAUVAIS
    - Un patient peut présenter un fort risque de maladie cardiaque
    - Un client peut présenter un comportement atypique
  - La Classification a pour objectifs :
    - Détecter les variables possédant un lien fort avec la variable décisionnelle
    - Construire un modèle de classification liant ces variables à la décision
  - Plusieurs méthodes et techniques pour classifier :
    - Arbre de décision
    - Forêts Aléatoires
    - K-NN *k*-nearest neighbors
    - Séparateur à vaste Marge SVM
    - Régression Logistique

- <u>**Scoring**</u> :

  - Evaluation de campagne terrain : déterminer **l'efficacité** **de** **la** **communication** avec les clients.
  - Marketing ciblé : optimiser les chances d'obtenir des réponses (positives) de la part des clients à une offre particulière par un ciblage plus précis, mettant en évidence les clients avec une forte probabilité de réponse.
  - Data mining & CRM : le datamining a beaucoup d'applications qui peuvent apporter un soutien considérable au marketing et à la gestion de la relation client (*faire* *correspondre* *des* *profils* *des* *clients* *avec des* offres produits *afin* *d’augmenter* *le* *taux* *de* *conversion* *:* *cross* *selling*)

- **<u>Régression Linéaire</u>** :

  - La variable décisionnelle est **quantitative**
    - Prédire les tendances salariales la prochaine année
    - Prédire le meilleur pourcentage de réduction de coûts
    - Construire un modèle générique pour l’estimation de la consommation de carburant
  - La régression a pour objectifs :
    - Détecter les variables possédant un lien fort avec la variable cible
    - Construire un modèle prédictif avec l’ensemble des variables pertinentes afin de prédire la variable d’intérêt
    - Détecter les individus atypiques ou les aberrances
  - Régression Linéaire
    - Méthode des moindres carrés
    - Meilleurs prédicteurs
  - Applications :
    - Pricing : Déterminer le **prix** **"optimal"**convenable pour un produit.
    - Analyse Coûts-bénéfices : Identifier les produits et les campagnes les **plus** **rentables**





## Data mining & finance



### Banques & finances

- **Gestion** **de** **risque** **-** évaluer un risque de défaut. Au delà des techniques classiques de scoring, d'autre techniques de modélisation issues de l'intelligence artificielle permettent d'augmenter la maitrise de ces risques.
- **Crédit** **scoring** **-** évaluer le risque de non remboursement (technique data mining la plus déployée)
- **Détection** **de** **fraudes** **-** identifier plus facilement et plus rapidement les éventuelles transactions frauduleuses
- **Segmentation** **-** améliorer la connaissance de vos clients par la découverte de groupes homogènes et par une caractérisation selon leur profil 
- **Prédiction** **-** prévoir quels clients seront intéressés par une offre



### Vente,  Distribution,  Marketing

- Détection d'associations de comportements d'achat
- Découverte de caractéristiques de clientèle.
- Prédiction de probabilité de réponse aux campagnes de mailing.



### Assurances 

- Découverte d'associations des demandes de remboursements
- Identification de clients potentiels de nouvelles polices d'assurances.
- Détection d'association de comportements pour la découverte de clients à risque.
- Détection de comportement frauduleux.
- Prendre un client à un concurrent.
- Faire monter en gamme un client que l’on détient déjà.



Prise de Décision, Prédiction, Exploitation de données, etc.



## Les méthodes de data mining 



### Deux familles de techniques

**1- Apprentissage automatique** (Analyse descriptive)

- S’appliquent seulement sur les données quantitatives.
- Fournissent directement des résultats : à interpréter et à utiliser !
- Visent à mettre en évidence des connaissances **présentes** mais cachées par le volume des données
- Réduisent, résument, synthétisent les masses de données
- **pas de variable « cible** **»**



**2- Apprentissage supervisées** (Analyse prédictive)

- Fournissent un modèle (et non pas  des résultats), créé à partir d’un entrepôt d’apprentissage, testé et  validé sur un entrepôt de test, et  utilisé dans les problèmes de prise de décision sur des entrepôts de travail 
- visent à découvrir de nouvelles  informations à partir des  informations présentes :  connaissances, décisions 
- expliquent mieux les données
- Une(des) variable(s) « cible(s)»



### Types d'applications



<img src="https://github.com/CashStory/training-datamining-mds/blob/master/types-dapplications.PNG?raw=true" alt="drawing" width="1250" align='left'/>





2 familles de techniques : 

- Méthodes Non Supervisées
  - Analyse en Composantes  Principales ACP
  - Méthodes des Centres  Mobiles K-means
  - Classification Ascendante  Hiérarchique CAH
  - Règles  Associatives  Apriori
- Méthodes Supervisées
  - Arbres de Décisions
  - Analyse Linéaire Discriminante
  - Régression
  - Plus Proche voisin kNN
  - Réseaux de Neurones
  - Séparateur à Vaste Marge  SVM
- 




## **Pro**gramme 

Dans cette formation nous allons: 

- Apprendre les bases théoriques du Data Mining 
- Developper ensemble des cas d'usages simples sur le modèle CRISP (ju
- Appliquer le data mining en en mode collaboratif via : 
  - https://github.com/
  - https://colab.research.google.com/



## Ressources : 

- Data mining in Bio 
  - https://www-lmgm.biotoul.fr/enseignements/M2Pro_Bioinfo/intro.pdf
- DIKW, la pyramide qui inspire le futur des moteurs de recherche
  - https://www.scriptol.fr/web/dikw.php

- Why using CRISP-DM will make you a better Data Scientist
  - https://towardsdatascience.com/why-using-crisp-dm-will-make-you-a-better-data-scientist-66efe5b72686

