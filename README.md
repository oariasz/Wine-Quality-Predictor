# Wine Quality Predictor

This project compares different optimized machine learning models (supervised learning) to predict red and white wine quality rating based on physical-chemical properties.

### by Omar Arias

####  Data Source:
    - URL: https://data.world/joegr/winedata
    - Number of Instances: red wine - 1599; white wine - 4898.
    - Number of Attributes: 11 + output attribute
    - Attribute information:
        - Input variables (based on physicochemical tests):
             1 - fixed acidity
             2 - volatile acidity
             3 - citric acid
             4 - residual sugar
             5 - chlorides
             6 - free sulfur dioxide
             7 - total sulfur dioxide
             8 - density
             9 - pH
            10 - sulphates
            11 - alcohol
        - Output variable (based on sensory data):
            12 - quality (score between 0 and 10 - top quality)


#### ML Models compared:
    - Logistic Regression
    - KNN
    - Decision Trees
    - Random Forest
    - SVM
    - XGBoost

At the end we show the winner model and its accuracy.
