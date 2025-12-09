# amazon-diwali-sales-2025-analysis
An end-to-end analysis and visualization of Amazon Diwali 2025 sales data, featuring performance metrics, delivery tracking, product insights, and revenue trends
Technical Report on Amazon-Diwali-Sales-2024-Analysis

<img width="1314" height="541" alt="Dashboard of amazon-diwali-sales-2025-analysis" src="https://github.com/user-attachments/assets/49f369ce-8c86-4626-9b3a-2fb7d6bc6349" />
<img width="1314" height="541" alt="s d 9" src="https://github.com/user-attachments/assets/f3169e1a-658d-4f8d-bc0d-81d08fad0d41" />

Introduction
This report summarizes an analysis of Amazon — Diwali Product Sales for 2025. The dataset (downloaded from Kaggle) was cleaned and analyzed in Excel, and the results are presented as a dashboard (screenshot provided). The goal of this work was to turn raw order-level data into actionable insights about sales, customer behavior, delivery performance and top products during the Diwali/festival period.
The Story of the Data
The dataset contains transactional records for Amazon’s Diwali / festival-season sales in 2025. Each row corresponds to an order or an item line and includes attributes used in this analysis such as date (month), product, product category, payment method, order status (delivered/pending/returned), revenue, quantity and basic customer information. From this raw data we derived high-level KPIs (Total Sales, Customers, Order Success, Quantity Sold), monthly sales trend, revenue by category and payment method, delivery-performance metrics and the top selling products.
Methodology
The dataset downloaded from Kaggle was cleaned in Excel by removing duplicates, standardizing fields, handling missing values, creating helper columns, and then analyzed using PivotTables and formulas to generate aggregated metrics and visualizations for the final dashboard.
Data Breakdown
1.	Overall Performance: Total sales reached ₹1,118.16M, with 24,955 customers, 5,075 successful orders, and 44,770 items sold.
2.	Delivery Status: Orders were distributed as 5,075 delivered, 5,044 pending, and 4,881 returned, showing significant fulfilment and return activity.
3.	Category Revenue: The highest-earning categories were Beauty, Electronics, Books, Clothing, and Home & Kitchen, each generating over ₹216M.
4.	Payment Methods: Credit Card and Cash on Delivery led revenue generation at about ₹286M each, followed by Debit Card and UPI.
5.	Top Products: Items such as Lipstick, Children’s Books, Headphones, Hair Dryers, and Perfume ranked among the best sellers.
6.	Monthly Performance: Sales trended steadily across the year with noticeable peaks in May, Aug, and December.
Pre-Analysis: What I Explored
· Best product categories by highest total sales (INR)
· What is the average quantity purchased per product category
· Best Performing product names by unit price
· Top-selling products in each state
· How do product reviews (positive or negative) correlate with total sales
· Which payment method is most commonly used by customers in each state
· What is the average total sale per order for each payment method
· How does the delivery status affect customer reviews
· Best product category by overall revenue
· How does pricing (unit price) vary between product categories
· What is the average revenue per product and per order
Potential Insights
· Fine-tune product pricing by offering small discounts on high-value items to encourage higher sales volumes without hurting profit margins
· Fine-tune category focus by prioritizing best-selling products such as electronics and home décor during festive campaigns
· Fine-tune customer targeting by segmenting customers by state and tailoring product recommendations to local preferences
· Fine-tune product listings with more detailed images, specifications, and keyword-optimized titles to increase conversion rates
· Fine-tune review monitoring to quickly address negative feedback and improve product credibility.
· Fine-tune loyalty programs to reward repeat customers who consistently contribute to higher total sales
· Fine-tune regional marketing campaigns to strengthen presence in Tier-2 and Tier-3 cities showing fast growth.
· Fine-tune sales tracking dashboards to identify top-performing sellers and underperforming product lines
· Fine-tune unit pricing models using competitor benchmarking and customer affordability analysis
· Fine-tune promotional timing by aligning flash sales with peak festive shopping days to maximize revenue
· Fine-tune upselling and cross-selling tactics to increase average order value during checkout
In Analysis Observation
· Lipstick topped the chart with total sales of ₹48,159,020.15, making it the best-performing product overall
· Credit Card payments generated the highest revenue of ₹286.89 million, making it the most preferred method among customers
· Delivered orders lead with 5,075 deliveries, showing that most orders were successfully completed
· Beauty products led the chart with ₹227.49 million, showing strong customer demand for personal care and cosmetics
· Sikkim recorded the highest sales with ₹43,113,469.51, making it the top-performing state regionally
· August recorded the highest sales at ₹97.58 million, showing peak performance possibly driven by seasonal promotions or festive demand
Data Visualization
The dashboard organizes the analysis into visually distinct widgets:
1. Top KPI tiles (Total Sales, Customers, Order Success, Quantity Sold): give an instant sense of scale and core health metrics.
2. Delivery performance donut chart: highlights an unexpectedly high count of pending and returned orders relative to delivered orders — suggests operational strain or refund/return patterns during the sale. This flags a logistics / returns investigation.
3. Sales performance bar chart (by category): Beauty, Electronics and Books are almost equal in revenue — showing a broad, multi-category demand rather than a single-category spike. Useful for inventory planning and ad-budget allocation.
4. Revenue by payment method (vertical bar chart): Credit Card and Cash on Delivery are the largest contributors, nearly tied — indicating strong COD persistence in festival sales and also healthy digital payments. Payment method distribution informs payment-gateway partnerships and fraud-monitoring priorities.
5. Top selling products (horizontal bar chart): Mix of low-ticket (lipstick, books) and higher-ticket (laptop, air fryer) items among top sellers — indicates conversion across price bands and cross-category promotional effectiveness.
6. Monthly trend line: Shows a seasonal uplift in several months (May, Jul, Dec) and a dip in August. The trend helps forecast inventory needs for future festival windows.
Conclusion
The analysis shows strong overall sales performance across diverse categories, a heavy reliance on both credit card and COD payments, unusually high pending and returned orders that require operational review, and clear monthly peaks that can guide future inventory and marketing strategies.
Reference
Source: Kaggle — https://www.kaggle.com/datasets/anandshaw2001/amazon-product-sales-2025
Microsoft Excel — data cleaning, aggregation (PivotTables) and dashboard creation.


