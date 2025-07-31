## Project Overview
This project aims to analyze the declining sales and non-recurring customer trends in the electronics section of Imtiaz Mall. Through comprehensive data analysis, the project identifies key correlations, segments customers into distinct clusters, and evaluates predictive models to develop actionable strategies for improving customer retention and sales growth.

---

## Key Findings

### 1. **Correlation Analysis**
- **Customer Loyalty**: Strong positive correlation with purchase frequency (`0.68`) and likelihood of future purchases (`0.26`).
- **Lifetime Spend**: Correlates with average spending per purchase (`0.54`) and purchase frequency (`0.57`).
- **Age**: Moderate positive correlation (`0.40`) with lifetime spend, indicating older customers contribute more over time.
- **Weak Relationships**: Income bracket and purchase amount show minimal influence on other variables.

### 2. **Clustering Insights (K-Means)**
- **Cluster 4**: High-spending customers with strong brand affinity. Ideal for premium product targeting.
- **Cluster 6**: Frequent purchasers with low spending. Potential for bundled offers.
- **Cluster 1**: Moderate spenders with low brand loyalty. Focus on educational campaigns.

### 3. **Model Performance**
- **Linear Regression**: Poor fit (R²: `-0.01`), indicating non-linear relationships in the data.
- **Decision Tree Classifier**: High accuracy (`0.92`), precision (`0.95`), and recall (`0.96`) for predicting purchase behavior.
- **K-Means Clustering**: Identified 7 actionable customer segments with distinct behaviors.

---

## Recommendations

### 1. **Marketing Strategies**
- **Premium Customers (Cluster 4)**: Offer loyalty rewards, early access to high-end products, and brand-exclusive deals.
- **Frequent, Low-Spend Customers (Cluster 6)**: Promote bundled discounts and value-driven messaging.
- **Low Brand Affinity (Cluster 1)**: Use educational campaigns to build brand trust and highlight product quality.

### 2. **Inventory Management**
- Align stock with high-demand product categories identified in clusters (e.g., "High" preference clusters).
- Use predictive models to anticipate purchase trends and optimize inventory levels.

### 3. **Customer Retention**
- Leverage decision tree insights to personalize follow-ups (e.g., targeted product recommendations).
- Implement retention programs for high-loyalty customers (e.g., VIP perks, personalized offers).

---

## Files and Resources
- **Report PDF**: Contains detailed analysis, visualizations, and full recommendations.
- **Data Sources**: Customer purchase history, demographics, and behavioral metrics (not included in this repository).
- **Models**: Linear regression, decision tree classifier, and K-means clustering (code not included).
---



