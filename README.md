## **Uncovering Patterns Behind Telco Customer Churn**  

### **-By Ferry Ath Thaariq Mudhofir**  

### Based on the [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

---

<b> Domain Background </b>

Customer churn is a critical challenge for telecommunication companies. It represents the loss of customers who discontinue their subscriptions, impacting revenue and profitability. Understanding the reasons behind customer churn and identifying patterns early can help businesses design better retention strategies.  

In the telecom sector, customer churn can be influenced by a variety of factors, such as service quality, pricing, contract duration, and customer satisfaction. Machine learning provides an effective approach to analyze these factors and predict churn, enabling companies to take proactive measures to retain valuable customers.  

---

<b> Problem Statement </b>

The problem provided by the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) can be defined as a binary classification task. The goal is to predict whether a customer will churn (discontinue the service) or stay, based on various features such as demographic data, customer account information, and service usage metrics.  

---

</b> Datasets and Inputs </b>

The [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) consists of a single CSV file containing information on 7,043 customers. Each row represents a customer and includes various features related to demographics, service usage, and account details. The dataset contains the target variable **Churn**, with binary values:  
- **Yes**: The customer has churned.  
- **No**: The customer has not churned.  

The key features of the dataset include:  
1. **Demographics:** Gender, Senior Citizen, Partner, Dependents.  
2. **Account Information:** Contract type, Payment method, Monthly charges, Total charges.  
3. **Service Usage:** Internet service type, Online security, Tech support, Streaming services.  

The dataset provides a rich set of features that can be analyzed to uncover important factors influencing churn and to build a predictive model for customer retention.  

---

</b> Dataset Overview </b>

Below is a summary of the dataset structure and connectivity:  

| **Feature Category**       | **Description**                                                                 |  
|----------------------------|---------------------------------------------------------------------------------|  
| Demographics               | Information about customer profiles, such as age and family status.             |  
| Service Details            | Features related to the services used by the customers (e.g., phone or internet services). |  
| Account Information        | Data about the customer's account, such as billing and contract type.           |  
| Target Variable            | **Churn** (Yes/No) indicating whether the customer discontinued the service.     |  

---
