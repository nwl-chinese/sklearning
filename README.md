Machine Learning and Transportation

Project 1:Diabetes Prediction Based on Machine Learning

1.Background

   One in seven Adults in the United States now has diabetes, according to the Centers for Disease Control and Prevention. But by 2050, that share will have risen rapidly to as much as a third. We have a diabetes data set in the UCL Machine learning database, and we hope to use this data set to understand how machine learning can help us predict diabetes.Data from  https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/diabetes.csv

2.Process

 (1)Data readng
     First,we should import some packages,Including pandas,numpy and matplotlib.pyplot. we used pd.read_csv() to read datasets, and we used print(data.columns) and data.shape to confirm data information,and we used data.head() to check whether the data was read correctly.  We supposed X as the feature columns and y as the target variable, and we set the test_size to be 0.2 that meant 80% of the data were used to train and 20% of the data were used to test.

 (2)Method makes
    We used five models of supervised learning to predict the data, including KNN, LOGISTIC regression, Decision tree ，Random forest and GradientBoostingClassifier. These five models are used to train data and forecast data, and the accuracy of each model is calculated. In addition, after adjusting the cords, we find in the KNN model test rate is also improved in order to solve the fitting problem in the model, in the decision tree and random forest model we also by limiting the depth of the tree made training set and testing set accuracy as the tree depth change line chart, found that can be solved by limiting the depth of the tree can be fitting problem and improve the accuracy of the test set.When printing the importance of features in the decision tree, blood sugar was found to be the most important feature affecting diabetes。
    
3.Result
   
   By comparing the test set accuracy of various models in the default state, it is found that the random forest has a high accuracy rate.
 

4.Thinking

   For a novice programmer, it takes a lot of time to understand these models. After understanding the processing process of these models, they start to look for datasets. After finding and handling the outliers in the datasheet from the Internet, some of the data sets were handed over to me. After consulting with my teammates, we selected five models to predict, established the models and compiled the code Machine forest has the highest accuracy. After careful study at that time, it was found that the accuracy rate of some model training sets reached 1. Thinking of the problem of over fitting that the teacher said in class, we adjusted the parameters and found the best parameters. We originally wanted to compare the accuracy of the five models after parameter adjustment, but we abandoned it if we could not find a unified standard. This machine learning modeling, a lot of problems, harvest is also a lot of understanding the basic knowledge of machine learning, but also let me have a strong interest in machine learning.
