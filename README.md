# MusicStore_SSAS_OLAP_Reports

## 📁 Project Overview
This project is built as part of a university assignment to demonstrate Business Intelligence capabilities using SQL Server Analysis Services (SSAS), Microsoft Excel (OLAP), and Power BI. The solution uses a data warehouse created for a digital music store.

## 🔍 Objectives
- Create an SSAS Cube with necessary dimensions and measures.
- Perform OLAP operations in Excel (Roll-up, Drill-down, Slice, Dice, Pivot).
- Build and publish interactive Power BI reports.

## 🏗️ Components

### ✅ Data Warehouse (Source)
- Based on Music Store sales data.
- Contains one fact table: `FactSales`
- Includes dimensions: `DimCustomer`, `DimTrack`, `DimEmployee`, `DimDate`

### 🧠 SSAS Cube (SalesCube)
- Measures: `Quantity`, `UnitPrice`, `TotalAmount`, `txn_process_time_hours`
- Dimensions: `Customer`, `Employee`, `Track`, `Date`
- Hierarchies: `Date Hierarchy (Year → Quarter → Month → Day)`

### 📊 OLAP Demonstration (Excel)
- Connected to Cube
- Demonstrated:
  - Roll-up
  - Drill-down
  - Slice
  - Dice
  - Pivot

### 📈 Power BI Reports
1. **Matrix Report** – Tabular report with row and column groupings
2. **Slicer Report** – Multiple filters with cascading slicers
3. **Drill-down Report** – Explore data hierarchically (Year → Month)
4. **Drill-through Report** – Navigate to a detailed view by right-clicking

## 💻 Tools Used
- SQL Server Data Tools (SSDT)
- SQL Server Analysis Services (SSAS)
- Microsoft Excel
- Power BI Desktop & Service


## ✍️ Author
- Nipuni Siriwardhana
- Semester 1, 2025 | Assignment 02

