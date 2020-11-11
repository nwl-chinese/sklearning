Machine Learning and Transportation

Project 1:Diabetes Prediction Based on Machine Learning

1.Background
   
   One in seven Adults in the United States now has diabetes, according to the Centers for Disease Control and Prevention. But by 2050, that share will have risen rapidly to as much as a third. We have a diabetes data set in the UCL Machine learning database, and we hope to use this data set to understand how machine learning can help us predict diabetes.Data from  https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/diabetes.csv

2.Method
 
 (1)Data readng
     First,we should import some packages,Including pandas,numpy and matplotlib.pyplot. we used pd.read_csv() to read datasets, and we used print(data.columns) and data.shape to confirm data information,and we used data.head() to check whether the data was read correctly.  We supposed X as the feature columns and y as the target variable, and we set the test_size to be 0.2 that meant 80% of the data were used to train and 20% of the data were used to test.

 (2)Method makes
    We used four models of supervised learning to predict the data, including KNN, LOGISTIC regression, Decision tree and Random forest. These four models are used to train data and forecast data, and the accuracy of each model is calculated. In the decision tree model we get a better one by changing the depth of the tree.
