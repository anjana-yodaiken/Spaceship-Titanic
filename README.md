# Spaceship Titanic Kaggle Project

## Project description 

The Spaceship Titanic collided with a spacetime anomaly. Although the ship stayed mostly intact, almost half of the passengers were transported to an alternate dimension. The task in this project is to predict whether or not passengers were transported to an alternate dimension. 

Full details can be found on the Kaggle competition page: https://www.kaggle.com/competitions/spaceship-titanic/overview

## Repository description

The data provided by the competition can be found in the `data` folder, this includes:
- `train.csv`
- `test.csv`
- `sample_submission.csv`

The full notebook can be found in `spaceship_titanic.ipynb`, this notebook includes: 
- Data loading
- Exploratory data analysis
    - Univariate data analysis 
    - Multivariate data analysis 
    - Cardinality assessment
- Data preprocessing 
    - Preprocessing helper functions 
    - Preprocessing pipelines
- Modelling 
    - Random Forest 
    - Logistic Regression 
    - Support Vector Classification 
    - XGBoost 
    - Decision Tree Classifier 
    - KNeighbours 
    - Voting Classifier 
- Hyperparameter tuning 
    - Random Forest
    - Logistic Regression 
    - XGBoost 
- Final model (Voting Classifier including Random Forest, XGBoost, Logistic Regression)
- Submission creation 
- Leaderboard score

## Leaderboard score 

| Submission | Score |
|--|--|
| base | 0.79167 |
| final | 0.80406 |