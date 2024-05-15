# Credit_Card_Approval
Overview : The aim of this project is to develop a predictive model that can accurately classify credit card applications as either approved or denied based on various features. 

About Dataset : The dataset contains information such as applicant's age, income, employment status, and other relevant factors.

Steps Performed :
1. During analysis we have dropped the null value column "Job title".
2. We checked the correlation between al the columns and dropped those columns whih are not correlated and highly correlatd.
3. Then we have data imbalancing in target column so we performed SMOTE technique to balance the data.
4. Split the data into training and testing then scaled it.
5. Now the final we have developed 3 models :
   >> Logistic regression accuracy : 0.70 ||
   >> RandomForest Classifier accuracy : 0.77 || 
   >> KNN Classifier accuracy : 0.90
6. In the end we conclued, based on the model performance, it is evident that the KNN classifier outperforms both the logistic regression and random forest models in terms of accuracy. With an accuracy of 0.90, the KNN classifier demonstrates the highest predictive power among the three models. This indicates that the KNN classifier is better suited for the given task compared to logistic regression and random forest. 
