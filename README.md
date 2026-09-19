# data-cleaning-and-feature-engineering
A data preprocessing and feature engineering project using Python, Pandas, NumPy, and Scikit-learn, covering missing-value handling, outlier detection, data-type correction, categorical encoding, feature creation, and numerical standardization.

Objective: The objective of this project is to transform a raw dataset into a clean, structured, and analysis-ready dataset by applying data cleaning, handling missing values and outliers, correcting data types, and creating meaningful new features. 

 

Problem Statement: Raw datasets often contain missing values, inconsistent data types, and extreme observations that can affect analysis and machine-learning performance. This project addresses these issues in the Ames Housing dataset through data cleaning, categorical encoding, numerical standardization, and feature engineering to produce a reliable, analysis-ready dataset. 

 

Technologies Used: Python, Pandas, NumPy, Scikit-learn, and Google Colab. 

 

Dataset Description: The Ames Housing dataset contains information about residential properties in Ames, Iowa, including property size, location, construction details, facilities, and sale prices. 

Records: 2,930 

Original columns: 82 

Target variable: SalePrice 

Data types: Numerical and categorical 

The dataset contains missing values and extreme observations, making it suitable for demonstrating data preprocessing techniques. 
 

Preprocessing:  

Data exploration: Examined dataset dimensions, column types, missing values, and descriptive statistics. 

Missing-value handling: Applied appropriate replacements for missing numerical and categorical values. 

Duplicate detection: Checked for duplicate records. 

Outlier handling: Detected extreme values using the IQR method and applied logarithmic transformations. 

Data-type correction: Corrected an invalid construction year and converted selected columns to appropriate types. 

Feature engineering: Created six features representing property area, bathrooms, and facilities. 

Categorical encoding: Converted categorical variables into numerical columns using one-hot encoding. 

Standardization: Applied StandardScaler to selected numerical features. 

Final verification: Compared descriptive statistics and data quality before and after preprocessing. 

 

Conclusion: The preprocessing process successfully cleaned the dataset while preserving all 2,930 records. Missing values were reduced to zero, no exact duplicate records remained, and nine additional columns were created through transformation and feature engineering. The resulting dataset contains 91 columns and is prepared for further analysis. 
