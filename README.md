# Dynamic Pricing Optimization for Retail Stores

## Introduction
In this notebook, we aim to develop a **dynamic pricing model** to optimize item prices at a retail store. The objective is to **maximize revenue** while ensuring our prices remain competitive in the market. This involves analyzing sales data, understanding the impact of pricing strategies, and leveraging competitor pricing and market trends.

---

## Dataset Overview
The dataset provides comprehensive pricing information for various items sold in a retail store, including their corresponding prices at competing stores. The key columns in the dataset are as follows:

1. **`Fiscal_Week_Id`**: The fiscal week identifier, indicating the time frame of the data.
2. **`Store_Id`**: A unique identifier for each store.
3. **`Item_Id`**: A unique identifier for each item sold.
4. **`Price`**: The price of the item at our store.
5. **`Item_Quantity`**: The quantity of the item sold during the fiscal week.
6. **`Sales_Amount_No_Discount`**: The total sales amount for the item, calculated without applying any discounts.
7. **`Sales_Amount`**: The total sales amount for the item after applying discounts.
8. **`Competition_Price`**: The price of the same item at a competing store.

This dataset spans multiple fiscal weeks, covering a variety of items and categories, providing a rich source for understanding pricing strategies and their performance.

---

## Problem Statement
The retail sector is highly competitive, and pricing plays a crucial role in driving sales and maximizing revenue. The current challenge involves creating a **dynamic pricing model** that optimizes item prices while maintaining competitiveness in the market.

The key tasks to address this problem include:

### 1. **Analysis of Current Pricing Strategy**
   - Examine the relationship between our store's prices, competitor prices, and sales performance.
   - Identify trends in sales and revenue across fiscal weeks.

### 2. **Competitor Pricing Gap Analysis**
   - Compare our store's prices with competitor prices for each item.
   - Identify opportunities to adjust prices where competitors may have an advantage.

### 3. **Dynamic Pricing Model Development**
   - Incorporate factors such as:
     - **Competitor Pricing**: Adjust prices based on how our pricing compares to competitors.
     - **Demand Elasticity**: Analyze the sensitivity of item sales to price changes.
     - **Market Trends**: Utilize historical sales data and seasonal patterns to predict optimal pricing.

### 4. **Model Simulation and Evaluation**
   - Implement the dynamic pricing model.
   - Simulate its performance on historical data.
   - Compare the results of the dynamic pricing model against the current pricing strategy to evaluate its impact on revenue.

### 5. Machine Learning Model Selection
   - Identify the best machine learning models for dynamic pricing optimization.
   - Compare model performance using key metrics (e.g., RMSE, MAE, revenue impact).

---

## Expected Outcomes
1. A detailed analysis of the current pricing strategy and its effectiveness.
2. Insights into competitor pricing gaps and potential adjustments.
3. A dynamic pricing model tailored to optimize revenue while maintaining competitiveness.
4. Simulated results showcasing the potential revenue uplift with the new pricing model.
5. Recommendations on the best machine learning model for dynamic pricing optimization.

Let’s begin by exploring the dataset and understanding the pricing trends [click here](./Dynamic%20Pricing.ipynb)