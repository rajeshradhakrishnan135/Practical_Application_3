## Practical Application 3: Comparing Classifiers
By Rajesh Radhakrishnan
Date: 01/22/2025

# URL of Jupyter Notebook that contains the Analysis
https://github.com/rajeshradhakrishnan135/Practical_Application_3/blob/main/Comparing_Classifiers.ipynb

# Business Objective
To classify the bank customers contacted in the marketing campaigns by their subscription to a term deposit and using the 
attributes collected about the customers, in order to better directly target the customers in future campaigns.

# Findings
The analysis of marketing campaigns data for a Portugese bank was conducted to determine the best classification model 
for predicting whether the client will subscribe to a term deposit. The bank information variables such as age, job, 
marital, education, default, housing, loan, contact, month, day_of_week, campaign, pdays, previous, poutcome were used to 
build the classification models.

The dataset (total records = 41188) is an imbalanced one because the number of records with the y variable (has the client 
subscribed a term deposit?) having a value 'yes' is 36548 whereas having a value 'no' is 4640 (implies 88.73% of the data 
belongs to the 'yes' class)

The analysis reveals that the Support Vector Machines (SVM) model performs the best in terms of Accuracy Score. 
The Logistic Regression model came in second with KNearestNeighbors (KNN) in third, and Decision Trees in final place. 
In terms of the time taken for fitting the data, the KNN model took the least time whereas the SVM model took the most time
(SVM is computationally expensive).

# Recommendations and Next Steps
It is recommended that the Support Vector Machines model be applied to classify new customers and determine those who should be contacted 
in the marketing campaigns since they are more likely to subscribe to a term deposit. The next steps are to gather more client related 
features in order to better tune the model and hence to get a higher accuracy score and F1-score.