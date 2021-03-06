# Predicitve-Maintenance

Dataset taken from

http://aws-proserve-data-science.s3.amazonaws.com/predictive_maintenance.csv

PROJECT: Maintenance cost reduction through predictive techniques

BACKGROUND A company has a fleet of devices transmitting daily telemetry readings. They would like to create a predictive maintenance solution to proactively identify when maintenance should be performed. This approach promises cost savings over routine or time-based preventive maintenance, because tasks are performed only when warranted.

GOAL To build a predictive model using machine learning to predict the probability of a device failure. When building this model, be sure to minimize false positives and false negatives. The column you are trying to predict is called failure with binary value 0 for non-failure and 1 for failure.

Result: 
Confusion Matrix from XGBoost model

![image](https://user-images.githubusercontent.com/66092829/114091906-1de05e00-986e-11eb-9879-b2babe44a82a.png)

