# SparkML_Linear-Regression_Consulting_Project

- Business Statement:
--------------------------------

client is selling ships to some new customers and want you to create model and use it to predict how many crew members the ships will need.

Therefore, client want accurate estimates of how many crew members a ship will require. 

The client also mentioned that they have found particular cruise lines will differ in acceptable crew counts, so it is most likely an important feature to include in analysis.

- Data Preprocessing procedure
----------------------------------

The "cruise line" feature values are string. So, apply "StringIndexer" technique to "cruise line" column to convert strings to numbers with python and spark. see the documentation page (spark.apache.org)


Solution:
------------------
Model has achieved fairly good results of R2 and RMSE values in predicting crew members. Also, there is a high correlation between crew and passsenger features suggests that more passengers would require more crew members.

Also, there is a high correlation between crew and cabin features suggests that more cabins would require more crew members.
