#   Homework 8 Campaign Response

Name : Nattakit Keawwilai        
ID : 6220422030
#### Dataset : Customer Survey from students BADS CRM Analytics 

#### Topic : Improvement Model accuracy rate and baseline model performance by machine learning techniques.

### Data Exploratory
Distirbuted total transaction amount
![Screenshot]()
Total amount and Total customer by time
![Screenshot]()

### Data Preparation
### create data set with RFM variables
![Screenshot](rfm)
### Created feature as below
1. transaction amount on Weekend/Weekday
2. transaction define Size of Amount (S,M,L)
3. date between previous purchased
4. monetary_value
5. Frequency

### Calculating response rate
![Screenshot](imbalance)

### Imbalance campaign response data with label


## Data Re-sampling
Under Sampling
Over Sampling
SMOTE
SMOTE-Tomek Links

## Model Improvement
#### 1.Logistic Regression
#### 2.XG-Boost

## Result
## Logistic Regression
| Resampling Method| Train max | Test max |
|------------------|-----------|----------|
|  Under Sampling  |   0.63    |   0.65   |
|
