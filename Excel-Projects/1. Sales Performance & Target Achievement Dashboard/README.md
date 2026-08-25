# Sales Performance & Target Achievement Dashboard

An interactive Excel dashboard designed to analyze sales executive
performance, target achievement, and performance gaps across multiple
regions.

## 📊 Project Overview

The **Sales Performance & Target Achievement Dashboard** provides a
visual and interactive way to monitor sales performance across different
regions and sales executives.

The dashboard focuses on answering key business questions such as:

-   Who are the top-performing sales executives?
-   Who are the bottom-performing sales executives?
-   How much of the sales target has been achieved?
-   Which executives are furthest away from their targets?
-   How does performance vary across regions?
-   How are individual executives contributing to overall sales?

The dashboard uses Excel-based data analysis, calculations, filters,
tables, and charts to convert raw daily sales data into actionable
performance insights.

------------------------------------------------------------------------

## 🎯 Project Objectives

The primary objectives of this project are to:

1.  Analyze sales performance at the individual executive level.
2.  Compare total sales against predefined targets.
3.  Identify the **Top 5** and **Bottom 5** sales executives.
4.  Calculate target achievement percentages.
5.  Identify executives who are furthest away from their targets.
6.  Provide region-wise filtering for interactive analysis.
7.  Present sales performance through an easy-to-understand dashboard.

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Microsoft Excel**
-   Excel Tables
-   Excel Formulas
-   Sorting & Filtering
-   Pivot-style analysis
-   Charts & Data Visualization
-   Dashboard Design

------------------------------------------------------------------------

## 📁 Dataset

The dataset contains sales records for **141 sales executives**
distributed across eight regions:

-   Chennai
-   Delhi
-   Mumbai
-   Nagpur
-   Patna
-   Pune
-   Ranchi
-   Surat

Each executive has sales recorded over five days.

### Dataset Columns

  Column               Description
  -------------------- ----------------------------------------
  Emp Code             Unique employee identification code
  Sales Executive      Name of the sales executive
  Region               Assigned sales region
  Day1 -- Day5         Daily sales figures
  Total Sales          Total sales generated over five days
  Target               Sales target assigned to the executive
  Target Hit %         Percentage of target achieved
  Away From Target %   Percentage of target still remaining

------------------------------------------------------------------------

## 📐 Key Calculations

### Total Sales

Total sales are calculated by adding sales from all five days:

``` text
Total Sales = Day1 + Day2 + Day3 + Day4 + Day5
```

### Target Hit %

Measures how much of the assigned target has been achieved:

``` text
Target Hit % = (Total Sales / Target) × 100
```

### Away From Target %

Measures the remaining percentage required to reach the target:

``` text
Away From Target % = 100% - Target Hit %
```

For this project, each sales executive has a target of **500**.

------------------------------------------------------------------------

## 📌 Dashboard Components

### 1. Regional Filter

The dashboard includes region selectors for:

> Chennai \| Delhi \| Mumbai \| Nagpur \| Patna \| Pune \| Ranchi \|
> Surat

This allows the user to analyze performance for a specific region.

### 2. Top 5 Sales Executives

Displays the five executives with the highest total sales within the
selected region.

This helps identify high-performing employees and understand the
characteristics of strong sales performance.

### 3. Bottom 5 Sales Executives

Displays the five executives with the lowest total sales within the
selected region.

This can help identify employees who may require additional support,
training, or performance analysis.

### 4. Target Hit % Analysis

Shows the target achievement percentage for selected executives.

This provides a more meaningful performance comparison than looking at
raw sales alone.

### 5. Away From Target % Analysis

Highlights how far each executive is from achieving the assigned target.

A lower percentage indicates that the executive is closer to the target.

### 6. Sales Comparison Chart

A horizontal bar chart compares total sales across the selected
executives.

This makes differences in sales performance easier to identify visually.

### 7. Target Achievement Distribution

A pie chart provides a visual representation of the contribution of
selected executives to the displayed sales performance.

### 8. Away From Target Trend

A line chart compares the percentage gap from target across the selected
bottom-performing executives.

------------------------------------------------------------------------

## 🔍 Example Insights

Using the dashboard data, several useful observations can be made.

-   **Jagdish Chandra** recorded the highest total sales in the dataset
    at **389**, achieving **77.8%** of the target.
-   **Rachita Anupam** recorded **385** total sales and achieved
    **77.0%** of the target.
-   **Miny Mole** recorded **384** total sales with a target achievement
    of **76.8%**.
-   **Anikuttan** achieved **76.4%** of the target with total sales of
    **382**.
-   **Praveen Kumar** and **Dinesh Kumar** were among the lowest
    performers at **166** total sales and **33.2%** target achievement.
-   **Omprakash O** recorded **143** total sales, corresponding to
    **28.6%** of the target.

These examples demonstrate how the dashboard can quickly surface both
high and low performers.

------------------------------------------------------------------------

## 💡 Business Use Cases

A dashboard like this could be used by a sales manager or business
analyst to:

-   Monitor sales team performance.
-   Identify high-performing employees.
-   Detect underperforming employees.
-   Track target achievement.
-   Prioritize coaching and training.
-   Compare regional performance.
-   Support performance review discussions.
-   Make data-driven sales decisions.

------------------------------------------------------------------------

## 📈 Key Performance Indicators

The dashboard primarily focuses on the following KPIs:

  KPI                  Purpose
  -------------------- -------------------------------------
  Total Sales          Measures actual sales generated
  Target               Measures expected sales
  Target Hit %         Measures achievement against target
  Away From Target %   Measures remaining target gap
  Top 5 Sales          Identifies strongest performers
  Bottom 5 Sales       Identifies weakest performers

------------------------------------------------------------------------

## 🧠 What I Practiced Through This Project

This project helped develop practical skills in:

-   Data organization in Excel
-   Formula-based calculations
-   Sales KPI analysis
-   Ranking and comparison
-   Data filtering
-   Dashboard creation
-   Chart selection
-   Business-focused data visualization
-   Converting raw data into actionable insights

------------------------------------------------------------------------

## 📂 Project Structure

``` text
Sales Performance & Target Achievement Dashboard/
│
├── Sales Performance & Target Achievement Dashboard.xlsx
└── README.md
```

------------------------------------------------------------------------

## 🚀 How to Use

1.  Download or clone the repository.
2.  Open the Excel workbook.
3.  Navigate to the dashboard.
4.  Select a region using the region filters.
5.  Review the Top 5 and Bottom 5 performers.
6.  Analyze target achievement and target gaps.
7.  Use the charts to compare sales performance visually.

------------------------------------------------------------------------

## 🎓 Project Type

**Excel Data Analytics & Business Intelligence Project**

**Focus Areas:**\
Sales Analytics • KPI Tracking • Performance Analysis • Target Analysis
• Data Visualization • Dashboard Development

------------------------------------------------------------------------

## 👤 Author

**Drishay Chauhan**

This project was created as part of my practical data analytics
portfolio to demonstrate the use of Microsoft Excel for business
performance analysis and dashboard development.
