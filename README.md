# CODTECH

TITLE: CODTECH IT SOLUTIONS INTERNSHIP- TASK DOCUMENTATION: CREDIT CARD FRAUD DETECTION USING ML ALGORITHMS

DATA SCIENCE TASK ONE:
CREDIT CARD FRAUD DETECTION
Build a machine learning model to identify fraudulent credit card
transactions. . Preprocess and normalize the transaction data,
handle class imbalance issues, and split the dataset into training
and testing sets. .Train a classification algorithm, such as
logistic regression or random forests, to classify transactions as
fraudulent or genuine.Evaluate the model's performance using
metrics like precision, recall, and F1-score, and consider
techniques like oversampling or under sampling for improving
result.Additionally, Imagine you've been tasked with creating
comprehensive documentation for a CREDIT CARD FRAUD DETECTION
project.

Introduction: 
NAME: ODDAM RANITHA
ID: ICOD6614

Credit card fraud is a major concern for both consumers and financial institutions. Fraudulent transactions can lead to financial losses and damage to the reputation of financial institutions. Machine learning techniques have been used extensively to detect fraudulent transactions. In this project, we use logistic regression to classify transactions as either legitimate or fraudulent based on their features.

Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Data:

The data used in this project is a CSV file containing credit card transaction data. The data has 31 columns and 284,807 rows. The "Class" column is the target variable, which indicates whether the transaction is legitimate (Class = 0) or fraudulent (Class = 1).

Preprocessing:

Before training the model, we first separate the legitimate and fraudulent transactions. Since the data is imbalanced, with significantly more legitimate transactions than fraudulent transactions, we undersample the legitimate transactions to balance the classes. We then split the data into training and testing sets using the train_test_split () function.

Model:

We use logistic regression to classify transactions as either legitimate or fraudulent based on their features. Logistic regression is a widely used classification algorithm that models the probability of an event occurring based on input features. The logistic regression model is trained on the training data using the LogisticRegression () function from scikit-learn. The trained model is then used to predict the target variable for the testing data.

Evaluation:

The performance of the model is evaluated using the accuracy metric, which is the fraction of correctly classified transactions. The accuracy on the training and testing data is calculated using the accuracy_score() function from scikit-learn.

Streamlit Application:

We use Streamlit to create a user interface for the credit card fraud detection project. The Streamlit application allows the user to upload a CSV file containing credit card transaction data, and the uploaded data is used to train the logistic regression model. The user can also input transaction features and get a prediction on whether the transaction is legitimate or fraudulent.

Conclusion:

In this project, we used logistic regression to detect fraudulent credit card transactions. We achieved a high accuracy on both the training and testing data, indicating that the model is effective at detecting fraudulent transactions. The Streamlit application provides an easy-to-use interface for detecting fraudulent transactions in real-time.

About The Code:
This is a machine learning project for credit card fraud detection. The project uses a logistic regression model to classify transactions as either legitimate or fraudulent based on their features.

The code begins with importing necessary libraries such as numpy, pandas, scikit-learn, and Streamlit. Then, the layout of the Streamlit application is set using the st.set_page_config() function. The load_data() function is defined to load data from a CSV file, which is uploaded by the user using the file_uploader() function. The train_model() function is defined to train a logistic regression model on the uploaded data. The function first separates the legitimate and fraudulent transactions, undersamples the legitimate transactions to balance the classes, and then splits the data into training and testing sets using the train_test_split() function. The logistic regression model is then trained on the training data and evaluated on the training and testing data using the accuracy_score() function.

The parse_transaction_string() function is defined to parse a comma-separated string of transaction features and convert it into a dictionary with feature names as keys and feature values as values.

Finally, the Streamlit application is created using the st.title() function to set the title, the file_uploader() function to allow the user to upload a CSV file, and the text_input() function to allow the user to input transaction features and get a prediction. The uploaded data is loaded using the load_data() function, and the model is trained and evaluated using the train_model() function. The training and testing accuracies are displayed using the st.write() function, and the user can input transaction features using the text_input() function.



DATA SCIENCE TASK TWO:

TITANIC SURVIVAL PREDICTION
Use the Titanic dataset to build a model that predicts whether a
passenger on the Titanic survived or not. This is a classic
beginner project with readily available data. . The dataset
typically used for this project contains information about
individual passengers, such as their age, gender, ticket class,
fare, cabin, and whether or not they survived..Additionally,
Imagine you've been tasked with creating comprehensive
documentation for a TITANIC SURVIVAL PREDICTION project.

DATASET USED: https://www.kaggle.com/competitions/titanic


