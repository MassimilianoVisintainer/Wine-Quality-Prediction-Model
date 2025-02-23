## Wine Quality Prediction with Random Forest Classifier

### Introduction

This repository contains the code for predicting wine quality using a Random Forest Classifier. The code is based on a Jupyter notebook originally generated by Colab.

### Functionality

This code performs the following tasks:

* **Import Libraries:** Imports necessary libraries like pandas, numpy, matplotlib, seaborn for data manipulation, visualization, and machine learning with scikit-learn.
* **Data Loading:** Loads the red wine quality dataset (`winequality-red.csv`) into a pandas dataframe.
* **Data Exploration:**
  * Displays the first few rows (`head()`).
  * Checks data shape (number of rows and columns).
  * Provides summary statistics (`describe()`).
  * Identifies missing values using `np.sum(wine_dataset.isnull())`.
* **Data Analysis and Visualization:**
  * Analyzes the distribution of wine quality using a countplot (seaborn).
  * Creates barplots to visualize the relationship between quality and specific features (volatile acidity, citric acid).
  * Generates a heatmap using seaborn to explore correlations between features.
* **Data Preprocessing:**
  * Separates the features (independent variables) from the target label (quality).
  * Binarizes the quality label (good or bad quality based on a threshold).
  * Splits the data into training and testing sets using `train_test_split` from scikit-learn to ensure model generalizability.
* **Model Training:** Trains a Random Forest Classifier model using `RandomForestClassifier` from scikit-learn.
* **Model Evaluation:**
  * Evaluates the model's accuracy on both training and testing data using `accuracy_score`.
  * Reports the accuracy scores for both sets.
* **Prediction System:** Demonstrates how to use the trained model to predict the quality of a new wine sample.

### Running the Code

This code is intended to be run in a Jupyter Notebook environment. You can follow these steps:

1. Download the code and data files.
2. Open the `Wine_Quality_Prediction.ipynb` file in a Jupyter Notebook environment.
3. Run the code cells sequentially.

### Dependencies

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

**Note:** This is a basic example of Wine Quality prediction using a Random Forest Classifier. More advanced techniques like feature engineering, hyperparameter tuning, and different classification algorithms can be explored for potentially improved performance.


