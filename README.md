# 🏢 Riyadh Real Estate Data Analysis and Visualization Project 🏠



## 💡 Introdruon
- The Riyadh real estate market is active and changing quickly. This project aims to offer useful insights on market trends, home prices, and other significant variables that affect Riyadh's real estate market. We want to identify significant patterns and connections in the data using Python's data analysis tools and Plotly's interactive visualization features.

## 🧹 Data Cleansing & Preprocessing 
1. **Drop Unnamed Column:**
   - Remove the unnamed column from the DataFrame.

2. **Data Cleansing & EDA:**
   - Print basic information about the DataFrame such as columns, shape, and data types.
   - Check for missing values in the dataset.

3. **Drop Nulls:**
   - Remove rows with missing values from the DataFrame.

4. **Rename Columns:**
   - Rename specific columns in the DataFrame for better clarity.

5. **Unique Value Exploration:**
   - Examine unique values in various columns like 'Area,' 'apartments,' 'front,' 'rooms,' 'bathrooms,' etc.

6. **Handling Yes/No Columns:**
   - Identify columns with values [0, 1] that represent Yes/No attributes.
   - Convert these columns to 'Yes' and 'No' for better understanding.

7. **Drop Irrelevant Columns:**
   - Drop the 'tent' column from the DataFrame.

8. **Handling Duplex Houses with Zero Apartments:**
   - Identify and address cases where 'duplex' is 'No' and 'apartments' is 0.

9. **Drop Duplicated Rows:**
   - Drop duplicated rows from the DataFrame.

10. **Modify Apartments Value for Duplex:**
    - Update the 'apartments' value for rows where 'duplex' is 'Yes' and 'apartments' is 0.

11. **Handling Zero Property Age:**
    - Remove the 'propertyAge' column from the DataFrame since most rows have a value of 0.

12. **Change Data Types:**
    - Convert 'rooms,' 'apartments,' 'bathrooms,' and 'lounges' to numeric data types after handling special cases ('30+' and '7+') and removing decimals.

13. **Change Data Type of Bathrooms:**
    - Convert 'bathrooms' to numeric data type.

14. **Change Data Type of Lounges:**
    - Convert 'lounges' to numeric data type.

## 📊 Data Visualization and Insights 📈


