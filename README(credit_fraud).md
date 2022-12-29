# 💸Credit Card Default Prediction

Economic Development not only improves people’s living standards but also changes people’s consumption concept and consumption mode. People are more and more inclined to spend ahead of time and mortgage their “credit” to the bank to enjoy certain things in advance. However, when consuming, people often lack rational thinking and overestimate their ability to repay loans to banks in time. On the one hand, it increases the loan risk of banks; on the other hand, it increases the credit crisis of consumers themselves . With a large number of banks selling credit cards, the phenomenon of credit card default emerges one after another. It is very important for banks to effectively identify high-risk credit card default users.

## 📊 Data Source
In our dataset we have 25 columns which reflect various attributes of the customer. The target column is default.payment.next.month , which reflects whether the customer defaulted or not. Our aim is to predict the probability of default given the payment history of the customer. I have built my model using a public dataset available on kaggle.

https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

## 🎯Approach
Notebook Name : model trainig and selection.ipynb
Custom Defined Modules Used : None
Notebook Description :
General Data Visualisation, Analysing relation between features and target, Using Boxplots to visualize outliers, Data Sanity Checks, building models, evaluating them,
choosing and saving the best model

Notebook Name : User interface.ipynb
Custom Defined Modules Used : None
Notebook Description :
Deployment of web application 


Final Model is stored as pickle file randomforestclassifiermodel.pkl.

Author✍
Apoorv Tyagi
