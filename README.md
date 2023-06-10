# CodeClause
## **Churn Prediction in Telecom Industry**
![image](https://github.com/Tejasri-123/CodeClause/assets/85396281/a9457e7f-002d-4817-9615-3231de0d6c7b)
### **Goal** - By applying the machine learning models to predict churn on an individual customer in telecom industry
### **DataSet** - https://www.kaggle.com/datasets/blastchar/telco-customer-churn
### **Workflow**
* Import Libraries
* Import Data
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Train/Test Split
* Model Selection,Training
* Model Evaluation
### **Machine Learning Algorithms Used**
* Logistic Regression
* RandomForest Classifier
### **Libraries Used** 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
**************************************
## **Market Basket Analysis using Apriori Algorithm**
![image](https://github.com/Tejasri-123/CodeClause/assets/85396281/31feb39d-b4ac-42fb-aa7b-c34fceb4a526)
### **Goal** - Finding the frequent items in a dataset by using the association rule mining
### **DataSet** - https://www.kaggle.com/datasets/muratsikli/online-retailxlsx
### **Processflow**
* Import packages
* Reading the Dataset
* Data Pre-Processing
* EDA on Data
* Applying Apriori
* Coclusion
### **Libraries Used** 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Datetime
* mlextend
## **About Apriori Algorithm**
![image](https://github.com/Tejasri-123/CodeClause/assets/85396281/a1d01e76-468d-47c6-8b2a-84af02695412)

### **Association Rule Mining**  
 Association Rule Mining is a rule-based machine learning method that helps to uncover meaningful correlations between different products according to their co-occurrence in a data set.
 
### **Support**
Support refers to the default popularity of an item and can be calculated by finding number of transactions containing a particular item divided by total number of transactions. Suppose we want to find support for item A. This can be calculated as:
    ### **Support(A) = (Transactions containing (A))/(Total Transactions)**
### **Confidence**
Confidence refers to the likelihood that an item B is also bought if item A is bought. It can be calculated by finding the number of transactions where A and B are bought together, divided by total number of transactions where A is bought. Mathematically, it can be represented as:

   ### **Confidence(A→B) = (Transactions containing both (A and B))/(Transactions containing A)**
### **Lift**
Lift(A -> B) refers to the increase in the ratio of sale of B when A is sold. Lift(A –> B) can be calculated by dividing Confidence(A -> B) divided by Support(B). Mathematically it can be represented as:

  ### **Lift(A→B) = (Confidence (A→B))/(Support (B))**
### **Steps involved in Apriori algorithm**
* Step 1: Set a minimum value for support and confidence. This means that we are only interested in finding rules for the items that have certain default existence (e.g. support) and have a minimum value for co-occurrence with other items (e.g. confidence).
* Step 2: Extract all the subsets having higher value of support than minimum threshold.
* Step 3: Select all the rules from the subsets with confidence value higher than minimum threshold.
* Step 4: Order the rules by descending order of Lift.



   

