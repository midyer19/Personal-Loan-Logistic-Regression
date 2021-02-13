# Personal Loan Campaign Logistic Regression
Prepare, Train, and Evaluate a Logistic Regression model to predict the likelihood that a bank's liability customer would buy a personal loan.

### Objective:
- The classification goal is to predict the likelihood of a liability customer buying personal loans.
- Demonstrate Exploratory Data Analysis
- Prepare the data to train a model
- Train and make predictions using a classification model
- Evaluate model

### Data Description:
The dataset in "Bank_Personal_Loan_Modelling.csv" contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

### Attribute Information:
- ID: Customer ID
- Age: Customer's age in completed years
- Experience: #years of professional experience
- Income: Annual income of the customer (\$000)
- ZIP Code: Home Address ZIP
- Family: Family size of the customer
- CCAvg: Avg. spending on credit cards per month (\$000)
- Education: Education Level. {1: Undergrad; 2: Graduate; 3: Advanced/Professional}
- Mortgage: Value of house mortgage if any. (\$000)
- Personal Loan: Did this customer accept the personal loan offered in the last campaign?  
- Securities Account: Does the customer have a securities account with the bank?
- CD Account: Does the customer have a certificate of deposit (CD) account with the bank?
- Online: Does the customer use internet banking facilities?
- Credit card: Does the customer use a credit card issued by the bank?

### Steps and tasks:
1) Import the datasets and libraries, check datatype, statistical summary, shape, null values or incorrect imputation.

2) EDA
- Number of unique in each column?
- Number of people with zero mortgage?
- Number of people with zero credit card spending per month?
- Value counts of all categorical columns.
- Univariate and Bivariate
- Get data model ready

3) Split the data into training and test set in the ratio of 70:30 respectively 

4) Use the Logistic Regression model to predict whether the customer will take a personal loan or not. Display all the metrics related to evaluating the model performance and display a confusion matrix as a heatmap.

5) Find out coefficients of all the attributes and show the output in a data frame with column names. 

6) Give conclusion related to the Business understanding of your model? 
