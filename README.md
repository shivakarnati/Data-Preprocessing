# Data-Preprocessing
In this project, we can find some important aspects of data preprocessing and the techniques to make data clean for Regression/Classification tasks.

Requirements:
pandas, Jupyter Notebook, R and R studio (in R)

Dataset:
Here we processed a simple dataset which contains three independent variables (Country,Age,Salary), and one dependent variable (Purchased).

For prediction of a Purchased, we use these three independent variables. But before doing any machine learning task, the data preprocessing is essential.
The following are the steps, which we follow for Data-preprocessing.

1. Reading the data
In Python, we can read an excel file by using pandas. And In R, we can directly use ```read.csv``` command to read an excel file.

2. Handling the missing data
We have several methods to handle the missing data, but  here we used ```mean``` (Average) of the particular column to fill up the missing values.

3. Encoding the categorical data (One-hot Encoding)
For Countries, we will transform categorical data into numerical representation (not numeral values) 

4. Splitting the Dataset
Generally, We follow 80-20 ratio to split the dataset. Here 80% will be the Training set, 20% will be the Test test.

5. Feature scaling
Feature scaling is a method used to normalize the range of independent variables or features of data. 
In data processing, it is also known as data normalization and is generally performed during the data preprocessing step.

When you have the normalised data, you can use "Normalization" method for feature scaling, or else you can use "Standardization" method for feature scaling.
![plot](./home/shivakrishnakarnati/Pictures/normalization.jpg)
