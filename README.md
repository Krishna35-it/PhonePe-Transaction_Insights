# PhonePe-Transaction_Insights
PhonePe transaction insights with Power BI Visualization

# 1.Project Overview
With the increasing reliance on digital payment systems like PhonePe, understanding the dynamics of transactions, user engagement, and insurance-related data is crucial for improving services and targeting users effectively. This project aims to analyze and visualize aggregated values of payment categories, create maps for total values at state and district levels, and identify top-performing states, districts, and pin codes to drive business strategies through data-driven insights.

# 2.Objectives
* Analyze transaction patterns across different states, districts, and pin codes.
* Visualize user engagement and device usage trends.
* Understand insurance penetration and growth potential.
* Create interactive dashboards for business insights.
* Enable data-driven decision making for strategic planning.

# 3.Technologies and Tools Used

| Category                   | Tools                            |
|----------------------------|----------------------------------|
| **Programming Language**   | Python 3.x                       |
| **Database**               | MySQL                            |
| **Data Processing**        | Pandas, NumPy                    |
| **Database Connectivity**  | PyMySQL                          |
| **Visualization**          | Power BI                         |
| **Data Source**            | PhonePe Pulse GitHub Repository  |

# 4.Database Schema
## The project creates 9 structured tables in MySQL database:
### 1. Aggregated Tables

`aggregated_transaction`: Aggregated transaction data by state, year, quarter, and transaction type.  
`aggregated_user`: User engagement data aggregated by state, brand, and time period.  
`aggregated_insurance`: Insurance transaction aggregates at state level.  

### 2. Map Tables

`map_transaction (map_map)`: District-level transaction data with geographical mapping.  
`map_user`: District-level user registration and app opens data.  
`map_insurance`: District-level insurance transaction data.  

### 3. Top Tables

`top_transaction (top_map)`: Top-performing districts and pin codes for transactions.  
`top_user`: Top districts and pin codes based on registered users.  
`top_insurance`: Top-performing areas for insurance transactions.  

# 5.Workflow
## STEP 1: Data Extraction
## Step 2: Data Transformation
    * Import Required Libraries
    * Extract and Transform JSON Data
    * Data Cleaning
## STEP 3: Database Connection & Table Creation
## STEP 4: Data Loading
## Step 5: Power BI Integration

# 6.Business Case Studies & Insights
## Case Study 1: Decoding Transaction Dynamics on PhonePe
### Visualizations:
* Bar Chart: Transaction Amount by State
* Line Chart: Transaction Amount by Year & Quarter (Transaction Type-wise)
* Card Visuals: Total Transaction Count (235.28bn) and Total Transaction Amount (₹345.52T)
* Slicers: Year, Quarter, and Transaction Type filters

### Key Insights:
* Telangana and Karnataka lead in transaction volumes
* Merchant payments dominate across all states
* Growth trend peaked in 2021 and 2022, with minor slowdowns visible in Q4 2023

## Case Study 2: Device Dominance and User Engagement Analysis
### Visualizations:
* Stacked Bar Chart: Users Count by Brand and State
* Pie Chart: Brand-wise Registered Users Count
* Matrix: State-wise Brand Counts
* Card Visuals: Total Registered Users (38.06bn), Total App Opens (1.02T), Top Device Brand (Xiaomi)

### Key Insights:
* Xiaomi, Samsung, and Vivo lead in user registrations
* Device engagement growth was high post-2020
* Certain brands dominate in Tier 2 and Tier 3 states

## Case Study 3: Insurance Penetration and Growth Potential Analysis
### Visualizations:
* Bar Chart: Insurance Amount by State
* Shape Map: Insurance Amount Distribution across States
* Line Chart: Insurance Count Trend over Years
* Card Visuals: Total Insurance Policies and Total Insurance Amount (₹345.52T, 235.28bn)
* Slicers: Year, Quarter, Insurance Type, and State filters

### Key Insights:
* Tamil Nadu and Karnataka show high insurance penetration
* Insurance growth was exponential from 2020 to 2023
* Low adoption states present high growth potential (e.g., Bihar, Assam)

## Case Study 4: User Engagement and Growth Strategy
### Visualizations:
* Bar Charts: Registered Users by State, App Opens by State
* Line Chart: App Opens Trend over Time
* Table: Detailed District Engagement
* Slicers: Year, Quarter, and State filters

### Key Insights:
* Maharashtra and Uttar Pradesh show high engagement
* Some states have high registrations but comparatively lower app opens (targeted campaigns needed)
* Districts with high growth potential identified

## Case Study 5: Insurance Engagement Analysis
### Visualizations:
* Bar Chart: Insurance Count by State
* Table: Top PIN Codes for Insurance Transactions
* Line Chart: Yearly Growth Trend on Insurance Count
* Slicers: Year, Quarter, and State filters

### Key Insights:
* Kerala and Tamil Nadu show high insurance transaction density
* Top PIN codes clustered in metros (Chennai, Bangalore)
* Insurance adoption opportunity exists in North-East and rural India

# 7. Power BI Dashboard Features
## Interactive Elements:

**Dynamic Filters** : Year, Quarter, State, Transaction Type.  
**Cross-Filtering** : Click on any visual to filter other visuals.  
**Drill-Through** : Navigate from state to district to pin code level.  
**Tooltips** : Hover over visuals for detailed information.  

## Key Visualizations:

* Geographical Maps (Shape Maps) for India.  
* Time Series Analysis (Line Charts).  
* Comparative Analysis (Bar Charts).  
* Distribution Analysis (Pie Charts).  
* Detailed Tables with conditional formatting.  
* KPI Cards for quick insights.  

# 8.Best Practices Implemented:

* Cleaned and standardized State/District names
* Used Measures for clean KPI names instead of raw sums
* Applied appropriate data types (Pincodes as Text)
* Used slicers for dynamic filtering
* Professional color themes for different categories
* Optimized Shape Map for India using TopoJSON

# 9.Skills Demonstrated

**Data Extraction** : Cloning and extracting data from GitHub repositories.  
**ETL Pipeline** : Extract, Transform, Load processes.  
**SQL Proficiency** : Database design, table creation, data insertion.  
**Data Transformation** : JSON parsing, data cleaning, standardization.  
**Data Visualization** : Power BI dashboard creation.  
**Analytical Thinking** : Business case study analysis.  
**Documentation** : Comprehensive project documentation.  
**Problem Solving** : Handling complex nested data structures.  

# References & Resources

PhonePe Pulse Data: [PhonePe Pulse GitHub](https://github.com/PhonePe/pulse)
Official PhonePe Pulse Website: [https://www.phonepe.com/pulse/]
Power BI Documentation: [Microsoft Power BI Docs](https://docs.microsoft.com/power-bi/)
MySQL Documentation: [MySQL Official Docs](https://dev.mysql.com/doc/)

# Author

Krishna Raj S

GitHub: @Krishna35-it
Project Repository: [PhonePe-Transaction_Insights](https://github.com/Krishna35-it/PhonePe-Transaction_Insights)

# License
This project is created for educational and analytical purposes. Data source: PhonePe Pulse (publicly available).
