# Working_on_Pandas_Library
The document is a comprehensive guide to using the Pandas library in Python for data exploration, cleaning, transformation, and exporting, demonstrated on a Titanic dataset.

The uploaded file is a Pandas Cheat Sheet in Jupyter Notebook format. It focuses on practical operations with the Pandas library in Python, applied to a Titanic dataset. T

1. **Basic Data Exploration**:
   - Display first/last rows: `df.head(10)`, `df.tail(10)`
   - View dataset shape and column names: `df.shape`, `list(df.columns)`
   - Statistical summary: `df.describe()`
   - Information about data types and memory usage: `df.info()`

2. **Data Selection**:
   - Select specific rows/columns by index or condition.
   - Examples for fetching specific data points.

3. **Data Cleaning**:
   - Handling missing data: `df.isnull()`, replacing NaN values, filling missing data.
   - Removing duplicates.
   - Changing data types and renaming columns.

4. **Data Transformation**:
   - String manipulation to clean and format column values.
   - Handling categorical data.
   - Resetting index and saving cleaned data: `df.to_csv('cleaned_data.csv', index=False)`

5. **Custom Examples**:
   - Custom operations like filtering rows, calculating percentages, and more.


### Actions You’ve Performed in the Document:
1. **Explored Dataset**:
   - Viewed first and last rows, shape, and summary statistics.
   - Retrieved specific data points and checked column data types.

2. **Cleaned Data**:
   - Managed missing values by filling or dropping them.
   - Removed duplicates.
   - Renamed and reformatted column names.

3. **Transformed Data**:
   - Changed column types (e.g., float to integer).
   - Cleaned and standardized string data.
   - Encoded categorical data.

4. **Saved Results**:
   - Exported the cleaned dataset to a CSV file for further use.
