# NLP_Bank_Complaint_Classification
leverage NLP/LLM to classify customer complaints from a financial institution

Data Source:
https://www.kaggle.com/datasets/venkatasubramanian/automatic-ticket-classification

Business Problem:
These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base. The goal for this model is to automate its customer support tickets system.

**DS Problem**:
You need to build a model that is able to classify customer complaints based on the products/services

Suggested topic clusters:
1. Credit card / Prepaid card
2. Bank account services
3. Theft/Dispute reporting
4. Mortgages/loans
5. Others
This is a multi classification problem. 


**Model Experiments**
1. Multinomial Naive Bayes
The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts.

2. XGBoost (2.0 Version)
To implement XGBoost for text classification, the first step is to preprocess the text data and extract meaningful features from it, such as term frequency-inverse document frequency (TF-IDF) values. These features are then used as input to the XGBoost model, which is trained on the preprocessed data.
![image](https://github.com/ShawnLiu119/NLP_Bank_Complaint_Classification/assets/43327902/db5fb90f-53d3-404c-b8bb-571aaf15a67a)


4. LLM - ALBERT fintuning
![image](https://github.com/ShawnLiu119/NLP_Bank_Complaint_Classification/assets/43327902/f8f243d0-461e-4006-a560-20ffb0ad85a3)
