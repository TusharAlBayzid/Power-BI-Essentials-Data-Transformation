# Power BI Essentials: Setup, Data Transformation & Cleaning

This repository contains a foundational Power BI project focused on preparing raw data for analysis. The project demonstrates practical skills in data extraction, structural transformation, and data modeling using Power BI Desktop and Power Query Editor. 

This single `.pbix` file encapsulates the entire end-to-end data preparation workflow, serving as a practical reference for handling messy datasets.

## Core Topics Covered
*   **Data Extraction:** Importing multi-tabbed Excel/CSV datasets.
*   **Data Cleaning:** Removing duplicate records, handling null/missing values, and enforcing correct data types.
*   **Data Shaping:** Combining datasets through Append operations and normalizing data structures using Unpivot.
*   **Data Modeling:** Establishing logical relationships (Many-to-Many) between dimension and fact tables to create a cohesive data model.

## Step-by-Step Implementation

1.  **Initial Setup & Import:** Launched a blank Power BI report and connected to an external Excel dataset containing multiple sheets (North Branch and South Branch sales data).
2.  **Power Query Integration:** Loaded the raw data directly into Power Query Editor for initial inspection and structural review.
3.  **Data Cleansing:** 
    *   Identified and removed duplicate rows to ensure data integrity.
    *   Replaced missing values (`null` entries) to prevent calculation errors.
    *   Standardized column data types (e.g., setting ID columns to Whole Numbers, Date columns to Date formats).
4.  **Appending Tables:** Merged the two separate regional sales tables (North and South) vertically into a single, comprehensive dataset using the Append feature.
5.  **Unpivoting Data:** Transformed wide data formats into a long, flat format using the Unpivot feature, making the dataset suitable for time-series and categorical analysis.
6.  **Relational Modeling:** Configured the Data Model view by establishing a relationship between the tables using a common key (`CustomerID`), successfully handling cardinality requirements.
7.  **Finalization:** Applied all Power Query transformations directly to the Power BI data model and verified the accuracy in the Table View.

## Technologies Used
*   **Power BI Desktop** (Data Visualization & Modeling)
*   **Power Query Editor** (ETL - Extract, Transform, Load)

## How to View This Project
1. Clone or download this repository to your local machine.
2. Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
3. Open the `Power BI Essentials.pbix` file to explore the data model, applied steps in Power Query, and table structures.
