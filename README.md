# EDA_December
Exploratory Data Analysis with Pandas, NumPy, Seaborn, and Matplotlib

 * # 1. Import Libraries :
 - import pandas as pd: Pandas is a powerful library for data manipulation and analysis.
 - import numpy as np: NumPy is used for numerical operations in Python.
 - import seaborn as sns: Imports the Seaborn library for statistical data visualization.
 - import matplotlib as mpl: Imports the Matplotlib library for creating static, animated, and interactive visualizations in Python.
 - import matplotlib.pyplot as plt: Imports the Pyplot module from Matplotlib, providing a convenient interface to create various plots.

 * # 2. Ignore Warnings:
 - warnings.filterwarnings('ignore'): Suppresses warning messages to improve the cleanliness of the output.

 * # 3. Read Data:
 -  df = pd.read_csv("/content/mtcars.csv"): Reads a CSV file named "mtcars.csv" located at "/content/" into a Pandas DataFrame named 'df'.

 * # 4. Explore Data:
 - df.head()
 - df.tail()
 - df.dtypes
 - df.describe().T
 - df.info()
 - df.describe()
 - df.count()
 - df.isnull().sum()
