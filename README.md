# Credit-Card-Fraud-Detection

# Description ->
We are using the following Anomaly Detection Techniques namely: <br>

<b>Isolation Forest Anomaly Detection Algorithm</b><br>
<b>Density-Based Anomaly Detection (Local Outlier Factor)Algorithm</b><br>
<b>Support Vector Machine Anomaly Detection Algorithm</b><br>

# Observations ->
The data set is highly skewed, consisting of 492 frauds in a total of 284,807 observations. This resulted in only 0.172% fraud cases. This skewed set is justified by the low number of fraudulent transactions.<br>

The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28. Furthermore, there is no metadata about the original features provided, so pre-analysis or feature study could not be done.<br>

The ‘Time’ and ‘Amount’ features are not transformed data.<br>

There is no missing value in the dataset.<br>

# Dataset ->
The dataset that is used for credit card fraud detection is derived from the following Kaggle URL : <br>

https://www.kaggle.com/mlg-ulb/creditcardfraud

# Results ->

Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors vs. SVM detecting 8516 errors <br>
Isolation Forest has a <b>99.74%</b> more accurate than LOF of <b>99.65% </b>and SVM of <b>70.09%</b> <br>
When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%. <br>
So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%. <br>
