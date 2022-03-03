# MachineLearning
Exploring ML

## MNIST classification

## Student Grade Prediction
Uses linear regression to determine student grades.

## SVM with Sentiment Analysis Data
Applying SVM with various kernels to predict price movement of SNP500 using sentiment computed from Twitter 
data and previous days' prices. Sentiment analysis done with VADER model in a separate project with my
research group.

### Results
The best model had 9-dimensional input (previous 3 days' opening price, previous
3 days volume percent change, previous 3 days compound sentiment) using a linear kernel. Accuracy:
0.73 (see classification report in [svm_more.ipynb](https://github.com/nathanstefanik/MachineLearning/blob/main/svm/svm_more.ipynb))

### Customer Churn (IN PROGRESS)
Customer churn is a measure of how many users of a product will stop being customers. This [project](https://github.com/nathanstefanik/MachineLearning/tree/main/churn) uses a decision tree to predict if a customer will churn after a year using the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).
