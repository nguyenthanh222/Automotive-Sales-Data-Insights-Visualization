# Automotive Sales Insights & Market Analysis
## 📌 Project Overview
This project performs a comprehensive analysis of the automotive market using a dataset of various car models. The goal is to understand the relationship between vehicle specifications (horsepower, fuel efficiency, price) and their market performance (unit sales, resale value).

The analysis focuses on identifying which factors contribute most to a car's Retention Value and how different manufacturers compare in the premium and economy segments.

## 📊 Dataset Description
The dataset used in this project is sourced from Kaggle (IBM Data Visualization course). It contains information on several manufacturers, including:

Vehicle Specs: Engine size, Horsepower, Fuel efficiency, Wheelbase, Curb weight.

Sales Data: Unit sales, Current price, and 4-year resale value.

Key Calculated Fields: - Retention %: The ratio of resale value to original price.

Retention Value: Categorized performance (e.g., GOOD).

HP Level: Classification of performance based on Horsepower.

## 🛠️ Tools & Technologies
Data Source: Kaggle / IBM

Data Processing: Microsoft Excel (Pivot Tables, Data Cleaning)

Visualizations: Column Charts, Pie Charts, and Sunburst Charts (to visualize hierarchical data like Manufacturer > Model).

## 🚀 Key Insights
Based on the analysis (refer to the Bar Chart and Sunburst data):

Resale Performance: Luxury brands like Porsche and Mercedes-Benz maintain high average resale values (over $39k), but their sales volume is lower compared to mass-market brands.

Efficiency vs. Power: There is a clear trade-off between Fuel Efficiency and Horsepower. High-performance models (High HP Level) show a significant drop in MPG.

Retention Trends: Brands like Volkswagen show strong "GOOD" retention values, making them a balanced choice for budget-conscious consumers.

## 📈 Data Visualization & Analysis
This project transforms raw automotive data into actionable insights using three primary visualization strategic approaches:
<img width="1024" height="450" alt="image" src="https://github.com/user-attachments/assets/acd00823-410e-4e80-9823-d8eddb57f9ec" />

1. Brand Performance Analysis (Bar Chart)
Objective: Compare the financial positioning of major manufacturers.

Insight: By plotting Average Price against Average 4-Year Resale Value, we can identify which brands offer the best investment. For instance, while Porsche commands the highest price point, its resale value remains significantly higher than competitors, indicating strong brand equity.

2. Market Segmentation (Pie Chart)
Objective: Understand the distribution of vehicle types in the dataset.

Insight: Visualizing the ratio between Passenger cars vs. Other vehicle types reveals the market's inventory focus and helps identify which segment drives the bulk of unit sales.

3. Hierarchical Sales Exploration (Sunburst Chart)
Objective: Drill down from Manufacturer to specific Models.

Insight: This multi-level chart provides a bird's-eye view of sales distribution. It highlights "Hero Models" within each brand—for example, showing which specific Volkswagen model (like the Jetta or Passat) contributes most to the brand's overall volume.

4. Technical Correlation (Scatter Plot/Column)
Objective: Explore the link between Engine Performance and Efficiency.

Insight: Analysis of Horsepower (HP Level) vs. Fuel Efficiency shows the efficiency penalty paid for performance, categorized by "Medium" to "High" HP levels.
