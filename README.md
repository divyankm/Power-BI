#Machine Learning in Power BI using PyCaret

Clustering — Group data points with similar characteristics.
Anomaly Detection — Identify rare observations / outliers in the data.
Classification — Predict categorical class labels that are binary (1 or 0).
Regression — Predict continuous value such as Sales, Price etc

“PyCaret is democratizing machine learning and the use of advanced analytics by providing free, open source, and low-code machine learning solution for business analysts, domain experts, citizen data scientists, and experienced data scientists”.

#Example 1 — Clustering in Power BI - K-Means Clustering is perfomed in Jewellry dataset https://raw.githubusercontent.com/pycaret/pycaret/master/datasets/jewellery.csv and covid_symptoms_data.csv dataset.

![image](https://user-images.githubusercontent.com/80899863/121524830-54288e00-ca15-11eb-9430-087091ba92fa.png)
![image](https://user-images.githubusercontent.com/80899863/121524899-65719a80-ca15-11eb-9a30-e121675b7750.png)

There are 9 ready-to-use clustering algorithms available in PyCaret which can be implemented using Power BI.

All the preprocessing tasks necessary to train a clustering model such as missing value imputation (if table has any missing or null values), or normalization, or one-hot-encoding, they all are automatically performed before training a clustering model.

![image](https://user-images.githubusercontent.com/80899863/121524990-80dca580-ca15-11eb-97a5-4aaac542529f.png)

#Example 2 — Anomaly Detection in Power BI
Anomaly Detection is a machine learning technique used for identifying rare items, events, or observations by checking for rows in the table that differ significantly from the majority of the rows. Typically, the anomalous items will translate to some kind of problem such as bank fraud, a structural defect, medical problem or error. Some common business use cases for anomaly detection are:
✔ Fraud detection (credit cards, insurance, etc.) using financial data.
✔ Intrusion detection (system security, malware) or monitoring for network traffic surges and drops.
✔ Identifying multivariate outliers in the dataset.

Dataset used for Anamoly Detection are https://raw.githubusercontent.com/pycaret/pycaret/master/datasets/anomaly.csv and winequalityN.csv.

![image](https://user-images.githubusercontent.com/80899863/121525433-fb0d2a00-ca15-11eb-88d8-1b79627f5d8e.png)

There are over 10 ready-to-use anomaly detection algorithms in PyCaret:
All the preprocessing tasks necessary to train an anomaly detection model such as missing value imputation (if table has any missing or null values), or normalization, or one-hot-encoding, they all are automatically performed before training an anomaly detection model.

![image](https://user-images.githubusercontent.com/80899863/121525518-111aea80-ca16-11eb-9257-0d41fb4055de.png)

# Example 3-Classification in Power BI

Classification is a supervised machine learning technique used to predict the categorical class labels (also known as binary variables). Some common business use case of classification are:
✔ Predicting customer loan / credit card default.
✔ Predicting customer churn (whether the customer will stay or leave)
✔ Predicting patient outcome (whether patient has disease or not)

Results of classification model is shown in below image.Random Forect ML Classification model in implemented on Customer_Behaviour.csv file.
(1 means yes, 0 means no),whether particular person purchased car or not.

![image](https://user-images.githubusercontent.com/80899863/121526557-1dec0e00-ca17-11eb-8f2d-19430b18f0cb.png)

There are 18 ready-to-use classification algorithms available in PyCaret:
![image](https://user-images.githubusercontent.com/80899863/121527019-96eb6580-ca17-11eb-9d50-188e34264a38.png)

#Example 4— Regression in Power BI-

Regression is a supervised machine learning technique used to predict the a continuous outcome in the best possible way given the past data and its corresponding past outcomes. Unlike Classification which is used for predicting a binary outcome such as Yes or No (1 or 0), Regression is used for predicting continuous values such as Sales, Price, quantity etc.

In this Example,Real_estate.csv dataset is used to predict the prices of houses using "Gradient Booster Regreessor" Technique.

![image](https://user-images.githubusercontent.com/80899863/121527253-d4e88980-ca17-11eb-8a90-82325eb49607.png)

Results of Regression Algorithm.Algo able to predict nearabout correct price of house.

![image](https://user-images.githubusercontent.com/80899863/121527611-36a8f380-ca18-11eb-8b92-2cc4997707db.png)

Link for Reference-(Documentation) -https://pycaret.org/guide/
https://github.com/pycaret/pycaret
https://towardsdatascience.com/machine-learning-in-power-bi-using-pycaret-34307f09394a

