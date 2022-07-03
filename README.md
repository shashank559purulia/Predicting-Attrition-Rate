# Predicting-Attrition-Rate
This repository deals with preicting whether a driver will leave or not using Data Science methods.
Insights:
1)Monthly Income for the drivers who are still working is higher than the monthly Income for the drivers who have left.Median monthly income for the drivers who have left is 51000 while the median monthly income for the drivers who are still working is 61000.
2)Almost same proportion of drivers have left at very Education level.Therefore it seems that Education level has no impact on the driver's attrition rate.
3)There are 60% male drivers and 40% female drivers.The attrition rate for both males and females is very high(around 65%).
4)Since it is an imbalanced dataset with 66% positives and 34% negatives,I have chosen AUC_ROC as the best performance metric.The area under roc curve is highest for the Random Forest Classifier(0.78).
5)The most significant features which will determine whether a driver will leave or not are Quaterly Rating,last 3 months average  business value,last 3 months average Income while the least 3 contributing features are last 3 months average grade,education level and gender.
