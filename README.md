# 📊 Power BI Performance Dashboard: End-to-End Data Analytics Project

[![Dashboard Screenshot](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Dashboard%20Screenshot)](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Performance%20Report.pbix)

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

## 📂 Project Files
| File | Description | Link |
|------|-------------|------|
| `Performance Report.pbix` | Main Power BI dashboard | [Download](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Performance%20Report.pbix) |
| `Plant_DTS.xls` | Raw dataset | [Download](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Plant_DTS.xls) |
| `Dashboard Screenshot` | Dashboard preview | [View](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Dashboard%20Screenshot) |

## 🚀 How to Use
1. **Download** the [Power BI file](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Performance%20Report.pbix)
2. **Connect** to the [dataset](https://github.com/louay133/Performance-Analysis-Dashboard/blob/main/Plant_DTS.xls) if needed
3. **Refresh** data to see latest metrics
4. **Interact** with filters and slicers to explore insights

## Why It Matters
This dashboard transforms raw data into actionable insights, enabling stakeholders to:
✔ Track sales/profitability trends in real-time  
✔ Compare YTD vs. PYTD performance at a glance  
✔ Drill into granular metrics with interactive visuals  

---

> **Note**: Requires Power BI Desktop to view the interactive dashboard. [Download Power BI](https://powerbi.microsoft.com/en-us/desktop/)
