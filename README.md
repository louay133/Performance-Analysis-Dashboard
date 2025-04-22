# 📊 Power BI Performance Dashboard: End-to-End Data Analytics Project

## 🔧 Data Preparation & Modeling
- **Power Query Transformation**: Cleaned raw data (handled missing values, standardized formats, optimized datatypes)
- **Time Intelligence**: Created a virtual `dim_date` table to enable dynamic period comparisons (YTD, PYTD)
- **Data Model**: Established relationships and optimized schema for measure calculations

## 📈 DAX Measures & Core Logic
- **Base Metrics**: 
  - `Sales`, `Quantity`, `COGs`, `Gross Profit`, `GP%` (margin calculation)
- **Time Comparisons**:
  - `YTD_Sales`, `YTD_Quantity`, `YTD_GrossProfit` (year-to-date aggregations)
  - `PYTD_*` equivalents for prior-year benchmarking
  - **SWITCH Measures**: `S_YTD`, `S_PYTD`, and `YTD vs PYTD` to toggle between time periods dynamically
- **Dynamic Titles**: Auto-updating chart/report titles (e.g., Scatter title, Waterfall title) based on filters

## 📊 Advanced Visualizations
- **Treemap**: Hierarchical breakdown of performance by category
- **Waterfall Chart**: Visualized incremental profit drivers
- **Combo Chart**: Overlaid metrics (e.g., Sales vs. GP%) with dual-axis formatting
- **Scatter Plot + Zoom Slider**: Analyzed correlations with interactive zoom

## 🎨 UX & Final Touches
- **Conditional Formatting**: Highlighted outliers/trends (e.g., red/green for GP%)
- **Dynamic Labels**: Axis titles, tooltips, and report titles that adapt to filters
- **Layout Optimization**: Aligned visuals, consistent color schemes, and mobile-responsive design

## 🛠️ Tools Used
- Power BI (Data modeling, DAX, visuals)
- Power Query (Data cleaning)

## Why It Matters
This dashboard transforms raw data into actionable insights, enabling stakeholders to:
✔ Track sales/profitability trends in real-time  
✔ Compare YTD vs. PYTD performance at a glance  
✔ Drill into granular metrics with interactive visuals  

## Project Files
- `Performance_Dashboard.pbix` - Main Power BI file
- Plant_DTS.xls - Contains sample data files
- Dashboard_Screenshot - Additional technical notes
