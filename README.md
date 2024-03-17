# CreditFraudImbalancedData

Dataset Overview

# Context
The detection of fraudulent activities on credit card transactions is crucial for credit card companies to ensure that their clients are not billed for purchases they did not make.

Content
This dataset comprises credit card transactions by European holders in September 2013. Over the course of two days, it records 492 fraudulent transactions out of a total of 284,807. The dataset is significantly skewed, with fraud cases representing only 0.172% of all transactions.

The data features are numerical and have been anonymized through PCA transformation to protect confidentiality; thus, the original features and detailed background information are not available. Principal components V1 through V28 are derived from PCA, whereas 'Time' and 'Amount' remain unaltered. The 'Time' feature denotes the seconds elapsed from the first transaction, and 'Amount' indicates the transaction's value, useful for cost-sensitive learning models. The target variable 'Class' identifies a transaction as fraudulent (1) or genuine (0).





