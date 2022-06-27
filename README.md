![1_M2dT90tDTwIYTQcNPkcmvg](https://user-images.githubusercontent.com/71582007/175908575-3d9b8dcb-2c62-4b4e-a2e2-ae3fca2d5426.jpeg)
# Fraud-Detection
By : Ni Made Yuli Cahyani

**Goals of The Project:**
*   Learn how to classifying fraudulent and valid transactions
*   Learn how to explore data, preprocessing data and implement some various machine laerning methods and analys their performances

**About Dataset:**

Dataset that used in this project is Synthetic Financial Datasets For Fraud Detection from Kaggle.

 | About                   | Description                                                                              |
  | ----------------------- | --------------------------------------------------------------------------------------- |
  | Source                  | Synthetic Financial Datasets For Fraud Detection : [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1) |
  | Dataset Owner           | Edgar Lopez-Rojas                                                                           |
  | Lisensi                 | CC BY-SA 4.0                                                                |
  | Category                | Finance, Crime           |
  | Usability       | 8.82(Gold)                                                                            |
  | File type and size | CSV (493.53 MiB)   

This dataset was a sample of a much larger dataset generated from a simulation that closely resembles the normal day-to-day transactions including the occurrence of fraudulent transactions. The dataset was made for performing research on fraud detection methods.

Here are the variables in the dataset:
* step - `integer` - maps a unit of time in the real 
world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

* type - `string/categorical` - type of transaction: CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

* amount - `float` - amount of the transaction in local currency.

* nameOrig - `string` - customer who initiated the transaction

* oldbalanceOrg - `float` - initial balance before the transaction

* newbalanceOrig - `float` - new balance after the transaction

* nameDest - `string` - customer who is the recipient of the transaction

* oldbalanceDest - `float` - initial balance of recipient before the transaction.

* newbalanceDest - `float` - new balance of recipient after the transaction.

* isFraud - `boolean/binary` - determines if transaction is fraudulent (encoded as 1) or valid (encoded as 0)

* isFlaggedFraud - `boolean/binary` - determines if transaction is flagged as fraudulent (encoded as 1) or not flagged at all (encoded as 0). An observation is flagged if the transaction is fraudulent and it involved a transfer of over 200,000 in the local currency.
