# Customer-Churn-
- In this project data is stored on a csv file.
- Each row represents a customer, each column contains customer’s attributes.
- The data set includes information about:
Churn: Customers who left within the last month.
Services: Service that each customer has signed up for – phone, multiple lines, internet, online
security, online backup, device protection, tech support, and streaming TV and movies.
Customer account information: How long has he been a customer ? Contract, payment
method, paperless billing, monthly charges, and total charges.
Demographic information about customers: gender, age range, and has he partners and
dependants ?
You can find more information about used Data on Kaggle: Link to Data on Kaggle
• CustomerID: The Customer ID.
• Gender : Whether the customer is a male or a female.
• SeniorCitizen: Whether the customer is a senior citizen or not (1, 0).
• Partner: Whether the customer has a partner or not (Yes, No).
• Dependents : Whether the customer has dependants or not (Yes, No).
• Tenure: Number of months the customer has stayed with the company.
• PhoneService: Whether the customer has a phone service or not (Yes, No).
• MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone
service).
• InternetService: Customer’s internet service provider (DSL, Fiber optic, No).
• OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet
service).
• OnlineBackup : Whether the customer has online backup or not (Yes, No, No internet
service).
• DeviceProtection: Whether the customer has device protection or not (Yes, No, No
internet service).
• TechSupport: Whether the customer has tech support or not (Yes, No, No internet
service).
• StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet
service).
• StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No
internet service).
• Contract: The contract term of the customer (Month-to-month, One year, Two year).
• PaperlessBilling: Whether the customer has paperless billing or not (Yes, No).
• PaymentMethod: The customer’s payment method (Electronic check, Mailed check, . . . ).
• MonthlyCharges: The amount charged to the customer monthly.
• TotalCharges: The total amount charged to the customer.
• Churn: Whether the customer churned or not (Yes or No).
As the decision tree algorithm can not handle some types (String for example ), I converted
the data to numerical. Using the withColumn instance in Pyspark, I have manually achieved
a one-hot-encoding.
The purpose of the study is to find why customers unsubscribe rather than building the best
ML model to predict customer churn for this I have used only two algorithms (Decision Tree
and Logistic Regression).
I have converted all the features to numerical then I have chosen the most suitable. I can then
see the importance of each variable and keep only the relevant ones.
