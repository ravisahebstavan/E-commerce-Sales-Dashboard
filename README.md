# E-commerce Sales Performance Dashboard

### Author
Stavan Ravisaheb

---

### Project Overview
This project is a comprehensive analysis of a two-year dataset of online retail transactions. The primary goal was to create an interactive dashboard that provides key insights to support strategic business decisions in areas such as sales, product performance, and customer behavior.

### Technologies Used
* **Python:** Pandas for data cleaning and preprocessing.
* **SQL:** Data modeling to create a star schema for efficient analysis.
* **Power BI:** Data visualization and dashboard design.

### Project Steps
1.  **Data Preparation (Python):**
    I used a Jupyter Notebook to combine two years of data, remove rows with missing values or errors, and create a new column for total sales revenue. This process transformed the raw data into a clean, single file ready for modeling.

2.  **Data Modeling (SQL):**
    I structured the cleaned data into a star schema by creating three dimension tables (`DimCustomer`, `DimProduct`, `DimTime`) from the main fact table. This normalized the data and prepared it for efficient querying and reporting.

3.  **Data Visualization (Power BI):**
    I created a two-page interactive dashboard in Power BI.
    * **Page 1: Executive Overview** - Features key performance indicators (KPIs) and a bar chart of the top-selling products.
    * **Page 2: Detailed Analysis** - Contains a line chart to visualize sales trends over time and a map to show sales by country.

### Cleaned Data
The cleaned dataset (`online_retail_cleaned.csv`) is too large to be uploaded to GitHub. A screenshot of the first few rows is provided to show the final data structure, with the corrected `CustomerID` column and the new `Total_Price` column.

### Final Dashboard
The Final Power BI dashboard is included to showcase the completed report and key insights.
