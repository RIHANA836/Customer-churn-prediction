# Customer Churn Prediction  

## **Overview**  

This repository contains a machine learning project focused on **predicting customer churn** for a financial institution. The goal is to analyze customer data and identify factors that contribute to customer retention and churn. The insights from this project can help businesses take **proactive measures** to reduce churn and improve customer loyalty.  

## **Objective**  

The objective of this project is to develop a predictive model that can:  
- Identify customers who are likely to **churn** (discontinue service).  
- Analyze key factors influencing customer churn.  
- Provide insights to help businesses improve customer retention strategies.  

## **Dataset**  

The dataset contains **10,000 rows and 14 columns**, including demographic, financial, and account-related information.  
Key features include:  
- **CreditScore** – Customer’s creditworthiness score.  
- **Geography** – Country of residence (France, Spain, Germany).  
- **Age** – Customer’s age.  
- **Tenure** – Number of years with the company.  
- **Balance** – Account balance.  
- **NumOfProducts** – Number of financial products held.  
- **HasCrCard** – Credit card ownership (1 = Yes, 0 = No).  
- **IsActiveMember** – Whether the customer is active (1 = Yes, 0 = No).  
- **Exited** – Target variable (1 = Churned, 0 = Retained).

## **Results & Insights**  

### **Model Performance**  

The models used for predicting customer churn include **Logistic Regression** and **Random Forest Classifier**. The results are as follows:  

- **Logistic Regression Accuracy**: **81.6%**  
- **Random Forest Accuracy**: **86.7%**  

The **Random Forest model** performed better in terms of accuracy and recall, making it a preferable choice for customer churn prediction.  

### **Key Insights on Customer Churn**  

- **Geography Matters**: Customers from **Germany** have a higher churn rate compared to those from France and Spain.  
- **Age Factor**: **Older customers (above 40 years)** are more likely to churn.  
- **Customer Activity**: **Inactive members** have a significantly higher chance of leaving.  
- **Number of Products**: Customers with **only one product** tend to churn more, while those with multiple products are more likely to stay.  
- **Credit Score & Balance**: While **credit score does not show a strong impact**, customers with a **zero balance** tend to churn more frequently.

## Steps to Run the Project  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/RIHANA836/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction

2.**Install Dependencies**
   Ensure you have Python 3.x installed, then run:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

3. **Open Jupyter Notebook**
   Start Jupyter Notebook by running:
   ```bash
   jupyter notebook

4.**Open the Notebook File**
   Navigate to Customer_Churn_Prediction.ipynb in Jupyter Notebook.

5.**Run the Notebook**

   Execute the cells sequentially

Evaluate performance


## **Contributors**  

- **Rihana Iqbal** - [GitHub Profile](https://github.com/RIHANA836)  
