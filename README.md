# DATA-CLEANING-PROJECT
Data cleaning and preprocessing of the Hotel Bookings dataset using Python, Pandas, NumPy, and Seaborn. Includes missing value handling, outlier detection, encoding, and data validation.

cleaning and preprocessing a real-world hotel bookings dataset using Python and the Pandas library. 
The goal is to transform raw, inconsistent data into a clean, structured, and analysis-ready dataset for future data analysis and machine learning tasks.


##  Objectives

- Load and explore a real-world dataset.
- Identify and handle missing values.
- Remove duplicate records.
- Standardize column names and data types.
- Detect and handle outliers using the IQR method.
- Encode categorical variables.
- Validate the cleaned dataset.
- Export the cleaned dataset for further analysis.


##  Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn


##  Data Cleaning Process

The following preprocessing steps were performed:

- Loaded and explored the raw dataset.
- Checked dataset structure using `.info()`, `.head()`, and `.describe()`.
- Identified missing values using summary statistics and a heatmap.
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.
- Removed duplicate rows.
- Renamed columns using snake_case formatting.
- Corrected data types where necessary.
- Detected and treated outliers using the Interquartile Range (IQR) method.
- Encoded categorical variables using One-Hot Encoding.
- Validated the cleaned dataset.
- Exported the cleaned dataset as a new CSV file.



##  Conclusion

The raw hotel bookings dataset was successfully transformed into a clean and consistent dataset suitable for exploratory data analysis and machine learning applications. Proper preprocessing improves data quality and helps ensure more reliable insights and predictive model performance.
