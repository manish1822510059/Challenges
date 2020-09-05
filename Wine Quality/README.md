# Wine Quality
Predicting the qaulity of Red Wine.

### Objective:
The objective of the dataset is to predict qaulity of Red  Wine.

Dataset Link : https://archive.ics.uci.edu/ml/datasets/wine+quality

### Evaluation Criteria
Submissions are evaluated using Accuracy Score

### Task 1: Load the Data and Import Libraries
* Load the dataset using pandas.
* Import essential modules and helper functions from NumPy and Matplotlib.
* Explore the dataframe using the head().

### Task 2: Inspect the Data
* Explore the dataframe using the shape, info() functions.
* Check the null values
* Get Statistical Overview using describe()

### Task 2:  Visualize the Data(EDA)
* For this dataset, I used a histogram, correlation matrix, jointplot(), pairplot(), countplot(), boxplot()  using Seaborn & Matplotlib to visualize the data
* Pandas functions used to analyse data

### Task 3: Splitting Training Dataset into Test and Train set 
### Task 4: Train the model using Decision Tree 
         - Check accuracy score on Test and Train set
         - Visualise Result by ploting the graph of Predicted Values of Train and Test Set 
         - Display Confusion Matrix and Classification Report
### Task 5: Train the model using RandomForest 
         - Check accuracy score on Test and Train set
         - Visualise Result by ploting the graph of Predicted Values of Train and Test Set 
         - Display Confusion Matrix and Classification Report
### Task 6: Used Randomized Search-CV and Hperparameter tunning in Random Forest:
           * Tried to increase Test set Accuracy.
           * Display Confusion Matrix and Classification Report
### Task 7: Train the model using Gradient Boost 
             * Check accuracy score on Test and Train set
             * Visualise Result by ploting the graph of Predicted Values of Train and Test Set
             * Display Confusion Matrix and Classification Report
### Task 8: Used Hperparameter tunning in Gradient Boost:
              * Tried to increase Test set Accuracy.
              *  Display Confusion Matrix and Classification Report
### Task 9: Train the model using XG Boost 
             * Check accuracy score on Test and Train set
             * Visualise Result by ploting the graph of Predicted Values of Train and Test Set
             *  Display Confusion Matrix and Classification Report
### Task 10: Used Hperparameter tunning in XG Boost:
              * Tried to increase Test set Accuracy. 
              *  Display Confusion Matrix and Classification Report
### Task 11: Prediction on TEST DATA and Check accuracy score of each model
### Conclusion : Random Forset is giving best Accuracy on Test data, ie It is more accurate in predicting Red Wine Quality.
