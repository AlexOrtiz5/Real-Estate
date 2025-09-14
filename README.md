# Real-Estate
  Project status(Active)

# Project objective
  This project aims to leverage data science to analyze and gain actionable insights from a messy real estate dataset. The core objective is to move from raw, inconsistent data to a comprehensive understanding of the factors that drive property prices. The analysis will follow a structured approach, starting with extensive data cleaning and preprocessing to handle missing values and inconsistencies. Once the data is refined, it will be used to perform exploratory data analysis (EDA) to uncover trends and patterns. The project's ultimate goal is to build and evaluate a predictive model that can accurately estimate property prices. The analysis will conclude with a deeper dive into advanced topics like geospatial analysis and market segmentation through clustering to provide a holistic view of the real estate market.

  The data for this project is sourced from the publicly available "A messy house price dataset" from Kaggle:
  https://www.kaggle.com/datasets/sinafadakhah/a-messy-house-price-dataset

# Methods
  - Data Cleaning & Preprocessing
    - Filtering: Dropping duplicate rows and handling missing values by removing rows with null coordinates during geospatial analysis.
    - Imputation: Filling missing numerical values (e.g., in Area, Price) with the mean to maintain data integrity.
    - Type Casting: Converting columns with string-based numbers into the correct numeric data types.
  - Exploratory Data Analysis (EDA)
    - Summary Statistics: Calculating descriptive statistics (.describe()) to get a quick overview of numerical features.
    - Visualization: Creating histograms to show data distribution, scatter plots to visualize relationships between variables, and bar charts to compare group means.
  - Predictive Modeling & Evaluation
    - Data Splitting: Separating the dataset into training and testing sets to evaluate model performance on unseen data.
    - Model Training: Training a Linear Regression model for a baseline and a more advanced Random Forest Regressor to improve predictive accuracy.
    - Model Evaluation: Using metrics like R-squared (R2), Mean Absolute Error (MAE), and Mean Squared Error (MSE) to assess model performance.
    - Feature Importance: Analyzing feature weights from the Random Forest model to determine which variables contribute most to price prediction.
  - Deeper Analysis
    - Geocoding: Converting street addresses into geographical coordinates (latitude and longitude) using geopy.
    - Geospatial Visualization: Creating an interactive map with folium to plot properties and visualize price distribution by location.
    - Clustering: Using the K-Means algorithm to segment the real estate market and identify distinct groups of properties.
    - Data Scaling: Standardizing features with StandardScaler to ensure that the clustering algorithm treats all variables equally.

# Technologies 
  List with used technologies:
  - Python: The core programming language used for all data manipulation, analysis, and modeling.
  - Pandas: A powerful library for data handling, cleaning, and preprocessing.
  - Scikit-learn: A machine learning library used for building and evaluating predictive models (Linear Regression, Random Forest) and for data scaling and splitting.
  - Matplotlib: A plotting library used to create static visualizations like histograms and scatter plots for exploratory data analysis.

# Project Description
  The dataset used in this project is the "A Messy House Price Dataset" from Kaggle. As its name suggests, the dataset is intentionally unstructured and contains several challenges common in real-world data, including missing values, inconsistent data types, and outliers. The dataset includes 3,480 rows and 8 key columns that describe various aspects of properties: Area, Room, Parking, Warehouse, Elevator, Address, Price, and Price(USD). The core of the project involves a comprehensive data science workflow, from cleaning and exploration to building predictive models. The project's goal is to predict property prices and derive meaningful insights into the factors that influence real estate values.

# Steps
  Add here any insights you had during the project

# Conclusion
  Final conclusion
  
# Contact
  linkedin, github, medium, etc 