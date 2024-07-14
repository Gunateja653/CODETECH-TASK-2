# CODETECH-TASK-2
Credit_Card Fraud_Detection ML model
# Boston-Housing-mL-model
The Boston Housing Dataset
* **NAME:** Guna Teja sarvan Patnaik
* **COMPANY:** CODETECH IT SOLUTIONS
* **ID:** CT4ML4739
* **DOMAIN:** MACHINE LEARNING
* **DURATION:** 25 JULY 2024
* **MENTOR:** Muzammil Ahmed

# Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

1. **Data Loading and Exploration:**
   - Load the Credit_Card Fraud_Detection Dataset from '/content/creditcard[1].csv'.
   - Perform exploratory data analysis (EDA) to understand the dataset's characteristics, including descriptive statistics and visualizations.

2. **Outlier Detection and Handling:**
   - Identify and handle outliers in the 'Class' column to improve model performance.

3. **Feature Selection:**
   - Utilize mutual information Classifier to select the most relevant features for predicting 'Class'.

4. **Model Selection and Evaluation:**
   - Experiment with different regression models, including logisticRegression ,Random forest classifier, Decision Tree Regressor, and XGBoost Regressor.
   - Evaluate model performance using metrics  asaccuracy_score

5. **Prediction System:**
   - Develop a prediction system using the best-performing model (RandomForestClassifier in this case) to predict 'Class' based on user-provided input values for the selected features.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- RandomForestClassifier

## Usage

1. Install the required dependencies.
2. Run the provided code in a Google Colab environment or a Jupyter Notebook.
3. Follow the prompts to input values for the selected features and obtain the predicted 'class'.

## Model Training:

RandomForestClassifier library is used to create and train a Classifiction model.
Model parameters such as the objective function  accuracy score

![Screenshot 2024-07-14 2000400](https://github.com/user-attachments/assets/bd5cb935-cfc3-48d0-b0ba-cda34d063712)
