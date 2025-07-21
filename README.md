#  Dynamic Pricing Strategy for E-commerce Profit Optimization

This project explores dynamic pricing strategies using historical Amazon sales data. The objective is to estimate demand elasticity, simulate profit outcomes under different pricing scenarios, and provide actionable insights to optimize product pricing and maximize profit.

---

##  Project Objectives

- **Clean and preprocess** raw e-commerce sales data.
- **Model price elasticity** to understand how demand responds to price changes.
- **Simulate** different price change scenarios (±10%) to forecast impact on revenue and profit.
- **Segment** products by category and analyze variations in elasticity.
- **Visualize** profit outcomes and recommend optimal pricing adjustments.

---
## Summary of the Solution

- **Data Cleaning & Preprocessing:** Handled missing and inconsistent values, converted data types, and standardized columns such as price (`Selling Price`), quantity (`Qty`), and category.
- **Feature Engineering:** Created simulated pricing and demand columns based on elasticity assumptions.
- **Elasticity Modeling:** Used a simple demand model with assumed elasticity (`-1.5`) to simulate how demand reacts to ±10% price changes.
- **Profit Simulation:** Calculated profit under different pricing strategies and summarized results at the category level.
- **Visualization:** Plotted bar charts to compare simulated profits across categories for price increases vs. decreases.
---

##  Files in this Repository

| File | Description |
|------|-------------|
| `dynamic_pricing_analysis.ipynb` | Main Jupyter/Colab notebook with data processing, modeling, simulation, and plotting code. |
| `Amazon Sale Report.csv` | Cleaned sales dataset used in the analysis. *(You may upload this separately if sensitive)* |
| `profit_simulation_plot.png` | Bar chart showing simulated profit by category and price scenario. |
| `pricing_strategy_memo.pdf` | 1–2 page summary report outlining the methodology, insights, and recommendations. *(optional)* |

---

##  How to Run

You can run this notebook using [Google Colab](https://colab.research.google.com/) or Jupyter locally:

```bash
pip install pandas seaborn matplotlib
```
---

## Key Insights:<br>
Categories like Set and Kurta are highly sensitive to price changes.<br>
Increasing prices by 10% in some categories can yield ~40% more profit, while others may see diminishing returns.<br>
Elasticity varies by category — one-size-fits-all pricing strategies are suboptimal.<br>
Demand modeling shows negative price elasticity, consistent with standard economic behavior.
