
# Spam Detection Classification Challenge

---

## Overview

This repository contains the solution to the Spam Detection Classification Challenge, which focuses on training and evaluating machine learning models to classify emails as spam or not spam. The project leverages Logistic Regression and Random Forest models to determine the most effective classification method.

---

## Key Tasks

The analysis consists of the following major tasks:

1. Data Retrieval:

- Importing the spam classification dataset from an online source.
- Loading the data into a Pandas DataFrame for analysis.

2. Data Cleaning and Preparation:

- Creating labels (y) from the "spam" column, where 1 represents spam and 0 represents legitimate emails.
- Defining the features (X) from the remaining columns.
- Checking for class imbalances in the dataset.

3. Data Splitting and Feature Scaling:

- Splitting the dataset into training and testing sets using an 80/20 ratio.
- Standardizing the feature data using StandardScaler to improve model performance.

4. Model Training and Evaluation:

- Training a Logistic Regression model and evaluating its accuracy.
- Training a Random Forest Classifier and evaluating its accuracy.
- Comparing model performance to determine which method is more effective.

5. Results Interpretation:

- Analyzing the accuracy scores of both models.
- Discussing model selection trade-offs between simplicity and performance.

---

## How to Run

Clone the Repository: git clone https://github.com/CCIEMikeG/classification-challenge.git cd classification-challenge


1. Set Up the Environment:

- Ensure Python 3.x is installed.
- Install required libraries: pip install -r requirements.txt

2. Run the Notebook:

- Open the spam_detector.ipynb notebook using Jupyter Notebook or VS Code.
- Execute each cell sequentially to train the models and analyze the results.

---

## Dependencies:

Ensure the following Python libraries are installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries with: pip install pandas numpy matplotlib scikit-learn

---

### Results

The analysis successfully:

- Imported and processed the spam classification dataset.
- Standardized features to optimize model performance.
- Trained both Logistic Regression and Random Forest models.
- Evaluated model accuracy:
  - Logistic Regression Accuracy: 92.73%
  - Random Forest Accuracy: 95.87%
- Determined that the Random Forest model provided better accuracy for spam classification.

---

## License

This project is licensed under the MIT License.