# 📌 Fraud Detection — Financial Transactions

This project focuses on detecting fraudulent activities in financial transactions using a large-scale real-world dataset. The dataset contains **6.3 million transaction records**, with various transaction types and flags indicating whether a transaction is fraudulent.

---

## 📂 About the Dataset

The dataset provides detailed information for each transaction:

- **step**: Portion of the time period when the transaction occurred.
- **type**: Type of transaction (*CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER*).
- **amount**: Amount involved in the transaction.
- **nameOrig**: Name of the source account.
- **oldbalanceOrg**: Old balance of the source account.
- **newbalanceOrig**: New balance of the source account.
- **nameDest**: Name of the target account.
- **oldbalanceDest**: Old balance of the target account.
- **newbalanceDest**: New balance of the target account.
- **isFraud**: Fraud flag (*1 = Fraud, 0 = Not Fraud*).

### 💳 Transaction Types

- **CASH-IN**: Increasing the account balance by depositing cash through a merchant.
- **CASH-OUT**: Withdrawing cash from a merchant, decreasing the account balance.
- **DEBIT**: Sending money from the mobile money service to a bank account (similar to CASH-OUT).
- **PAYMENT**: Paying for goods or services, which decreases the sender’s balance and increases the receiver’s balance.
- **TRANSFER**: Sending money to another user through the mobile money platform.

---

## 🎯 Objective

This project aims to:
- Analyze the transaction dataset to understand patterns and trends.
- Engineer new features to improve fraud detection algorithms.
- Identify weaknesses in the existing detection methods.
- Develop and evaluate models to improve fraud detection accuracy.

---

## ⚙️ Solution

**The detailed solution, models, and results will be updated here once the project is complete.**

---

## 📑 Source

- [Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset/data)

---

Feel free to check back for updates and results!
