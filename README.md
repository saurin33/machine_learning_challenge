Exoplanet Exploration

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

### Preprocess the Data

* Preprocessed the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

Comparison Between 3 models:

Random Forest : 
Accuracy Score : 87.58%
F1_Score : (79%, 83%, 98%)
Best Parameters: max_depth: 30, max_features= auto, n_estimators=200

Logistic Regression: 
Accuracy Score: 87%
F1_score: 72%, 79%, 99%
Best Parameters: C = 100, penalty: Lasso Regression(l2)

Support Vector Machine: 
Accuracy Score: 88.91%
F1_score: 76%, 82%, 99%
Best Parameters: c = 1000, gamma=0.1

If we see just the accuracy score SVM has little edge over Random Forest, even though I choose Random Forest to predict the neccesary task becasue it's more rebust and better predictor with more data. 

