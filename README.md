# Churn-Prediction-in-Telecom-Industry-using-ML

This project is a component of my internship at CodeClause in data science. It's a model that forecasts customer attrition in the telecom sector.
Churning occurs when a consumer cancels their subscription with you within a predetermined window of time.

The dataset was simple to use. The dataset contained no nulls or duplicates, but it did have 11 empty strings in the "Total Charges" column.
which I filled in with the mean of the column. Preprocessing and data visualization were done in order to view the values of each categorical 
column and determine the potential relationship between each categorical feature and churning. Box plots and further visualization were used 
to search for outliers, but none were discovered.
I transformed the categorical columns into numerical data using a label encoder, and then I used the vif test to determine multicollinearity. Four columns showed high collinearity. I attempted to address the problem with PCA, but it greatly decreased accuracy.


I used the chi-square test to choose features after learning about the association. To see the changes, I trained and tested using data that was imbalanced and balanced. To deal with variable imbalance, I used SMOTE. I used grid search with the unbalanced dataset to get the best results.
The change was evident in each set of data's categorization report, accuracy, and confusion matrix after training. I appreciate CodeClause giving me the opportunity to advance and showcase my expertise in this area.


