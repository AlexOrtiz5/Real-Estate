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
  - Data Collection & Initial Assessment: The project began by sourcing a "messy" real estate dataset from Kaggle. The initial inspection revealed several inconsistencies, including non-numeric characters within numerical columns and missing values, which confirmed the need for a thorough data cleaning process.
  - Data Cleaning & Preprocessing: This was a critical phase. Key steps included filtering to remove duplicate rows and imputation to handle missing values by filling them with the mean. A major insight here was the necessity of type casting—converting columns like 'Price' and 'Area' from object types (due to commas or special characters) to a numeric format to enable mathematical operations.
  - Exploratory Data Analysis (EDA): Through various visualizations, we gained valuable insights. The scatter plot of 'Area' vs. 'Price' revealed a strong positive linear relationship, confirming that larger properties generally cost more. Bar charts also highlighted a clear insight: the presence of amenities like an 'Elevator' or 'Parking' significantly increases the average property price.
  - Predictive Modeling: The modeling phase demonstrated the power of advanced algorithms. We started with a Linear Regression model as a baseline. The core insight was the substantial performance improvement when using a Random Forest Regressor, which better captured the complex relationships in the data. Furthermore, the model's feature importance scores revealed that 'Area' and 'Room' were the most influential factors in predicting a property's price.
  - Deeper Analysis: This phase provided rich, strategic insights. The geospatial analysis allowed for the visual identification of high-value regions on a map. The clustering analysis was a key insight, as it automatically segmented the market into distinct groups (e.g., luxury properties vs. standard homes), which could be used for targeted marketing or strategic investment decisions.

# Conclusion
  In this project, we successfully navigated a comprehensive data science workflow, transforming a messy and inconsistent real estate dataset into a valuable source of insights and predictions. By meticulously cleaning the data, we established a reliable foundation for analysis. The subsequent exploratory analysis revealed key market drivers, such as the strong correlation between property area and price, and the significant impact of amenities like parking and elevators. We then built a powerful predictive model using a Random Forest Regressor, which not only achieved a high level of accuracy in estimating property prices but also provided crucial insights into which features were most influential. Finally, our deeper analysis, including geospatial mapping and market segmentation through clustering, provided a holistic understanding of the real estate market. Ultimately, this project demonstrates how a structured data science approach can unlock strategic value from raw data, enabling more informed decision-making for real estate valuation and market analysis.
  
# Contact
  linkedin, github, medium, etc 