# 🛒 Retail Sales Data Analytics
### Think Like a Designer – Improving Data Visualizations

> Exploratory data analysis & visualization of retail sales transactions using Python. Covers 11 chart types — bar, line, scatter, histogram, box, violin, bubble & interactive Plotly charts. Built with Pandas, Matplotlib, Seaborn & Plotly to uncover sales trends, profit insights & regional performance.

---

##  Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

---

##  Overview

This project demonstrates how to **think like a designer** when creating data visualizations. It is not just about displaying data — it is about communicating a story **clearly, accurately, and beautifully**.

For each visualization, a  **Before** (plain default chart) is compared against a  **After** (redesigned chart) applying core design principles:

| Principle | Description |
|---|---|
| **Clarity** | Remove chart junk; maximize data-ink ratio |
| **Accuracy** | Honest axes, no misleading truncation |
| **Colour** | Purposeful palette; accessible to colour-blind readers |
| **Labelling** | Clear titles, axis labels, units, and annotations |
| **Hierarchy** | Guide the eye to the most important insight first |

---

##  Dataset

**File:** `sales_data.csv`  
**Rows:** 500 transactions  
**Period:** January 2023 – December 2023

| Column | Type | Description |
|---|---|---|
| `Order_ID` | String | Unique order identifier |
| `Date` | Date | Order date |
| `Region` | Category | North / South / East / West / Central |
| `Category` | Category | Electronics / Clothing / Furniture / Food / Sports |
| `Sales` | Float | Revenue from the order (USD) |
| `Quantity` | Integer | Units ordered |
| `Discount` | Float | Discount rate applied (0.0 – 0.4) |
| `Profit` | Float | Profit earned (can be negative) |
| `Customer_Age` | Integer | Age of the customer |

---

##  Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4c72b0)
![Plotly](https://img.shields.io/badge/Plotly-5.x-3F4F75?logo=plotly)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

---

##  Project Structure

```
retail-sales-data-analytics/
│
├── think_like_a_designer_visualization.ipynb   ← Main notebook
├── sales_data.csv                               ← Dataset
├── README.md                                    ← This file
└── requirements.txt                             ← Dependencies
```

---

##  Visualizations

The notebook contains **11 visualizations** across 2 sections:

### Section 1 — Core Visualizations (Before & After)
| # | Chart Type | Library | Business Question |
|---|---|---|---|
| 1 | Bar Chart | Seaborn / Matplotlib | Which category generates the most revenue? |
| 2 | Line Chart | Matplotlib | How do sales trend across 12 months? |
| 3 | Scatter Plot | Seaborn | Does higher sales always mean higher profit? |
| 4 | Histogram | Seaborn | How are sales values distributed? |
| 5 | Grouped Bar | Plotly | Which region × category performs best? |

### Section 2 — Additional Visualizations
| # | Chart Type | Library | Business Question |
|---|---|---|---|
| 6 | Box Plot | Seaborn | Which category has the most consistent sales? |
| 7 | Stacked Bar | Matplotlib | What is the sales mix inside each region? |
| 8 | Violin Plot | Seaborn | Which regions are most/least profitable? |
| 9 | Donut Chart | Plotly | What % of revenue does each category own? |
| 10 | Bubble Chart | Plotly | Which region balances sales, profit & volume best? |
| 11 | Multi-Line Chart | Plotly | How does each category trend month by month? |

---

##  Key Insights

-  **Electronics** consistently generates the highest total revenue across all regions
-  Sales show a **seasonal peak** mid-year with a dip in early months
-  High sales do **not always guarantee profit** — some large orders result in losses due to high discounts
-  The **North and West regions** lead in both total sales and profit margins
-  **Food and Clothing** categories have the tightest profit margins with frequent break-even orders
-  Sales distribution is **right-skewed** — most orders are small with a few very high-value outliers

---

## ▶️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/retail-sales-data-analytics.git
cd retail-sales-data-analytics
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook think_like_a_designer_visualization.ipynb
```

**4. Run all cells**  
Go to `Kernel` → `Restart & Run All`

>  Make sure `sales_data.csv` is in the same folder as the notebook.

---

##  Requirements

```
pandas
numpy
matplotlib
seaborn
plotly
jupyter
```

Install all at once:
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

---

##  License

This project is for educational purposes as part of a university data visualization assignment.

---

<p align="center">Made with  using Python & Jupyter Notebook</p>
