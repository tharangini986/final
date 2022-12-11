The ability to precisely classify observations is extremely valuable for predicting the house price and whether a particular user will be eligible for loan or not.
We have used two models to predict the house price details and the mortgage details. 
They are  Lasso Regression – used for house price prediction.
          Random Forest Classifier – used for mortgage approval prediction.  

We can conclude that using lasso regression, we can  predict the dependent variable ‘Sales price’ which is a continuous variable.
Whereas random forest classifier will make decision trees even though it takes more space, it will provide better results.
By using these models, we can reduce the time complexity and we can further improve this in future by adding new data to the model and make more complicated predictions.

House pricing depends on multiple factors like the Home size and usable space, condition of the house, location whether it is urban, semi urban or rural and the facilities it is going to provide like kitchen, number of bedrooms and garden. 
Also factors like whether it is near the road, does the house has pool, Utilities will influence the sales price of the house.
We use Lasso Regression model to predict the prices of houses.
Here the data is unrefined, so we need to clean the data which is also called as data preprocessing.
For this we need to deal with the missing values or null values then we need to deal with the string values like “Sale Condition” where there is normal or abnormal from which we can assign normal value as 1 and abnormal value as 0.

Several factors include Gender, Education Qualification, Self Employed, Dependents and whether the person is  married or not will effect the mortgage status.
Also, the income of applicant, Loan amount, area of the property and credit history of the person are necessary to know if a certain person can get a loan or not.
In this method, we use Random forest model to predict if mortgage application is approved or not.
We import necessary packages and load the data set which contains data on gender employment dependents and credit history in this model. 
We can use seaborn and matplot lib to show the data in a meaningful way in the form of graphs.
We can deal with the missing values and assign dummy values as the string values so that we can make them into single data type.


