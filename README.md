# Data-Analytics-with-Oasis-Infobyte-data-cleaning-
Data cleaning and preprocessing of the New York City Airbnb dataset, focusing on missing values, duplicates, data types, outliers, and validation.
### Data Cleaning Process for NYC Airbnb Dataset:

1. Handling Missing Values:
   - Identified columns with missing data.
   - Imputed missing values with mean/median for numerical data, and mode for categorical data. Alternatively, dropped rows/columns with excessive missing values.

2. Removing Duplicates:
   - Checked for and removed duplicate rows to ensure data uniqueness and avoid bias in analysis.

3. Correcting Data Types:
   - Converted columns to appropriate data types (e.g., converting dates to `datetime`, numerical columns to `float` or `int`) to facilitate proper analysis.

4. Handling Outliers:
   - Used statistical methods (e.g., IQR or Z-score) to identify and handle outliers, either by capping values or removing extreme data points.

5. Data Validation:
   - Verified data consistency, accuracy, and integrity to ensure the dataset was ready for further analysis or modeling. 

