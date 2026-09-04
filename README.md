# 🏠 India House Rent Analysis

An end-to-end **India House Rent Analysis** project using **Python and Microsoft Power BI** to clean, analyze, and visualize house rental data across major Indian cities.

## 📌 Project Workflow

**Dataset → Python Data Cleaning → Power BI Dashboard**

### 1️⃣ Get Dataset
The project starts with the **India House Rent Dataset**, containing information about:

- City
- Rent
- Size
- BHK
- Bathroom
- Tenant Preferred
- Furnishing Status
- Posted Date

### 2️⃣ Python Data Cleaning
Python and Pandas were used to clean and prepare the raw dataset.

The cleaning process included:

- Loading the dataset using Pandas
- Checking data types and missing values
- Removing duplicate records
- Cleaning column names
- Handling missing values
- Converting numerical columns into appropriate data types
- Standardizing categorical values
- Preparing the cleaned dataset for Power BI

**Libraries Used:**
- Python
- Pandas
- NumPy

### 3️⃣ Power BI Dashboard
The cleaned dataset was imported into **Microsoft Power BI** to create an interactive dashboard.

### 📊 Dashboard KPIs

- 💰 Total Rent
- 📐 Total Size
- 🏠 Total BHK
- 🚿 Total Bathrooms

### 📈 Dashboard Visualizations

- House distribution by City
- Rent by Tenant Preference
- Total Houses by City
- Size and Rent comparison by City
- Daily Size Trend
- Daily Rent Trend
- Monthly Property and Size Analysis
- Monthly Rent by City

### 🔎 Filters

Users can analyze the data based on tenant preferences:

- Bachelors
- Bachelors/Family
- Family

## 💡 Key Insights

This dashboard helps analyze:

- City-wise rental property distribution
- Rental price differences between cities
- Relationship between property size and rent
- Tenant preferences
- BHK and bathroom distribution
- Daily rental trends
- Monthly rental trends
- City-wise rental performance

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning |
| Pandas | Data Manipulation |
| NumPy | Data Processing |
| Power BI | Data Visualization |
| DAX | Calculations & Measures |
| GitHub | Project Documentation |

## 🔄 Project Pipeline

```text
Raw Dataset
     ↓
Python / Pandas
     ↓
Data Cleaning & Transformation
     ↓
Cleaned Dataset
     ↓
Power BI
     ↓
DAX Measures
     ↓
Interactive Dashboard
     ↓
Business Insights
