# Evaluation-model-based-on-logistic-regressionn-l
This project trains and evaluates a **Logistic Regression** model for binary classification. Here's what it does:

1. **Creates a sample dataset** with two numerical features and a binary target variable.
2. **Saves the dataset to a CSV file** and then reloads it.
3. **Splits the dataset** into training and testing sets (80% train, 20% test).
4. **Standardizes the feature values** using `StandardScaler` to improve model performance.
5. **Trains a Logistic Regression model** on the training data.
6. **Makes predictions** on the test data.
7. **Evaluates the model** using:
   - **Accuracy**: Measures overall correctness.
   - **Precision**: Focuses on how many predicted positives are correct.
   - **Recall**: Measures how well the model detects actual positives.
   - **F1-score**: Balances precision and recall.
8. **Prints a classification report** with detailed performance metrics.

