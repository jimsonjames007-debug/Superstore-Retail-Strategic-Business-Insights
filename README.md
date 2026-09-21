# Superstore Retail Strategic Business Insights

[![Tableau](https://img.shields.io/badge/Tableau-Packaged_Workbook-E97627?style=flat-square&logo=tableau&logoColor=white)](tableau/)
[![Dataset](https://img.shields.io/badge/Data-Superstore_Retail-2980B9?style=flat-square&logo=google-sheets&logoColor=white)](data/)
[![Reports](https://img.shields.io/badge/Documentation-Reports_&_Analysis-27AE60?style=flat-square&logo=adobe-acrobat-reader&logoColor=white)](reports/)

> **Comprehensive End-to-End Business Intelligence and Data Storytelling Solution** analyzing retail sales performance, customer segments, profit leakages, discount elasticity, and regional operational metrics using Tableau.

---

## Repository Structure

```
├── data/
│   └── Superstore_Retail_Dataset.csv                   # Raw Superstore transaction dataset
├── tableau/
│   └── Superstore Strategic Business Insights - VSTT.twbx # Full packaged interactive Tableau workbook
├── reports/
│   ├── VSTT Practical Assignment Report.pdf             # Comprehensive project report (PDF)
│   ├── VSTT Practical Assignment Report.docx            # Editable documentation report (DOCX)
│   └── VSTT Project Output Oct25 G1.pdf                 # Project output presentation & slides
├── images/
│   ├── dashboards/                                      # High-resolution dashboard screenshots
│   │   ├── Customer & Product Performance Dashboard.png
│   │   ├── Executive Overview Cockpit Dashboard.png
│   │   ├── Executive Overview Dashboard.png
│   │   └── Regional & Operational Insights Dashboard.png
│   ├── stories/                                         # Tableau Story Points progression
│   │   ├── Strategic Retail Executive Story.png
│   │   ├── Strategic Retail Executive Story 2.png
│   │   ├── Strategic Retail Executive Story 3.png
│   │   ├── Strategic Retail Executive Story 4.png
│   │   ├── Strategic Retail Executive Story 5png.png
│   │   └── Strategic Retail Executive Story 6.png
│   └── charts/                                          # Key specialized chart visualizations
│       ├── Discount vs Profit Margin Scatter.png
│       └── Sub-Category Profitability Waterfall.png
├── .gitignore                                           # System and temp files ignore rules
└── README.md                                            # Project overview & documentation
```

---

## Project Overview & Key Objectives

1. **Executive Performance Cockpit:** Provide high-level visibility into total revenue, profit margins, order volumes, and year-over-year growth trajectories.
2. **Profit Leakage & Discount Analysis:** Investigate how excessive discounting impacts profit margins across product categories and sub-categories (e.g., Tables, Bookcases, Supplies).
3. **Customer & Product Segmentation:** Analyze customer lifetime value (CLV), purchase frequency, segment-level profitability (Consumer, Corporate, Home Office), and top revenue-generating SKUs.
4. **Regional & Operational Efficiency:** Identify geographic profit concentrations, underperforming states/regions, and shipping delay bottlenecks.
5. **Interactive Executive Storytelling:** Guide decision-makers through strategic insights, root-cause diagnostics, and actionable recommendations.

---

## Dashboards & Visualizations

### 1. Executive Overview Dashboard
Comprehensive summary tracking revenue trends, profit KPIs, category breakdown, and monthly trajectory.

![Executive Overview Dashboard](images/dashboards/Executive%20Overview%20Dashboard.png)

---

### 2. Executive Overview Cockpit Dashboard
Streamlined executive cockpit designed for rapid KPI monitoring and macro performance tracking.

![Executive Overview Cockpit Dashboard](images/dashboards/Executive%20Overview%20Cockpit%20Dashboard.png)

---

### 3. Customer & Product Performance Dashboard
Deep-dive into customer segments, retention patterns, high-value accounts, and product matrix performance.

![Customer & Product Performance Dashboard](images/dashboards/Customer%20&%20Product%20Performance%20Dashboard.png)

---

### 4. Regional & Operational Insights Dashboard
Geographical maps, shipping mode comparisons, delivery timeframes, and regional margin variances.

![Regional & Operational Insights Dashboard](images/dashboards/Regional%20&%20Operational%20Insights%20Dashboard.png)

---

## Specialized Diagnostic Visualizations

| Discount vs. Profit Margin Scatter | Sub-Category Profitability Waterfall |
| :---: | :---: |
| ![Discount vs Profit Margin](images/charts/Discount%20vs%20Profit%20Margin%20Scatter.png) | ![Sub-Category Waterfall](images/charts/Sub-Category%20Profitability%20Waterfall.png) |
| *Identifies aggressive discounting thresholds leading to negative margins.* | *Demonstrates cumulative profit contributions and erosion by sub-category.* |

---

## Strategic Executive Story Progression

The interactive Tableau Story walks executives through key narrative milestones:
- **Story Point 1-2:** Overall Financial Health & Revenue Dynamics
- **Story Point 3-4:** Discount Thresholds & Negative Margin Diagnostics
- **Story Point 5-6:** Operational Bottlenecks & Strategic Action Plan

![Strategic Retail Executive Story](images/stories/Strategic%20Retail%20Executive%20Story.png)

---

## How to Run / Explore

1. **Prerequisites:** Install [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Reader](https://www.tableau.com/products/reader) (Free).
2. **Open Workbook:**
   - Clone or download this repository.
   - Navigate to `tableau/` and double-click `Superstore Strategic Business Insights - VSTT.twbx`.
3. **Data Source:** The packaged workbook includes the embedded extract, or you can access the raw CSV file in `data/Superstore_Retail_Dataset.csv`.
4. **Documentation:** Detailed business reports and findings are located in `reports/`.

---

## Authors & Project Info
- **Project:** VSTT Practical Assignment & Business Intelligence Case Study
- **Tools Used:** Tableau, Excel / CSV, Data Analytics & Storytelling
