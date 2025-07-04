# AMAZON-CASE-STUDY

## 🛍️ E-Commerce Product Dataset Analysis

##📌 Project Topic
Amazon Product Review Analysis — A case study exploring product performance, customer engagement, and pricing strategies using Excel-based data analysis.

## 📊 Project Overview
This project focuses on analyzing an Amazon e-commerce product dataset to uncover insights about pricing, discounts, ratings, and customer engagement. The goal is to clean the data, explore patterns using PivotTables and calculated columns, and present findings in a dynamic Excel dashboard.

## 🛠️ Tools Used
Microsoft Excel (PivotTables, formulas, charts, dashboard)

## 📂 Data Sources
The dataset was scraped from Amazon product pages and includes:

Product details: name, category, price, discount, and ratings
Customer engagement: review count, review titles, and content
Each row represents a unique product with aggregated reviewer data Total Records: 1,465 rows Total Fields: 16 columns Purpose: Educational and analytical use

## 🧹 Data Cleaning (Excel)
✅ Tasks Performed:-

- Removed duplicates and blank rows
- Converted discount percentages from text to numeric
- Split and cleaned comma-separated values
- Standardized column names and formats
- Ensured consistency in price and rating fields
  

## 📈 Analysis Tasks & Formulas
Question Description Formula/Method

- 1️⃣ Average discount % by category =AVERAGEIFS(discount_percentage, category, [category])

- 2️⃣ Product count per category PivotTable: Rows = category, Values = Count of product_name

- 3️⃣ Total reviews per category =SUMIFS(rating_count, category, [category])

- 4️⃣ Highest-rated products Sort by rating descending

- 5️⃣ Avg actual vs discounted price by category PivotTable with two value fields: AVERAGE(actual_price) and AVERAGE(discounted_price)

- 6️⃣ Products with most reviews Sort by rating_count descending

- 7️⃣ Products with ≥ 50% discount =COUNTIF(discount_percentage, ">=50")

- 8️⃣ Rating distribution PivotTable: Rows = rating, Values = Count of product_name

- 9️⃣ Potential revenue by category =actual_price * rating_count, then sum by category

- 🔟 Product count by price range Use IF or IFS to bucket prices, then count

- 1️⃣ Rating vs. Discount Scatter plot: X = discount %, Y = rating + trendline

- 2️⃣ Products with < 1,000 reviews =COUNTIF(rating_count, "<1000")

- 3️⃣ Categories with highest discounts PivotTable: MAX(discount_percentage) by category

- 4️⃣ Top 5 products by rating × reviews Create a new column: rating * rating_count, then sort descending

## 💡 Recommended Strategies
- Focus marketing on high-rated, low-review products to boost visibility
- Offer targeted discounts in underperforming categories
- Bundle top-rated products with low-selling items
- Use customer feedback to improve product descriptions and quality
- Prioritize logistics for high-potential products based on review volume and ratings.

  
## 📊 Final Task: Dashboard Creation
Using the cleaned dataset and pivot outputs, a dynamic Excel dashboard was created featuring:

## 📌 KPI Cards: Total Products, Avg Rating, Total Reviews, Products with ≥ 50% Discount
- 📈 Charts: Rating Distribution, Top Products by Reviews, Discount vs. Rating
- 🎯 Slicers: Filter by Category and Price Range
- 📊 PivotTables: Category-level summaries and product-level insights.
The dashboard is designed to be interactive, visually clean, and decision-focused.

## ✅ Conclusion
This project demonstrates how Excel can be used to transform raw e-commerce data into actionable insights. From identifying top-performing products to understanding customer sentiment, the analysis supports data-driven decisions for product strategy, marketing, and customer engagement. 📫 Contact For questions or collaborations: 📧 Email: [commyjohn700@gmail.com]
