# Project title: 
* Data Cleaning
  
# Project Overview:
* In this project, I conducted comprehensive data cleaning and preprocessing tasks on a dataset containing Airbnb details. The dataset included information such as name, hostname, availability, reviews, prices, and location data. The goal was to prepare the dataset for further analysis and modeling by addressing issues related to data quality, consistency, and completeness.

# Steps involved:
1. Importing important Libraries.
2. Loading Dataset.
3. Data exploration and Missing Data Handling: Dealing with missing values by either imputing them or making informed decisions on how to handle gaps in the dataset..
4. Checking and fixing data types, Looking for null and duplicates values.
5. Columns which contain missing text data like 'name' and 'hostname' was replaced with the mode of the name/hostname on the basis of their neighbourhood_group and neighbourhood.
6. Replacing the null values on 'reviews_per_month' with zero and using ffill on datetime column 'last_review' to fill the null values.
7. Standardization: Consistent formatting and units across the dataset for accurate analysis.
8. Outlier Detection: Identifying and addressing outliers that may skew analysis or model performance.
9. Using Boxplot and IQR method to indentify and remove or either replace the outliers with the lower and upper range.
