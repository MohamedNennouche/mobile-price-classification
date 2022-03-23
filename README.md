## :iphone: App price classification
The goal is the realization of a classifier allowing the classification of 2000 models of telephones according to 4 categories of price (0, 1, 2 and 3) according to several parameters such as the duration that holds the battery, the size of the screen or several functionalities available or not like the wifi or the bluetooth. 


Dataset that you can find on Kaggle [here]("https://www.kaggle.com/iabhishekofficial/mobile-price-classification")
## :white_check_mark: Organization of the repository 
This repository consists of the following files: 
- notebook-price.ipynb : contains the Jupyter notebook processing the project
- train.csv : dataset containing the training and test instances of the classification models
- test.csv : dataset that can be used for clustering

## :memo: Software requirements
This project uses : 
- Python 3.8 and up

As well as the following Python packages and modules: 
- scikit-learn
- Numpy
- Pandas
- Matplotlib (module Pyplot)
- Seaborn 

## :scroll: Content of the project
1) A data visualization allowing the visualization of the distribution of different variables
2) Pre-processing of the data (normalization and subdivision of the dataset in two for training and testing)
3) Classification without dimension reduction using 
    * A KNN model
    * A Random Forrest based model
    * A decision tree based model
    * A SVM

## :straight_ruler: Performance achieved
| Algorithm | Accuracy in test (%)
|--- |:-: |
| KNN (without normalization) | 94.17 |
| Random Forrest | 89.17 |
| Decision Tree | 85.33 |
| SVM (without normalization) | 96 |