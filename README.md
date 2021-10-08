# Second-hand-car-prize-prediction
We are making prediction of second hand cars prize for a car showroom.  They are providing their past few years of data in which some information  about cars like mileage, miles  driven, transmission,etc are given.  We are applying some machine learning algorithm on that information to  predict the second hand prize of the cars.




1.for that we need some modules like 
1. pandas 
2. numpy
3. matplotlib
4. seaborn
5. sklearn

2. After importing modules upload dataset(csv file).
3. now you have split the data in x and y column.(features and target)
4. Then e need to analyse our dataset for missing values, outliers and make it clean so we can perform our work on that otherwise there will be the possibility of occurring errors or wrong prediction.
5. To fill the messing values you can drop this row or replace that empty cell with mean or mode of that column.
6. Now your data is ready for work.
7. Now you have to find some relation between feature and target to get important feature for prediction and drop some non related column so that our model will become less expensive.
8. you have do some visualization to understand the relation between feature.
9. Feature in our dataset has different scale we need to make down in same scale. For that we use module name sklearn.
10. we need to separate the categorical and continuous columns.
11. If the data is in continuous manner then we should do standardization. and if the features in categorical manner then we use one hot encoding.
12. now join that data again as x.
13. Now you can split tour data in training and testing. 
14. we need to set random_state so that your data will have same values and model will not change the result each run.
15. then this the time where you need to apply machine learning algorithms. as you know we are predicting prize means we have continuous values to predict so we use regression algorithms.
16. we applied linear regression, decision tree regression and random forest regressor.
17. we tuned that algorithms by managing some feature values and try to reduce error.
18. As a result we found that linear regression algorithm gives us best results.
