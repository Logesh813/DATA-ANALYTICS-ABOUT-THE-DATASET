# DATA-ANALYTICS-ABOUT-THE-DATASET
# AIM
To perform data analytics on a given dataset using Python and Pandas, understand the characteristics of the dataset, identify different types of data, examine missing values, and prepare the dataset for further analysis and machine learning.
# THEORY
Data Analytics is the process of examining, cleaning, transforming, and interpreting data to discover useful information and patterns.

Python provides several libraries for data analysis. Among them, Pandas is widely used for handling structured datasets such as CSV and Excel files.

Important Pandas Functions
head() – Displays the first few records of the dataset.
tail() – Displays the last few records.
shape – Gives the number of rows and columns.
info() – Displays information about columns, data types, and non-null values.
describe() – Provides statistical information such as mean, standard deviation, minimum, and maximum.
isnull().sum() – Identifies the number of missing values in each column.
dtypes – Shows the data type of each column.
nunique() – Finds the number of unique values in each column.
dropna() – Removes rows or columns containing missing values.
fillna() – Replaces missing values with suitable values.
Types of Data

The dataset may contain different types of data:

Numerical data – Age, marks, salary, temperature, etc.
Categorical data – Gender, city, department, product type, etc.
Boolean data – True/False or Yes/No.
Date/Time data – Date, time, year, etc.
Basic Data Analytics Process

Import Dataset → Explore Data → Identify Data Types → Check Missing Values → Clean Data → Statistical Analysis → Prepare Dataset

Sample Python Code
import pandas as pd

# Load dataset
data = pd.read_csv("dataset.csv")

# Display first five records
print(data.head())

# Display dataset size
print(data.shape)

# Display information
print(data.info())

# Display statistical summary
print(data.describe())

# Display data types
print(data.dtypes)

# Check missing values
print(data.isnull().sum())

# Find unique values
print(data.nunique())

# RESULT
Thus, data analytics was performed successfully using Python and Pandas. The dataset was explored by examining its size, structure, data types, statistical characteristics, unique values, and missing values. The dataset was thereby prepared for further data analysis and machine-learning applications.
