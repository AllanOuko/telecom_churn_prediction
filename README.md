# telecom_churn_prediction

## Problem Statement

Imagine you're working with Sprint, one of the biggest telecom companies in the USA. They're really keen on figuring out how many customers might decide to leave them in the coming months. 
Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that.

We used the dataset from Kaggle [https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets] for the classification models.
We also settled on Random Forest and XGBoost classifiers to classifiy whether customers would leave or not.

**Data fields**
* State: string. 2-letter code of the US state of customer residence
* Account length: numerical. Number of months the customer has been with the current telco provider
* Area code: numerical 3 digit area code.
* International plan: (yes/no). The customer has international plan.
* Voice mail plan: (yes/no). The customer has voice mail plan.
* Number vmail messages: numerical. Number of voice-mail messages.
* Total day minutes: numerical. Total minutes of day calls.
* Total day calls: numerical. Total number of day calls.
* Total day charge: numerical. Total charge of day calls.
* Total eve minutes: numerical. Total minutes of evening calls.
* Total eve calls: numerical. Total number of evening calls.
* Total eve charge: numerical. Total charge of evening calls.
* Total night minutes: numerical. Total minutes of night calls.
* Total night calls: numerical. Total number of night calls.
* Total night charge: numerical. Total charge of night calls.
* Total intl minutes: numerical. Total minutes of international calls.
* Total intl calls: numerical. Total number of international calls.
* Total intl charge: numerical. Total charge of international calls
* Number customer service calls: numerical. Number of calls to customer service
* Churn: (True/False). Customer churn - target variable.
