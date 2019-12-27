## Anomaly detection (Fraud) on Credit card transactions

Work in progress....

In this project we will work on anomaly detection on credit card transactions using the dataset available on Kaggle. These anomlaies or outliers in the transactions are potential Fraud, and such problems differs from ordinary supervised learning since the volume of such outliers in the dataset would be very few. Traditional supervised learning model often fail to pick outliers and hence such problems needs to be dealt differently.

Due to significantly low number of fraud transactions you may have in the dataset, you would not use a metric like accuracy to measure the performance of different models, instead would rely on F1-score which is a metric that balances the precision and recall scores. We will use different techniques to solve the problem.

1   Statistical method  
1.1 Using t-test and Gaussian distribution

2   Machine Learning method   
2.1 Using supervised learning (Random Forest) 
2.2 Unsupervised Learning (Isolation Forest)

3   Deep Learning method  
3.1 Using Autoencoder reconstruction error


Note: Read the notebooks in the numerical order
