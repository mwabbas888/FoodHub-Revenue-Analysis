# FoodHub: Revenue & Operations Analysis

This repository contains the full analysis and data for the FoodHub project, completed as part of the MIT Data Science and Machine Learning program.

---

## Business Objective

The goal of this project was to analyze customer order data for FoodHub, a food delivery aggregator. The key objectives were to identify the main drivers of revenue, uncover operational inefficiencies, and provide actionable recommendations to enhance customer satisfaction and boost profitability. This project demonstrates skills in exploratory data analysis (EDA), data visualization, and strategic business insight generation.

---

## Key Questions Addressed

1.  **Revenue Drivers:** Which cuisine types and restaurants generate the most revenue?
2.  **Operational Efficiency:** What is the relationship between order cost, preparation time, and delivery time?
3.  **Customer Satisfaction:** What factors correlate with higher customer ratings?
4.  **Spending Patterns:** How do customer spending habits differ between weekdays and weekends?

---

## Key Findings & Visualizations

Here are some of the key insights derived from the analysis:

**1. American Cuisine is the Primary Revenue Driver**
*Insight:* While several cuisines are popular, American food generates significantly more revenue for the platform, making it a prime target for promotional activities.
<img src="./visualizations/revenue_by_cuisine.png" alt="Revenue by Cuisine"/>

**2. Customer Satisfaction is Not Driven by Speed or Cost Alone**
*Insight:* The correlation heatmap showed no strong link between ratings and variables like delivery time or cost. This suggests that food quality and order accuracy are likely more important drivers of satisfaction.
*(You would include your correlation matrix image here, e.g., `<img src="./visualizations/correlation_heatmap.png" alt="Correlation Heatmap"/>`)*

**3. Clear Weekend Spending Uplift**
*Insight:* Customers, on average, spend more per order on weekends, especially on American and Japanese cuisine. This presents a clear opportunity for targeted weekend promotions.
<img src="./visualizations/weekday_weekend_spending.png" alt="Weekday vs Weekend Spending"/>

---

## Actionable Recommendations

Based on the analysis, I recommended the following strategic actions:

* **Launch Targeted Promotions:** Offer "weekend special" vouchers for American and Japanese restaurants to capitalize on existing spending habits and further increase average order value.
* **Prioritize High-Value Restaurant Partnerships:** Focus marketing efforts and premium placement on restaurants that have both high ratings and high order volume (e.g., The Meatball Shop, Shake Shack) to maximize platform revenue.
* **Shift Focus for Improving Ratings:** Instead of focusing solely on reducing delivery times, implement a system to track order accuracy and food quality feedback to better address the real drivers of customer satisfaction.

---

## Technical Details

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Dataset:** `foodhub_order.csv` (included in this repository)
* **Analysis Notebook:** `Foodhub_Analysis.ipynb` (the Jupyter Notebook containing all the code)
