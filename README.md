Optimising Furniture Sales Potential 🪑📊
=========================================

### Business Data Management Capstone Project | IIT Madras

**Student:** Ayan Hussain | **Roll:** 23f1000932 | **Institute:** IIT Madras

📖 Project Overview
-------------------

**Good Luck Furniture** (Prayagraj, UP) is a family-owned business known for handcrafted wooden furniture. Despite a reputation for quality, the business faced recurring **operational bottlenecks**---specifically during the wedding ("Lagan") season.

This project utilized **2 years of digitized sales records (2023-2025)** to diagnose the root causes of lost revenue and provide a data-backed roadmap for growth.

👉 [**View the Live Project Website**](https://23f1000932.github.io/optimising-furniture-sales-potential/ "null") for interactive charts and the full analysis journey.

📂 Data Assets
--------------

The analysis is built on two primary datasets digitized from manual logbooks:

### 1\. Sales Dataset (`Dataset.csv`)

Contains **80 verified transactions** with the following schema:

-   `OrderID`: Unique identifier (e.g., GLF-1001)

-   `OrderDate`: Date of purchase

-   `Category`: Bed, Sofa, Table, Custom, etc.

-   `CostPrice` vs `SellingPrice`: Used to calculate margins

-   `Profit`: Calculated field

### 2\. Shop Gallery

Visual documentation of the inventory and workshop conditions was collected to contextualize the data.

-   [View Shop Photo Gallery (Google Drive)](https://drive.google.com/drive/folders/1441zYiGjtpiynHZVXoQ-ygZSdqwY5lN4 "null")

🛠️ Analysis Methodology
------------------------

### Phase 1: Data Cleaning & Prep

-   **Standardization:** Converted inconsistent date formats to `DD-MM-YYYY`.

-   **Error Handling:** Removed incomplete records from the manual logs.

-   **Feature Engineering:**

    -   `Delivery_Lag` = `Actual_Delivery_Date` - `Promised_Date`

    -   `Profit_Margin` = `(Profit / Selling_Price) * 100`

### Phase 2: Exploratory Data Analysis (EDA)

-   **Time-Series Decomposition:** Visualized monthly profit to identify the **10x spike** in Nov/Dec.

-   **Pareto Analysis (80/20):** Identified that **63.8%** of profits come from just the 'Bed' & 'Custom' categories.

-   **Supplier Benchmarking:** Calculated average delay days per supplier.

💡 Key Findings
---------------

| Metric         | Insight                                      | Impact |
|---------------|----------------------------------------------|--------|
| **Seasonality** | Nov profits > ₹1 Lakh vs Sep profits < ₹25k | ~30% lost revenue due to stockouts in peak season |
| **Top Products** | Bed & Custom categories dominate           | Chair category is underperforming (<3% profit share) |
| **Supply Chain** | *Sheesham Crafts Inc.* avg delay: **5.5 days** | This single supplier causes **80% of production halts** |


🚀 Strategic Recommendations
----------------------------

Based on the data, three strategies were presented to the stakeholder:

1.  **Seasonal Inventory Plan:**

    -   *Action:* Procure raw materials for top 10 items 30% in advance of September.

    -   *Target:* Capture the forecasted **₹1.67 Lakh** peak profit in 2025.

2.  **"Bundle & Clear" Strategy:**

    -   *Action:* Bundle slow-moving inventory (Rocking Chairs) with high-demand Beds.

    -   *Target:* Liquidate dead stock to free up **₹1 Lakh** in working capital.

3.  **Supplier Diversification:**

    -   *Action:* Shift 50% of orders from "Sheesham Crafts" to "Rajesh Timber Store".

    -   *Target:* Reduce average delay to **< 2 Days**.

📂 Repository Contents
----------------------

-   `index.html`: Portfolio website source code.

-   `Dataset.csv`: Cleaned sales transaction data.

-   `final-report.pdf`: Comprehensive analysis & charts.

-   `presentation.pptx`: Executive summary deck.

-   `midterm.pdf` & `proposal.pdf`: Project timeline and initial findings.

*This project was completed as part of the Business Data Management (BDM) course at IIT Madras.*
