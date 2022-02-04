# machine-learning-challenge
Northwestern Homework #21
# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. Three different  machine learning models were created to help process this data; they are capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

## Programs Used:

* Python Pandas
* Scikit-Learn
* Keras

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

## Steps to Creating the Models:

1. Preprocessed the raw data
    * Cleaned the data.
    * Removed unnecessary columns.
    * Scaled the data with the `MinMaxScaler`.
    * Separated the data into training and testing data.

2. Tuned the models
    * Used `GridSearch` to tune model parameters.
    * NOTE: Only used `GridSearch` on the SVM and Logistic Regression models.

3. Quantified the models
    * Found the best score from the trained GridSearch model
    * Made predicitons from the hypertuned model.


## Findings
My predition was that the Deep Learning model would highest accuracy due to it using more than one layer of hidden nodes. The Support Vector Machine (SVM) and Logistic Learning models had similar accuracy (0.87)when they were hypertuned with the GridSearch parameters. The Deep Learning model has marginally higher accuracy (0.89). The scores of the hypertuned GridSearch models moderately increased when compared to the test scores of the regular SVM and Logistic Regression models.Overall, the Deep Learning model appears to be the most accurate. 



