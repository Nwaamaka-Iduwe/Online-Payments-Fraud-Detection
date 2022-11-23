# Online-Payments-Fraud-Detection
This project aims to use different machine learning algorithms to detect fraud on a banks online payment platform. To achieve this aim, the first thing done was to clean the data so that it is easier to understand. This involved changing column names and chaning the 0's and 1's in the target variable to 'No Fraud' and 'Fraud' respectively.
After this, exploratory data analysis was conducted to understand the data components better. This was followed by one-hot encoding columns with 'object' data type, 
to numerical data as most ML models only work with numeric data. Following this, a train and test variable was set up along with a list of models and a function. 
I used a for loop to apply to test each model in the list using the function created. I also implemented a confusion matrix that accompanied the accuracy, precision and recall score of the models after they were trained and tested.

Random Forest Classifier turned out to be the most accurate model with a 99.97% score.It also had the highest precision score at 97% and second highest recall score at 78% falling behind Decision Tree by 1%.
Following this, a cross-validation evaluation was conducted using K-Fold to test again, the accuracy of the models and see how accurate and precise they truly were. The results were exactly the same with Random Forest being the most accurate model at 99.97%.

In this project, the libraries used were NumPy and Pandas for data analysis, Matplotlib and Seaborn for data visualization, and most importantly, Sklearn for statistical modeling.

