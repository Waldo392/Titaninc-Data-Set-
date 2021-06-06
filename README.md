# Titaninc-Data-Set-
This is my analysis on the working with the TItanic data, applying variuos models and find one fit to predict accurately , based on certain parameters, if a person would survive the disaster

I started with the **Raw Data** from **Kaggle** to get started with and used certain ways to clean the _Continuous_ and _categorical_ data, remove redundant parameters and club the "Parch" and "SibSp" to make a "Family" column usning pandas and numpy.
After the annotations, the data was divided into _train, test and Validation_ sets so as to work efficiently on the models.

The following model were used 
  1.Loagistic Regression
  2.Support Vector Machine 
  3.Multilayer Perceptron
  4.Random forest
  5.Graded Boosting
 The models were trained using the **k-fold cross validation** and best results provideing hyperparameters were found out and pickled out.
 
 THe pickled out hyperparameters settingss were used to validate and test the models to find out the best suited model for the purpose 

**Random forest** was found out to be the most suited for the dataset 
 ![image](https://user-images.githubusercontent.com/69895829/120924816-27ae0280-c6f3-11eb-9a12-91f52c078308.png)
