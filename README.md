![Screenshot 2024-12-08 101325](https://github.com/user-attachments/assets/7fe4a0c1-8db5-49a0-80d3-0a499af191c0)
![Screenshot 2024-12-08 101547](https://github.com/user-attachments/assets/1d3582c7-3f21-4d56-b92a-2417365dd9b3)
![Screenshot 2024-12-08 101426](https://github.com/user-attachments/assets/ea23ed9a-197b-440e-b7a1-f48997adc7d7)
![Screenshot 2024-12-08 101406](https://github.com/user-attachments/assets/ccc0b9c0-cbcc-492e-9e05-1c4ac3b6994b)
![Screenshot 2024-12-08 101355](https://github.com/user-attachments/assets/75927a15-04e4-4de6-ae81-775a572711da)
![Screenshot 2024-12-08 101347](https://github.com/user-attachments/assets/bba78dc4-c8f2-4722-8fa8-21f14edfab41)

# CODTECH-task1

Name : VIDYARANI PATIL
Company : CODTECH IT SOLUTIONS
ID : CT12DS2950
Domain : DataScience
Duration : November 25th, 2024 to January 25th, 2025

Overview of the Project

Project: Exploratory Data Analysis (EDA)
Objective
  Exploratory Data Analysis (EDA) aims to summarize, visualize, and better understand the dataset before applying statistical modeling or machine learning algorithms. By performing EDA, analysts ensure that they deeply understand the dataset, which helps in choosing the right algorithms, improving model performance, and drawing meaningful insights.  

Key Activities
  1) Loading and Preparing the Data
        Load the Iris dataset using sklearn.datasets.load_iris.
        Convert the data into a pandas DataFrame and map numerical target labels to species names.
     
  2) Dataset Overview
        Display the first few rows of the dataset using .head().
        Use .info() to examine data types, memory usage, and dataset structure.
        Generate summary statistics of numerical features using .describe().
     
  3) Missing Value Check
      Check for missing or null values in the dataset using .isnull().sum().
     
  4) Visualizing Feature Distributions
      Plot histograms to visualize the distribution of each feature.
      Use pair plots to examine pairwise relationships between features, color-coded by species.
     
  5) Correlation Analysis
      Calculate the correlation matrix for numerical features using .corr().
      Visualize correlations using a heatmap with annotated values.
     
  6) Outlier Detection
      Use box plots to detect outliers for each feature, segmented by species.


Technologies used
  1)  Programming Language
      Python: The script is written in Python, a versatile language widely used in data analysis and machine learning.
      
  2)  Data Manipulation and Analysis

     Pandas: Used to load, structure, and manipulate the dataset. Functions like .head(), .info(), .describe(), and .isnull() are utilized for exploration.
     Numpy: Utilized for numerical operations and efficient handling of arrays.

  3)  Data Visualization

      Matplotlib: Used for creating static, interactive, and visually appealing plots like histograms.
      Seaborn: A statistical data visualization library built on top of Matplotlib, used for pair plots, heatmaps, and box plots.
      
  5)  Dataset Source
      Scikit-learn: Provides the Iris dataset via sklearn.datasets.load_iris.
