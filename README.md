# Financial Payment Services Fraud Detection Analysis
## Arunava Kumar Chakraborty


### Introduction:

This notebook represents a Machine Learning-based predictive approach to explore the given **Fraud** dataset. The Dataset has been uploaded in my [Kaggle repository](www.kaggle.com/arunavakrchakraborty/financial-payment-services-fraud-data).

I have Proposed an experimental approach to develop a Fraud detection model to predict future Fraud customers based on the related features. The best feature variables will be selected on the basis of their linear relationships. Furthermore, the **Logistic Regression** classifier will be developed to build the predictive system.

The classifier will be trained using the training data to predict the fraud cases from the validation data to identify the fraudulent customer.
### Data Description:

Here the description of the database has been presented.

- **step** - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

- **type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

- **amount** - amount of the transaction in local currency.

- **nameOrig** - customer who started the transaction

- **oldbalanceOrg** - initial balance before the transaction

- **newbalanceOrig** - new balance after the transaction

- **nameDest** - customer who is the recipient of the transaction

- **oldbalanceDest** - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

- **newbalanceDest** - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

- **isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

- **isFlaggedFraud** - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

### Workflow of the Project:

    i. Data Preprocessing,

        ii. Exploratory Data Analysis,
    
            iii. Predictive Analysis.
                    
#### - By Arunava Kumar Chakraborty
