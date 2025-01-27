# 🏢 Riyadh Real Estate Data Analysis and Visualization Project 🏠



## 💡 Introdruon
- The Riyadh real estate market is active and changing quickly. This project aims to offer useful insights on market trends, home prices, and other significant variables that affect Riyadh's real estate market. We want to identify significant patterns and connections in the data using Python's data analysis tools and Plotly's interactive visualization features.


## ℹ Dataset Overview and Source
- URL link : https://www.kaggle.com/datasets/reemamuhammed/riyadh-villas-aqar
- About : This dataset contains over 50k villas located in Riyadh, Saudi Arabia. Each villa contains information such as the location, neighborhood, number of bedrooms, number of bathrooms, the space of the villa, and many more!
  
| Column Name   | Definition                                                                               |
|---------------|------------------------------------------------------------------------------------------|
| front         | The direction of the property's front that faces the street.                            |
| rooms         | Total number of bedrooms or living spaces in the property.                               |
| lounges       | Number of  lounges within the property.                                                   |
| bathrooms     | Total number of bathrooms in the property.                                               |
| streetWidth   | Width of the street where the property is located.                                      |
| stairs        | Presence and type of staircases in the property.                                         |
| driverRoom    | Whether the property has a separate room for drivers.                                   |
| SunLightRoom  | Presence of a room with ample sunlight in the property.                                 |
| kitchen       | Total number of kitchens in the property.                                                |
| outdoorRoom   | Outdoor or open-air living spaces attached to the property.                              |
| garage        | Availability of a garage for parking vehicles.                                           |
| duplex        | Whether the property is designed as a two-unit duplex.                                   |
| Area          | Total area or size of the property in square units.                                      |
| apartments    | Number of individual apartments or units in the property.                                |
| StaffRoom     | Whether there's a dedicated room for staff or workers.                                   |
| elevator      | Presence of an elevator in the property.                                                 |
| furnished     | Whether the property comes fully furnished.                                              |
| pool          | Whether there's a swimming pool on the property.                                         |
| basement      | Availability of a basement or cellar space.                                              |
| neighbourhood | Description of the surrounding area where the property is.                               |
| location      | More specific details about the property's address.                                     |
| price         | Listed price or cost to buy or rent the property.                                        |
| square_price  | Price per square unit of the property, useful for comparison.                             |




## 🧹 Data Cleaning & Preprocessing 
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
x   
13. **Change Data Type of Bathrooms:**
    - Convert 'bathrooms' to numeric data type.

14. **Change Data Type of Lounges:**
    - Convert 'lounges' to numeric data type.

## 📊 Data Visualization and Insights 📈
|    | Real Estate Insights |
| ----------- | ----------- |
| 1 | Real estate prices are high in northern Riyadh and low in the center. |
| 2 | Most houses have an area typically ranging between 2000 square meters and within the range of 20,000 square meters. |
| 3 | There is an unusual pattern across various areas of Riyadh where the price per square meter is high for properties with smaller areas (indicating the presence of other factors contributing to the higher price per square meter beyond just the area and location). |
| 4 | There is a real estate property with 7 rooms, the price of which is equal to or cheaper than properties with 4 or 5 rooms. |
| 5 | This 7-room property has almost the same qualities as other four/five rooms properties of a similar price. |
| 6 | Only real estate in the northern part of Riyadh has prices higher than 30 million. |
| 7 | The price tends to increase with more area. |
| 8 | The highest price recorded was 100 million, while the lowest price was 50 thousand. |
| 9 | The best-chosen region for buying a house based on the map on the dashboard is the center of Riyadh. have The highest area available at a cheap price. | 
| 10| The south region of Riyadh has the lowest area of houses. |


### Team Responsibilities 
| Name   | Tasks   | 
|--------|---------|
| Mailak alqathami | Dashboard |
| Sadeem Fihrah | Data Visualization |
| Abdulmohsen Albareed | Data Cleaning & EDA, Map box | 

