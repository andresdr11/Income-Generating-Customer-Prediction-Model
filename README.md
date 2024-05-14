# Predicting Revenue Generating Customers with Machine Learning

### Project Description:
This project aims to develop and implement three machine learning models to predict the likelihood of a customer generating revenue through online purchases from a retail company's website. The models to be analyzed are:

* Predictive Logistic Regression: A classical machine learning model for binary classification.
* Neural Networks: Capable of modeling complex non-linear relationships between variables.
* Random Forests: An ensemble of decision trees offering high accuracy and robustness.

The ultimate goal is to determine which of the three models performs best for the prediction task. Subsequently, the chosen model will be used to implement specific actions towards customers with a higher probability of making online purchases.

### Methodology:
Data Collection and Preprocessing: A dataset will be collected that includes information on customer characteristics, website behavior, and past purchases. Data preprocessing will be conducted to handle missing values, encode categorical variables, and normalize numerical variables.

Model Training and Evaluation: Each of the three machine learning models will be trained using a cross-validation technique to prevent overfitting. The performance of each model will be evaluated using metrics like accuracy, recall, and AUC (Area Under the ROC Curve).

Best Model Selection: The model with the best performance based on the evaluation will be selected.

### Conclusion:
The neural network model's higher AUC and sensitivity indicate its greater ability to distinguish between customers who will and will not generate revenue, making it the most valuable tool for targeted customer engagement.

#### Additional Information:
AUC (Area Under the ROC Curve): this metric measures the ability of a model to distinguish between two classes (e.g., customers who generate revenue and those who do not).

Sensitivity: The proportion of actual positive cases that are correctly identified by the model.

In this context, sensitivity is more important than other metrics because it is crucial to identify as many customers as possible who are likely to generate revenue.

