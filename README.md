# ML-Lab-Ex01
---
# AIM
To perform the initial investigations and analysis on the given dataset &amp; summarize the
characteristics of the given dataset using python implementation.

---
# DESCRIPTION
Exploratory Data Analysis refers to the critical process of performing initial
investigations on data so as to discover patterns to spot anomalies to test hypothesis and
to check assumptions with the help of summary statistics and graphical representations.
Python libraries use in machine learning:
 Numpy
 Scipy
 Scikit-learn
 Pandas
 Matplotlib
 Theano
 TensorFlow
 Keras
 PyTorch

---
# EXPLORATORY DATA ANALYSIS (EDA)
EDA refers to the process of performing initial investigations on data so as to discover
patterns, to spot anomalies, to test hypothesis and to check assumptions with the help of
summary statistics and graphical representations.
Prior to develop any Machine Learning (ML) model, it is a good practice to understand the
data first and try to gather as many insights from it.
1) Outlier analysis – process of identifying extreme values, or abnormal observations
 Mean value is less than median value 
 Large difference between 75th %tile and max values of predictors
 Z-score is &amp;gt;3
 IQR - minimum and maximum point Q1–1.5*IQR and Q3+1.5*IQR respectively
 Box plot
2) Correlation analysis - measure the strength of the linear relationship between two
variables and compute their association
 It’s a good practice to remove correlated variables during feature selection(which less
contributes with the target variable), to improve the model

 If correlation is zero, there is no linear relationship between these two variables, so it is
safe to drop these features
 Pearson correlation coefficient or Spearman correlation coefficient
3) Univariate, Bivariate and Multivariate analysis
 Univariate - analyzing only one variable.
 Bivariate - comparing two variables to study their relationships.
 Multivariate - comparing more than two variables and study their relationships
Univariate analysis:
Describe patterns found in univariate data include central tendency (mean, mode and median)
and dispersion: range, variance, maximum, minimum, quartiles (including the interquartile
range), and standard deviation.
Categorical data:
 Bar plot - rectangular bars with heights proportional to the values that they represent
 Pie plot - circular statistical graphic, which is divided into slices to illustrate numerical
proportion
Continuous data:
 Scatter plot - distribution of the observations
 Swarm plot - view the spread of values in a continuous variable
 Histogram plot - group the data into bins
 Violin plot - distribution of quantitative data across several levels (different category)
Bivariate Analysis of Continuous Variables:
 Scatter plot, Correlation - Heat map
Bivariate Analysis of Continuous Variables and Categorical Variables:
 Categorical plot – bar, box
Bivariate Analysis of Categorical Variables:
 Count plot - show the counts of observations in each categorical bin using bars
Multivariate Analysis
 Pair plot - to see how two continuous features behave for different classes
---
# QUESTIONS
1. Read the data
2. Display the first and last 5 rows
3. Display the number of rows and columns
4. Display the number of categorical and numerical columns

5. For numerical columns, display the min, max and mode
6. Display the columns with null values
7. Calculate the 5 number summary and correlate with box plot (Python code)
8. Display the outlier values using Z-score (Python code)
9. Display the features with high positive correlation, high negative correlation and no
correlation (Python code)
10. Analyze the skewness of the features using plot distribution graph and display the
features with right skew, left skew and no skew (Python code)
11. Perform univariate analysis for categorical variables using bar plot
12. Perform univariate analysis for continuous variables using swarm plot and violin plot
13. Display the scatter plat to show the relationship between two continuous variables
14. Perform a bivariate analysis between continuous variable and categorical variable
using categorical plot
15. Display the counts of observations for categorical variable using count plot
16. Perform a multivariate analysis between features using pair plot
