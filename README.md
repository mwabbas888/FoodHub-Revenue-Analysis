# FoodHub: Revenue & Operations Analysis

This repository contains the full analysis and data for the FoodHub project, completed as part of the MIT Data Science and Machine Learning program.

---

## Business Objective

The goal of this project was to analyze customer order data for FoodHub, a food delivery aggregator. The key objectives were to identify the main drivers of revenue, uncover operational inefficiencies, and provide actionable recommendations to enhance customer satisfaction and boost profitability. This project demonstrates skills in exploratory data analysis (EDA), data visualization, and strategic business insight generation.

---

## Key Questions Addressed

1.  **Popularity & Volume:** Which cuisine types have the highest order counts overall and how do they compare between weekdays and weekends?
2.  **Customer Satisfaction by Cuisine:** How do customer ratings for different cuisine types vary between weekdays and weekends?
3.  **Strategic Opportunities:** Where are the key areas to focus marketing and operational efforts based on order volume and customer satisfaction?

---

## Key Findings & Visualizations

Here are some of the key insights derived from the analysis:

**1. American Cuisine Dominates Order Volume**
*Insight:* American cuisine consistently shows the highest order count, significantly outperforming all other cuisine types. Japanese and Italian cuisines also demonstrate substantial popularity.
<img src="./visualizations/Cuisine Type vs Order Count.png" alt="Cuisine Type vs Order Count"/>

**2. Weekend Spikes in Popular Cuisines**
*Insight:* The top-performing cuisines (American, Japanese, Italian, Chinese) experience a notable increase in order volume during weekends compared to weekdays. American cuisine, in particular, shows a substantial jump.
<img src="./visualizations/Cuisine Type vs Order Count vs Day of the Week.png" alt="Cuisine Type vs Order Count vs Day of the Week"/>

**3. Varying Rating Performance Across Cuisines and Days**
*Insight:* While ratings generally remain high, some cuisines show distinct patterns. For instance, Spanish cuisine receives very high ratings on weekends but lower on weekdays. Conversely, Vietnamese cuisine's ratings drop significantly on weekends. American and Japanese cuisines maintain relatively consistent high ratings across both weekdays and weekends.
<img src="./visualizations/Line Plot: Ratings for Cuisine Types.png" alt="Line Plot: Ratings for Cuisine Types"/>

---

## Actionable Recommendations

Based on the analysis, I recommend the following strategic actions:

* **Capitalize on American Cuisine's Popularity:** Given its leading order volume, continue to prioritize American cuisine in marketing and partnerships. Consider "American Weekend Feast" promotions to leverage its weekend surge.
* **Boost Weekend Revenue with Targeted Promotions:** Design weekend-specific campaigns for American, Japanese, and Italian cuisines, as these show strong uptake during these periods. This could include weekend-only discounts or bundle deals.
* **Optimize for Spanish & Vietnamese Cuisine:**
    * **Spanish:** Investigate the factors contributing to its high weekend ratings. Can these insights be applied to weekday service for Spanish cuisine, or is it a specific weekend indulgence for customers? Promote Spanish cuisine heavily on weekends.
    * **Vietnamese:** Urgently investigate the significant drop in weekend ratings for Vietnamese cuisine. This could indicate operational issues (e.g., quality, delivery, accuracy) during peak weekend hours that need immediate attention to prevent customer churn.
* **Maintain Focus on Consistently High-Rated Cuisines:** Ensure consistent quality and operational excellence for American and Japanese cuisines, as their stable high ratings across the week indicate strong customer satisfaction.

---

## Technical Details

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Dataset:** `foodhub_order.csv` (included in this repository)
* **Analysis Notebook:** `Foodhub_Analysis.ipynb` (the Jupyter Notebook containing all the code)
