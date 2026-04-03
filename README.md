# E-Commerce Sales Analysis
EDA Project (Excel+Power Query)
## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Brazilian E-Commerce Public Dataset to uncover key business insights related to sales performance,customer behavior, product trends, and delivery efficiency.
An interactive Excel dashboard was built to visualize key metrics and support data-driven decision-making.
## Objectives
- Analyze overall revenue and order trends
- Identify top-performing product categories and regions
- Understand customer purchasing behavior
- Evaluate delivery performance and operational efficiency
## Dataset
- Source: Brazilian E-Commerce Public Dataset (Olist)
- Includes nine tables: orders, products, sellers, customers, order_items, order_payments, order_reviews, geolocation, product_category_translation
- Data was merged into a master table for analysis
## Tools & Techniques
- Microsoft Excel
- Power Query (Data Cleaning & Merging)
- Pivot Tables & Pivot Charts
- Data Transforming & Feature Engineering
- Dashborad Design & Visualization
## Data Preparation
- Merge 9 datasets into a single table
- Handle missing values (delivery status, categories)
- Extracted date, month, and hour from timestamps
- Create calculated fields: Delivery Status, Delivery Duration
## Dashboard Features
### KPIS
- Total Revenue
- Total Orders
- Average Order Value
- Average Delivery Duration
### Visualizations
- Monthly Revenue Trend
- Top 10 Catergories
- Top 10 States
- Delivery Time Distribution
- Peak Shopping Hour
### Interactive Filters/Slicers
- Year
- Month
- Category
- State
- Delivery Status
## Key Insights
- Although 2018 contains only nine months of data, it surpasses the total revenue of the full year 2017, suggesting a substaintial increase in average monthly revenue and overall business growth
- Health Beauty category leads in revenue contribution, suggesting high demand and customer preference, making it a critical segment for maintaining and growing overall business performance
- As the leading revenue-generating state, Sao Paulo represents a core market, highlighting opportunities for targeted marketing, logistics optimization, and customer retention strategies in this state.
- While the majority of deliveries are completed within a reasonable timeframe, the presence of significantly delayed orders and a notable number of undelivered or pending orders suggests inconsistencies in the delivery process that may impact customer satisfaction
- Peak shopping activity occurs between 12:00 and 23:00, highlighting a strong preference for afternoon and evening purchases, which presents an opprtunity to optimize marketing campaigns and promotions during these high-traffic hours
## Conclusion
The analysis highlights strong growth trends, key revenue-driving categories, and regional performance differences, while also identifying elivery ineficiencies that may impact customer satisfaction.
## Files Included
- E-commerce Sales Analysis(Pivot,Dashboard).xlsx
- Screenshots of Dashboard
## Future Improvements
- Build Power BI interactive dashboard
- Add predictive analysis
- Perform customer segmentation
