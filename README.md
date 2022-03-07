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
1- Une visualisation des données permettant la visualisation de la distribution de différentes variables
2- Pré-traitement des données (normalisation et subdivision du dataset en deux pour l'entrainement et le test)