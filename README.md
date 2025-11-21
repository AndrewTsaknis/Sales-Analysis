# Superstore Sales Analysis 📊

## 📌 Project Summary
This project analyzes the Superstore dataset to uncover trends in sales, profit, and customer behavior.  
The goal is to identify key performance insights such as best-selling categories, most profitable sub-categories, discount impact, and product performance.

The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations that highlight relationships between variables such as Sales, Profit, Category, Sub-Category, and Discount.  
This project is intended for practice with data analysis, Python visualization, and reporting.
---
## 📂 Dataset Location

Place the dataset file (Superstore.csv) in the same folder as the Jupyter notebook or Python script.
The project code is written to load the file from the root directory of the project.

## 🔗 Dataset Download

If you do not already have the dataset, you can download it here:

Superstore Dataset (Kaggle):
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
---

## 📊 Key Insights
The following visualizations were created using Python (Pandas, Matplotlib, Seaborn):
<img width="721" height="470" alt="download" src="https://github.com/user-attachments/assets/803f759e-a9cf-4ba8-9dac-18b11e94f154" />

1. **Sales by Category**
 A bar chart showing total sales for each category to compare performance.

-Technology leads in total sales, indicating strong customer demand for tech products.

-Furniture and Office Supplies follow but with noticeably lower revenue.

-This suggests Technology is the most impactful category for driving revenue growth.

2. **Profit vs Sales (Scatter Plot)**

-There is no strong linear correlation between higher sales and higher profit.

-Some high-sales orders result in negative profit, often due to large discounts or high shipping costs.

-Clusters show that moderate-sale orders tend to be more consistently profitable.

3. **Top 10 Products by Sales**

-A small group of products contributes a disproportionate amount of revenue.

-These top performers are mostly in Technology and Furniture.

-Focusing marketing, stock availability, and promotions on these products can increase revenue efficiency.

4. **Profit by Sub-Category**

-Sub-categories such as Copiers, Phones, and Accessories show strong profitability.

-Others — especially Tables, Bookcases, and Binders — frequently produce negative or low profit.

-This highlights areas where pricing strategy or supplier negotiation may need reevaluation.

5. **Discount Distribution**

-Most orders have very low discounts, but there are noticeable spikes at higher discount levels.

-High discounts correlate strongly with reduced profit, and many high-discount orders lead to losses.

-This suggests tightening discount policies could significantly improve financial performance.


2. **Profit vs Sales (Scatter Plot)**  
   Visualizes whether higher sales correlate with higher profitability and highlights category clusters.

3. **Top 10 Products by Sales**  
   Identifies the products generating the most revenue.

4. **Profit by Sub-Category**  
   Displays which sub-categories contribute most to profitability.

5. **Discount Distribution**  
   Shows how discounts are distributed across orders and helps evaluate the impact of discounting.

---

## 🛠️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/AndrewTsaknis/Sales-Analysis.git
