# Machine-Learning
### ML - Task1- Measures of Descriptive statistics-Central Tendency, spread
You are given house_price.csv which contains property prices in the city of Bangalore. You need to examine price per square feet do the following:<br>
Detect the outliers and remove it using:<br>
1. Mean Function
2. Percentile method
3. IQR(Inter quartile range method)
4. Normal distribution
5. Zscore method

Also, plot the box plot(for all the numerical columns), histplot(to check the normality of the column(price per sqft column))<br>
Check the correlation between all the numerical columns and plot heatmap.<br>
Scatter plot between the variables to check the correlation between them.

### ML - Task2 - Hypothesis testing

Q1.Suppose a child psychologist claims that the average time working mothers spend talking to their children is at least 11 minutes per day. You conduct a random sample of 1000 working mothers and find they spend an average of 11.5 minutes per day talking with their children. Assume prior research suggests the population standard deviation is 2.3 minutes.Conduct a test with a level of significance of alpha = 0.05.<br>

Q2. A coffee shop claims that their average wait time for customers is less than 5 minutes. To test this claim, a sample of 40 customers is taken, and their wait times are recorded. The sample mean wait time is found to be 4.6 minutes with a standard deviation of 0.8 minutes. Perform a hypothesis test at a significance level of 0.05 and determine whether there is enough evidence to support the coffee shop's claim.


### ML - Task3 - Data Preprocessing
Objective:<br>
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.<br>
Key Components to be fulfilled:<br>
Data Exploration:   Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns.<br>
Data Cleaning: <br>
Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers.<br>
Replace the value 0 in age as NaN<br>
Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode)<br>
Data Analysis:<br>
Filter the data with age >40 and salary<5000<br>
Plot the chart with age and salary<br>
Count the number of people from each place and represent it visually<br>
Data Encoding:<br>
Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.<br>
Feature Scaling: <br>
After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler.

### ML - Task4 - Regression
Problem Description<br>
A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:<br>
• Which variables are significant in predicting the price of a car<br>
• How well those variables describe the price of a car<br>
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.<br>
Business Goal<br>
You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to
understand the pricing dynamics of a new market.<br>
Dataset: CarPrice_Assignment.csv<br>
Dear students,<br>
Apply any 5 algorithms to the regression problem provided.<br>
For example:<br>
Linear Regression<br>
Decision Tree Regressor<br>
Random Forest Regressor<br>
Gradient Boosting Regressor<br>
Support Vector Regressor

### ML - Task5 - Classification and clustering
Problem Description<br>
Use sklearn.datasets iris flower dataset to train your model using logistic regression. You need to figure out the accuracy of your model and use that to predict different samples in your test dataset. In iris dataset there are 150 samples containing following features,<br>
Sepal Length<br>
Sepal Width<br>
Petal length<br>
Petal width<br>
Using above 4 features you will classify a flower  in one of the three categories,<br>
Setosa<br>
Versicolour<br>
Virginica<br>
Download the iris dataset directly from sklearn.dataset<br>
Use the same data for different clustering(exclude target variable) and classification algorithm
