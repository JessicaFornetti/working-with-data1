# working-with-data1

This project analyzes pollution indicators per city and population per country to gather insights on the main factors leading to pollution using Python. To do so the following 6 Kaggle datasets are used: [World Population by Country](https://www.kaggle.com/datasets/rajkumarpandey02/2023-world-population-by-country), [Global Air Pollution Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset), [World's Air Quality and Water Pollution Dataset](https://www.kaggle.com/datasets/victorahaji/worlds-air-quality-and-water-pollution-dataset), [World Population](https://www.kaggle.com/datasets/muhammedtausif/world-population-by-countries?select=world-population-forcast-2020-2050.csv), [World Population Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset)

This project was completed as part of the course Master of Science in Computer Science (Data Science) at TU Dublin, Ireland.

The main steps of the project are outlined below:

- **Data Cleaning and Exploration** : Inspection of each feature's distribution and outliers, correlation matrix for quantitative variables 
- **Model Training and Hyperparameter Tunning** : Exploration of different resampling methods (oversampling with SMOTE, under sampling with Random Undersampling), Logistic Regression, Random Forest, Gradient Boosting and SVM models trained in a pipeline consisting of encoding, feature selection using both filter and wrapper methods (information gain and forward sequential search) and a grid search to find the best hyperparameters for each model
- **Training The Best Model and Evaluation** : The best Random Forest model obtained was retrained and evaluated on precision, recall, f1-score, accuracy and AUC
- **Predictions on Queries Dataset** : Predictions were made on the queries dataset using the optimal model and saved in a txt file

# Repository Overview
This repository contains 1 Jupyter notebook: [CA1](CA1.ipynb).
