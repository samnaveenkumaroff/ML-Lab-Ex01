# ML-Lab-Ex01

```markdown
Welcome to the ML-Lab-Ex01 repository! This repository contains the code and resources for various machine learning exercises, focusing on data preprocessing and exploratory data analysis.

## Ex. No: 1a EXPLORATORY DATA ANALYSIS

### AIM
To perform the initial investigations and analysis on the given dataset & summarize the characteristics of the given dataset using Python implementation.

### DESCRIPTION
Exploratory Data Analysis (EDA) refers to the critical process of performing initial investigations on data to discover patterns, spot anomalies, test hypotheses, and check assumptions with the help of summary statistics and graphical representations.

Python libraries used in machine learning:
- Numpy
- Scipy
- Scikit-learn
- Pandas
- Matplotlib
- Theano
- TensorFlow
- Keras
- PyTorch

### EXPLORATORY DATA ANALYSIS (EDA)
EDA involves initial investigations on data to discover patterns, spot anomalies, test hypotheses, and check assumptions with the help of summary statistics and graphical representations.

#### 1. Outlier Analysis
- **Mean value is less than median value** 
- **Large difference between 75th percentile and max values of predictors**
- **Z-score > 3**
- **IQR** - minimum and maximum point Q1–1.5*IQR and Q3+1.5*IQR respectively
- **Box plot**

#### 2. Correlation Analysis
- **Remove correlated variables** during feature selection to improve the model.
- **Zero correlation** indicates no linear relationship between variables, making it safe to drop these features.
- **Pearson correlation coefficient** or **Spearman correlation coefficient**

#### 3. Univariate, Bivariate, and Multivariate Analysis
- **Univariate** - analyzing only one variable.
- **Bivariate** - comparing two variables to study their relationships.
- **Multivariate** - comparing more than two variables to study their relationships.

### QUESTIONS
1. Read the data
2. Display the first and last 5 rows
3. Display the number of rows and columns
4. Display the number of categorical and numerical columns
5. For numerical columns, display the min, max, and mode
6. Display the columns with null values
7. Calculate the 5 number summary and correlate with box plot (Python code)
8. Display the outlier values using Z-score (Python code)
9. Display the features with high positive correlation, high negative correlation, and no correlation (Python code)
10. Analyze the skewness of the features using plot distribution graph and display the features with right skew, left skew, and no skew (Python code)
11. Perform univariate analysis for categorical variables using bar plot
12. Perform univariate analysis for continuous variables using swarm plot and violin plot
13. Display the scatter plot to show the relationship between two continuous variables
14. Perform a bivariate analysis between continuous variable and categorical variable using categorical plot
15. Display the counts of observations for categorical variable using count plot
16. Perform a multivariate analysis between features using pair plot

## Contents

- [ML_Lab_01.ipynb](ML_Lab_01.ipynb): Jupyter notebook for the exercises.
- [ML_Lab_01.py](ML_Lab_01.py): Python script for the exercises.
- [insurance.csv](insurance.csv): Dataset used for the exercises.

## Usage

Clone the repository and run the Jupyter notebook or Python script to perform the machine learning exercises. Make sure to have the required dataset (insurance.csv) in the same directory or update the path accordingly.

### Example

```python
# Load the dataset
import pandas as pd
df = pd.read_csv('insurance.csv')

# Perform Min-Max Normalization
from sklearn.preprocessing import MinMaxScaler
def min_max_normalization(df, column_name):
    scaler = MinMaxScaler()
    df[[column_name]] = scaler.fit_transform(df[[column_name]])
    return df

df = min_max_normalization(df, 'bmi')
print(df['bmi'])
```

## Crafted with Love by Sam Naveenkumar .V

Thank you for visiting the ML-Lab-Ex01 repository. If you have any questions or suggestions, please feel free to raise an issue or contribute to the project.
```
