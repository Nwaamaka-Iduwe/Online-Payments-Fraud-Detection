# Online-Payments-Fraud-Detection
The aim of this project is to find the best ML algorithm to help Blossom Bank detect fraud on its online payment platform. To achieve this aim, the first thing done was to clean the data to ensure it is easy to understand. This involved changing column names and changing the 0’s and 1’s in the target column to ‘No Fraud’ and ‘Fraud’ respectively. This was followed by a series of Exploratory Data Analysis with the aim of understanding the data components better. After this, the ‘type’ column with ‘object’ data type was one-hot encoded to numerical data as most ML models only work with numeric data. 

Next, a train and test variable was set up along with a list of models and a function. I used a for loop to train and test each model in the list using the function created. I also created a confusion matrix function so that a confusion matrix would return with the accuracy, precision and recall scores. 

Random Forest Classifier turned out to be the best model with a 99.97% accuracy score, a 97% precision score and a 78% recall score. However, I decided to cross validate this result using k-fold to ensure these results and the results showed that truly, Random Forest was the best model.

In this project, the libraries used were NumPy and Pandas for data analysis, Matplotlib and Seaborn for data visualization and most importantly, Sklearn for statistical modelling.

