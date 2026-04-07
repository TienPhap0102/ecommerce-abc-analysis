
# **STRATEGIC PROFICT SEGMENTATION: OPTIMAZING E-COMMERCE INVENTORY & CUSTOMER LOYALTY THROUGH ABC ANALYSIS** 

## 📖 **Project Overview**
**The Business Context**

Operating a modern e-commerce platform with over 4,000 active SKUs and a rapidly growing customer base presents a critical resource allocation challenge. When warehouse capacity and marketing budgets are limited, treating every product and customer equally leads to bloated operational costs and inefficient marketing spend.

**The Core Objective**

This project bridges the gap between raw transactional data and strategic decision-making. The primary objectives are to:
- Optimize Inventory Operations: Identify the critical product lines that deserve premium warehouse space and strict inventory control.
- Maximize Marketing ROI: Pinpoint the absolute top 500 high-value customers to receive an exclusive Loyalty Program reward, ensuring the marketing budget is spent where it generates the highest retention value.

## 🗄️ **Data Architecture & Tech Stack**

**The Dataset**

The analysis is built on a robust relational dataset encompassing daily e-commerce operations. The data schema consists of four primary tables merged for comprehensive analysis:
- **EcomSales**: Transactional facts (Order volume, Sales, Discount, Profit).
- **Product**: Catalog dimensions (4,000+ SKUs, Categories, Sub-categories).
- **Customer**: Demographic attributes (Income levels, Occupations).
- **Region**: Regional mapping for logistics.
**Can reach Data Dictionary**: [Here](https://docs.google.com/spreadsheets/d/11u-oNOeFALZyMYU271r28vINu99LFzmb/edit?gid=678990590#gid=678990590)

**The Tech Stack**

- **Language**: Python 3.x
- **Environment**: Google Colab / Jupyter Notebook.
- **Data Manipulation**: `pandas`, `numpy` (Advanced aggregation, merging, and cumulative calculations).
- **Data Visualization**: `plotly.express`, `seaborn`, `matplotlib`.

## 🏆 **Executive Results & Strategic Recommendations**

### 📦 **Workstream 1: Inventory Optimization Strategy**
The analysis segmented the 4,000+ product catalog, revealing that a concentrated portfolio drives the vast majority of profitability. We are transitioning from a uniform warehousing model to a priority-based allocation strategy.
- **Group A (The Critical Drivers)**: ~35% of Products $\rightarrow$ 80% of Profit. 
-- **Operations**: Enforce rigorous daily/weekly cycle counts to guarantee zero stockouts.
-- **Logistics**: Allocate prime, easily accessible, and high-security warehouse zones to minimize picking lead times.
-- **Supply Chain**: Establish expedited shipping agreements and multi-vendor backups for these high-velocity items.

- **Group B (The Stable Core)**: ~29% of Products $\rightarrow$ 15% of Profit.
-- **Operations**: Maintain standard safety stock levels based on automated demand forecasting.
-- **Strategy**: Store in secondary accessible locations and bundle with Group A items to accelerate turnover.

- **Group C (The Capital Trap)**: ~36% of Products $\rightarrow$ 5% of Profit.
-- **Operations**: Drastically minimize stock levels to free up working capital.
-- **Strategy**: Transition to 'Make-to-Order' or dropshipping models where feasible. Relocate existing stock to deep/compact storage and initiate clearance promotions to liquidate stagnant inventory.

### 🎯 **Workstream 2: VIP Customer Loyalty Program**
- **Group A (The VIP Tier)**: ~30% of Customers $\rightarrow$ 80% of Profit
-- **Demographic Persona**: Predominantly 'Professional' (29%) and 'Skilled Manual' (26%) with consistent mid-to-high income levels ($20k-$60k).
-- **Insight**: High profitability here is driven by consistent purchasing behavior, not absolute wealth.
-- **Actionable Strategy**: Allocate 100% of the 500 premium gift slots exclusively to this group. Implement a dedicated VIP program offering early product access, personalized communication, and prioritized customer support.

- **Group B (The Growth Segment)**: ~15% of Customers $\rightarrow$ 10% of Profit
-- **Demographic Persona**: Mirrors Group A, indicating strong potential for upward migration.
-- **Actionable Strategy**: Deploy targeted up-selling and cross-selling campaigns. Introduce tiered loyalty incentives to encourage higher order frequencies and transition these users into Group A.

- **Group C (The Mass Market)**: ~55% of Customers $\rightarrow$ 10% of Profit
-- **Demographic Persona**: Highly fragmented with a broad income distribution.
-- **Actionable Strategy**: Avoid high-cost, personalized engagement. Shift to cost-effective retention strategies such as broad-reach email marketing, seasonal mass discounts, and automated reactivation workflows for infrequent buyers.
