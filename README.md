## Classification des téléphones suivant plusieurs caractéristiques
Le but est la réalisation d'un classifieur permettant la classification de 2000 modèles de téléphones suivant 4 catégories de prix (0, 1, 2 et 3) suivant plusieurs paramètres tels que la durée que tient la batterie, la taille de l'écran ou plusieurs fonctionnalités disponible ou non comme le wifi ou encore le bluetooth. 


Dataset que vous pouvez retrouver sur Kaggle [ici]("https://www.kaggle.com/iabhishekofficial/mobile-price-classification")
## Organisation du dépôt 
Ce dépôt est constitué des fichiers suivants : 
- notebook-price.ipynb : contient le notebook Jupyter traitant le projet
- train.csv : dataset contenant les instances d'entrainement et de test des modèles de classification
- test.csv : dataset utilisable pour du clustering éventuellement

## Pré-requis logiciel
Ce projet utilise : 
- Python 3.8 et +

Ainsi que les package et modules Python suivants : 
- scikit-learn
- Numpy
- Pandas
- Matplotlib (module Pyplot)
- Seaborn 

## Contenu du projet 
Le projet (disponible au niveau du notebook Jupyter) est constitué des étapes suivantes : 
1) Une visualisation des données permettant la visualisation de la distribution de différentes variables
2) Pré-traitement des données (normalisation et subdivision du dataset en deux pour l'entrainement et le test)
3) Classification sans réduction de la dimension utilisant 
    * Un modèle KNN
    * Un modèle basé sur un Random Forrest
    * Un modèle basé sur un arbre de décision
    * Un SVM

## Performances atteintes
|   Algorithme choisi    |   Précision en test (%)    |
|---    |:-:    |
|   KNN (avec normalisation)    |   63.67    |
|   KNN (sans normalisation)    |   94.17    |
|   Random Forrest    |    88.83  |
|   Decision Tree    |   85.33   |
|   SVM (avec normalisation)    |   87.83    |
|   SVM (sans normalisation)    |   96    |

## Remarques
- Dans un autre projet ayant des variables sous forme de catégories, il serait préférable de ne pas utiliser de normalisation avec StandardScaler en utilisant d'autres types de normalisation, par exemple MinMax ou autre. 
- Une autre manière de travailler serait de normaliser que les variables sous forme de distribution et laisser les variables sous forme de catégories