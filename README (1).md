# Fees and Commissions Notebook

This notebook walks through applying fees to a transaction through a transaction type. It follows the following steps.

---


### 1. Setting up LUSID and necessary instruments/transaction portfolio
Using the wildcards-commission-txns.csv file

### 2. Create property definition for fees to live
In this notebook, the fees are stored as derived properties and calculated at the derived property level

### 3. Create a Fees Side that uses those fee properties for the units & amounts field

### 4. Create a buy transaction type with the regular movements and add a Fee Carry movement that leverages the new fee side. Also update the Total Conideration calculation (in our case we chose to include the fees + grossConsideration)

### 5. Create transactions with this transaction type

