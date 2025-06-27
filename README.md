# ai_ml_elevate_labs_task4

This task implements a binary classification model using Logistic Regression on the Breast Cancer dataset. The dataset was preprocessed by converting the target variable into binary form (diagnosis column) and standardizing the features. A train-test split was performed to evaluate model generalization. The Logistic Regression model was trained using Scikit-learn, and its performance was evaluated using a confusion matrix, precision, recall, and ROC-AUC score. The decision threshold was tuned to observe changes in sensitivity and specificity. Additionally, the sigmoid function, which maps predicted values to probabilities, was visualized to explain how logistic regression makes binary predictions.

The sigmoid function is a function which maps any value number to the range of (0,1) which helps in binary classification.
The formula for sigmoid function is sigmoid = 1 / (1 + np.exp(-z))
