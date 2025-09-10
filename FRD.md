# Functional Requirements Document (FRD)

## 1. Functional Scope
The Sales Dashboard must:
- Show KPI Cards (Sales, Profit, Margin, Products Sold)
- Compare CY vs PY at product, city, and channel level
- Provide interactive filters (year, category, city)
- Include visualizations:
  - Line chart: Monthly Sales Trend
  - Bar chart: Top 5 Cities by Sales
  - Column chart: Profit vs Last Year by Channel
  - Customer-level sales table

## 2. Data Requirements
- **Inputs:** Revenue, Profit, Products, Cities, Channels, Customers  
- **Transformations:**  
  - Data cleaning  
  - DAX calculations for Sales, Profit Margin, YoY Growth  

## 3. Non-Functional Requirements
- Load time < 5 seconds  
- Intuitive design and drill-down navigation  
- Easy maintenance with new data  
- Access control for authorized users  

## 4. Assumptions & Dependencies
- Dataset is clean and static  
- Power BI environment available  
- Users trained in basic navigation  
