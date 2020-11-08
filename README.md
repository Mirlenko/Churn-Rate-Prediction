# Churn-Rate-Prediction

The project goal is to gain in-depth knowledge and practical skills of implementing ML classification problems.

The data for the project is provided by the French telecommunications company Orange. The problem requires client data, so the data was preliminarily obfuscated and anonymized: any personal information that allows identifying users was removed from the dataset, and the names and descriptions of variables intended for making forecasts were not provided. The dataset itself consists of 40 thousand objects and includes 230 variables, where the first 190 variables are numeric, and the remaining 40 variables are categorical.

Within the project framework, the churn prediction problem is solved. The task of predicting churn is one of the most important subtasks in the field of working with audiences and is relevant not only for telecommunications companies, but also for most organizations providing services in the B2B and B2C segments.

In the project, in order to find users prone to churn, predictive models are built - models that predict the likelihood that a user will leave the service. In the classical setting, probabilistic models of binary classification are built, where the target class is users leaving the service. The probability that the user belongs to the target class is the target value - the probability of churn. Accordingly, the greater this probability, the greater the chances that the user will refuse to use our service.

Within the project, the following aspects of Data Analysis and Machine Learning are covered:
* Explaratory Data Analysis
* Data Cleaning
* Feature Engineering
* ML Classification Algorithms Tuning (`XGBoost`)
