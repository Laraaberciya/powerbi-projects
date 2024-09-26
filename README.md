# Bank Customer Churn Analysis

## Business Requirement Document

### Data Dictionary

- **RowNumber**: Represents the record (row) number and has no effect on the output.
- **CustomerId**: Contains random values with no impact on customer churn.
- **Surname**: The surname of a customer has no influence on their decision to leave the bank.
- **CreditScore**: A customer’s credit score may affect churn, as those with higher scores are less likely to leave the bank.
  - **Credit Score Ranges**:
    - Excellent: 800–850
    - Very Good: 740–799
    - Good: 670–739
    - Fair: 580–669
    - Poor: 300–579
- **Geography**: A customer’s location may influence their decision to leave the bank.
- **Gender**: Exploring whether gender has any role in customer churn.
- **Age**: Age is a key factor, as older customers tend to be more loyal and less likely to leave.
- **Tenure**: The number of years a customer has been with the bank. Longer-tenured customers are generally more loyal.
- **Balance**: Customers with higher balances are less likely to leave the bank.
- **NumOfProducts**: Refers to the number of products a customer has purchased through the bank.
- **HasCrCard**: Indicates whether a customer has a credit card (1: Yes, 0: No). Credit card holders are less likely to leave.
- **IsActiveMember**: Active members are less likely to leave the bank (1: Active, 0: Inactive).
- **Estimated Salary**: Customers with lower salaries tend to be more likely to leave.
- **Exited**: Shows if the customer left the bank (1: Yes, 0: No).
- **Bank DOJ**: The date when the customer joined the bank.

### Data Gathering

The following data assets were used to pull information related to bank customers and their associated details:

- **ActiveCustomer**
- **Bank_Churn**
- **CreditCard**
- **CustomerInfo**
- **ExitCustomer**
- **Gender**
- **Geography**

### Churn Analysis

Customer churn is a critical concern for banks as it affects overall revenue and profitability. Analyzing the data provides insights into factors that lead customers to leave. These insights can help develop loyalty programs and retention campaigns to keep as many customers as possible.

---

**Objective**: Identify the key factors contributing to customer churn to help banks improve customer retention strategies.

