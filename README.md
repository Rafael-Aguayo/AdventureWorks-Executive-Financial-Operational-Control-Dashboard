# 🚴‍♂️ AdventureWorks: Executive Financial & Operational Control Dashboard
I recently redesigned a financial dashboard to transform it into a real decision-making tool. My goal was to move from simply "meeting a requirement" to designing a User Experience (UX) that prioritizes business logic. The dataset is from our beloved bicycle company: AdventureWorks.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-00599C?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-00838F?style=for-the-badge&logo=microsoft&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **From an Academic Assignment to a Real-World Executive Decision Tool.**  
> Comprehensive redesign of the **AdventureWorks** financial dashboard, converting a standard course project into a business-driven control board focused on **User Experience (UX)**, **Financial Storytelling**, and **Executive Decision-Making**.

---

## 📌 Quick Links & Resources
* 📁 **Download Power BI File (.pbix):** [Google Drive Download Link](https://drive.google.com/drive/folders/1d6TBJick7LWncmP-0UbqbZrEDHM3SIGX?usp=sharing) 
* 💼 **LinkedIn Profile:** [Your LinkedIn Profile](https://www.linkedin.com/in/rafael-aguayo-datos/)

---

## 🎯 Redesign Objectives & UX/UI Philosophy

The core goal of this project was to move beyond simply "fulfilling a prompt" and apply modern principles of information architecture and executive dashboard design:

1. **Canvas Maximization & Reduced Cognitive Load:**
   * Removed redundant slicers and brand logos that consumed prime visual real estate without adding analytical value.
   * Prioritized actionable data density per pixel.
2. **Intuitive Navigation via Cross-Filtering:**
   * Replaced traditional floating dropdown slicers with interactive cross-filtering.
   * Visual elements act directly as interactive filters, keeping the user interface clean, seamless, and professional.
3. **Business-Oriented Financial Storytelling:**
   * Shifted the analytical focus from static total sales figures to key **capital efficiency** and **operational return** metrics (`Operating ROI`, `Net ROCI`, `Operating Cost Ratio`).
4. **Visualizing Seasonality and Cumulative Efficiency:**
   * Implemented an **Area Chart** for Monthly Net Margin (%) to highlight seasonality and visual accumulation of operational profitability across the fiscal year.

---

## 📊 Dashboard Structure & Analysis

The dashboard is structured into two complementary analytical pages:

### 1. Operational Performance and Profitability Analysis

![Operational Performance & Profitability Analysis](docs/page1_preview.png)

Focuses on YoY growth dynamics, monthly trends, and absolute financial performance across 2011–2013:

* **Year-over-Year (YoY) Growth Dynamics:**
  * Tracks interannual percentage variations for Income (`% Income Variation`), Cost of Goods Sold (`% COGS Variation`), Gross Profit (`% Gross Profit Variation`), Operating Expenses (`% O.E. Variation`), and Net Profit (`% Net Profit Variation`).
  * In 2013, revenue experienced an explosive growth of **179.87%**, significantly outstripping the cost structure.
* **Monthly Revenue and Profitability Trends:**
  * Comparative time-series (January to December) plotting *Income*, *Gross Profit*, *Net Profit*, and *Operating Expenses*.
* **Statement of Results: Absolute Values (USD):**
  * **2011:** Revenue $7.08M | COGS $4.41M | Net Profit $2.10M
  * **2012:** Revenue $5.84M | COGS $3.56M | Net Profit $1.81M
  * **2013:** Revenue $16.35M | COGS $9.99M | Net Profit $5.05M
  * **Total Consolidated:** **$29.27M in Revenue** generating **$8.96M in Total Net Profit**.

---

### 2. Capital and Operational Efficiency Analysis

![Capital and Operational Efficiency Analysis](docs/page2_preview.png)

Evaluates overall financial health, operational leverage, and capital efficiency:

* **Executive KPI Cards:**
  * 💵 **Net Profit:** `$8.99M` (Total Net Profit generated).
  * 🔄 **Net ROCI:** `49.96%` (Return on Operating Capital Invested).
  * 🚀 **Operating ROI:** `383.12%` (Return generated on operating expenses).
  * 🛡️ **Operating Cost Ratio:** `61.35%` (Well-controlled cost structure).
* **Net Profit vs. Return Efficiency (ROI & ROCI):**
  * Combined visual contrasting exponential Net Profit growth (bars) against consistent ROCI (~50%) and high Operating ROI (~383%).
* **Monthly Profitability Efficiency (Net Margin %):**
  * Area chart demonstrating net margin acceleration from **30.1% in January** to peak levels exceeding **30.9% in November**, showing incremental margin retention as sales volume expands.

---

## 💡 Key Business Insights

* 🧊 **Strategic Cost Control (Operating Cost Ratio = 61.35%):**  
  Maintaining a controlled operating cost ratio ensures that revenue growth directly increases net profitability without triggering bloated fixed overhead.
* 🧊 **High Operational Return (Operating ROI = 383%):**  
  Every $1 invested in operating structure generated nearly **$4 in net profit**, validating operational agility and scalable processes.
* 🧊 **Inflection Point & Economies of Scale (2013):**  
  In 2013, process optimization allowed Net Profit growth to outpace Total Revenue growth, demonstrating strong economies of scale.
* 🧊 **Fast Capital Turnover (Net ROCI ≈ 50%):**  
  Confirms that capital deployed in inventory and logistics returns rapidly, doubling its value in each operational cycle.

---

## 🛠️ Data Architecture & Tech Stack

* **BI Tool:** Power BI Desktop / Service
* **Data Modeling:** Star Schema architecture connecting fact tables (Sales/Transactions) to time intelligence and dimension tables.
* **DAX Engine:** Custom measures for advanced financial metrics (`Operating ROI`, `ROCI`, `Cost Ratio`) and Time Intelligence calculations for YoY variations.
* **ETL Pipeline:** Advanced Power Query transformations for data cleaning, type enforcement, and performance optimization.

---

## 🚀 How to Use This Repository

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/adventureworks-financial-dashboard.git](https://github.com/YOUR_USERNAME/adventureworks-financial-dashboard.git)
