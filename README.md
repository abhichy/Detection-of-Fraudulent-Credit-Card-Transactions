# Detection-of-Fraudulent-Credit-Card-Transactions

Financial institutions and individuals both have serious concerns about fraud using credit cards. Traditional rule-based fraud detection algorithms may not be adequate to effectively identify fraudulent credit card transactions as deceptive activities become increasingly sophisticated. Due to their capacity to identify intricate patterns in data, machine learning models have emerged as viable methods for identifying credit card fraud.
The goal of this project is to create and assess several machine learning models for the identification of fraudulent credit card transactions. To begin by preprocessing the labelled credit card transaction dataset, which comprises both legitimate and fraudulent transactions. To assure the quality of the data and dealing with issues like missing values, outliers, and data imbalance. The dataset was then divided into training and testing sets for model development and assessment.
Here I implemented and compared various machine learning algorithms such as Logistic Regression, Random Forest Classifier, and Neural Networks. For the testing set, I trained these models on the training set and evaluate their performance using relevant evaluation measures such as accuracy, precision, recall, and F1-score.
To increase the model's performance, I additionally experiment with other feature engineering techniques and model hyperparameter adjustment for better optimization of the models. Also, I examined and interpret the results to determine the best effective models for detecting credit card fraud. Furthermore, here I analyzed the models' interpretability to get insights into the features and patterns that contribute to fraud detection.
The project's findings will provide important insights into the performance and interpretability of various machine learning models for credit card fraud detection. The findings can help to develop robust and effective fraud detection tools in the banking industry, hence reducing the financial losses connected with credit card fraud.

Dataset: - Using Credit Card Fraudulent Dataset from Kaggle. 

Link: - Credit Card Fraud Detection | Kaggle

To preserve cardholder privacy, the dataset is normally encrypted (V1 - V28), and it may include information such as transaction amount, transaction time, transaction type, and other transaction-related information. To ensure that the data is suitable for machine learning algorithms, the dataset is preprocessed to manage missing values, outliers, and data imbalance issues.

The dataset is separated between a training set and a testing set, using an 80:20 split ratio. The training set is used to train machine learning models, whereas the testing set is used to evaluate the learned models' performance. The goal is to create models that can correctly classify credit card transactions as fraudulent or valid based on patterns acquired from training data.

FRAMEWORK:
In this project the following structure was performed: 

Data Analysis -> Visualization -> Data Pre-processing -> Data Sampling -> Data Splitting -> Hyperparameter Tuning -> Validation.

In the portion of the data analysis and visualization, the dataset values was checked and tried to visualize the data through plots. In the data preprocessing, I worked on whether there are any missing values in the dataset or not and used Standard Scalar for all the distributions to become equal and normal distributions so that the model can learn and work properly. When it comes to the data sampling, I selected the downsampling option as the dataset was highly imbalanced because there was large number of legit transactions than the few fraudulent ones which will make the model difficult to work accurately. Downsampling will equalize the counts of legitimate and fraudulent transactions, allowing the model to work with its highest level of accuracy. 
Moreover, in data splitting I have divided the dataset into two sets training and testing set, and performed the hyperparameter tuning. In terms of the model training and evaluation, I have used three models which are the Logistic Regression model, Random Forest Classifier model, and the Neural Network model. Then I performed the hyperparameter tuning using the randomized search CV for better performance of the models and evaluated by comparing the score of precision, accuracy, recall, and F1 score.
