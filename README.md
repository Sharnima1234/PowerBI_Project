# 📊 Power BI Adventure Works Report Dashboard

A comprehensive, end-to-end Power BI dashboard project built using 7+ CSV files to simulate a full retail business intelligence scenario. This project covers data cleaning, modeling, DAX calculations, interactivity, and advanced reporting features — all structured for real-world Data Analysis use cases.

---

## 📁 1. Data Loading & Preparation (Power Query Editor)

- Loaded 7–8 CSV files into Power Query Editor
- Verified and corrected data types: `Text`, `Whole Number`, `Decimal`, `Date`, `Currency`
- Enabled Data Quality & Profiling tools:
  - **Column Quality** (Error %, Empty, Valid)
  - **Column Distribution** (Distinct count)
  - **Column Profile** (Min, Max, Average, etc.)
- Checked for nulls, errors, duplicates, data inconsistencies
- Applied basic formatting and column cleanup
- Used `Change Type with Locale` for accurate date format handling

---

## 🧠 2. Data Modeling

- Identified **Fact** and **Lookup** tables
- Built a **Star Schema** using manual relationships
- Created **Primary Key ↔ Foreign Key** relationships (Unidirectional filtering only)
- Categorized columns like `Country`, `Continent` for geographic visuals
- Created **Hierarchies**:
  - **Date Hierarchy**: Year → Quarter → Month
  - **Territory Hierarchy**: Region → Country → City
- Created **Calculated Columns**:
  - `Start of Month`, `Start of Year`
  - Custom flags and segment fields

---

## 🔣 3. DAX Measures & Calculated Columns

- Built **30+ custom DAX measures**, including:
  - `Total Revenue`, `Total Orders`, `Total Profit`, `Total Returns`
  - `Return Rate`, `Revenue per Customer`, `Average Basket Size`
- Used core DAX functions:
  - `CALCULATE`, `FILTER`, `RELATED`, `DIVIDE`, `SUMX`, `IF`
  - Time intelligence: `DATEADD`, `SAMEPERIODLASTYEAR`, `STARTOFMONTH`
  - Logic handling: `HASONEVALUE`, `SELECTEDVALUE`, `ISFILTERED`
- Created additional **Calculated Columns** for dynamic segments and flags

---

## 📊 4. Visualizations

- Used a diverse set of visuals:
  - **Tables**, **Matrix**
  - **Bar Charts**, **Line Charts**
  - **Cards**, **KPIs**
  - **Gauge Charts**, **Donut Charts**
  - **Map Visuals** for global-level insights
- Enabled **Drill-up / Drill-down** for hierarchical visuals
- Applied multiple **Slicers**: Product, Customer, Time-based, etc.

---

## 🧩 5. User Experience & Interactivity

- Customized **Visual Interactions** using “Edit Interactions”
- Implemented **Cross-filtering & Highlighting**
- Configured:
  - **Drill-through Pages**
  - **Custom Tooltips**
  - Page-level, visual-level, and report-level filters
  - Interactive **Date Hierarchies**

---

## 🚀 6. Advanced Features

- **Field Parameters**: Enabled toggling between multiple dimensions/metrics dynamically
- **Numeric Parameters**: Used to control thresholds for KPIs and input metrics
- **KPI Cards**: Configured with trend axis, forecast, and conditional formatting
- Enabled:
  - **Trend Axis** for comparing month-over-month performance
  - Forecast with shaded confidence intervals
- Used the **Selection Pane** to:
  - Layer shapes and visuals
  - Group objects (KPI backgrounds, labels, etc.)
- Created:
  - **Bookmarks** for navigation, resets, and filters
  - **Custom Buttons** with different states (Default, Hover, Pressed)
  - Page navigation using action buttons
- Controlled **Visual Layering** with Selection Pane & Format tools

---

## 🎨 7. Design & Performance Optimization

- Maintained clean, modular layout with grouped elements
- Applied consistent **Color Theme** and formatting across all pages
- Ensured high performance by:
  - Avoiding visual clutter
  - Using optimized DAX
  - Limiting unnecessary visuals or calculations
  - Turning off unused interactions

---

## ✅ Outcome

- A complete, **production-grade Power BI dashboard** with strong emphasis on DAX, storytelling, usability, and visual design.
- Demonstrates advanced Power BI capabilities suitable for real-world data analysis and decision support use cases.

---


