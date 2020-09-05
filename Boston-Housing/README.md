# Boston-Housing
Predicting the median value of owner-occupied homes

### Objective:

The objective of the dataset is to predict the median value of owner-occupied homes in 1000 USD's

Dataset Link : https://www.kaggle.com/c/boston-dataset/data

### Evaluation Criteria
Submissions are evaluated using RMSE Value

### Task 1: Load the Data and Import Libraries
* Load the dataset using pandas.
* Import essential modules and helper functions from NumPy and Matplotlib.
* Explore the dataframe using the head().

### Task 2: Inspect the Data
* Explore the dataframe using the shape, info() functions.
* Check the null values
* Get Statistical Overview using describe()

### Task 2:  Visualize the Data(EDA)
* For this dataset, I used a histogram, correlation matrix, jointplot(), pairplot()  using Seaborn & Matplotlib to visualize the data
* Used boxplot()/jointplot() to check outliers in data

### Task 3: Splitting Training Dataset into Test and Train set 
### Task 4: Train the model using RandomForest 
             * Check accuracy and RMSE Value on Test and Train set
             * Visualise Result by ploting the graph of Predicted Values of Train and Test Set            
### Task 5: Used Hperparameter tunning in Random Forest:
              * Tried to reduce RMSE 
              * Tried to increase Test set Accuracy.
### Task 6: Train the model using Gradient Boost 
             * Check accuracy and RMSE Value on Test and Train set
             * Visualise Result by ploting the graph of Predicted Values of Train and Test Set
### Task 7: Used Hperparameter tunning in Gradient Boost:
              * Tried to reduce RMSE 
              * Tried to increase Test set Accuracy.              
### Task 8: Train the model using XG Boost 
             * Check accuracy and RMSE Value on Test and Train set
             * Visualise Result by ploting the graph of Predicted Values of Train and Test Set             
### Task 9: Used Hperparameter tunning in XG Boost:
              * Tried to reduce RMSE 
              * Tried to increase Test set Accuracy.              
### Task 10: Prediction on TEST DATA and Check RMSE of each model
### Conclusion : XG Boost is giving least RMSE on Test data, ie It is more accurate in predicting Median value of Owner-Occupied homes.
