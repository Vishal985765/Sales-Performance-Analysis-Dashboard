🛍️ Store Sales Performance Analysis — Microsoft Excel

A dynamic Excel dashboard analyzing 1,000 gift-store orders to track revenue, seasonality, and category performance.


📌 Problem Statement

An occasion-based gifting store (cakes, plants, sweets, soft toys, etc.) had three years' worth of order data spread across separate customer, product, and order records with no consolidated view. The business couldn't easily answer:


Which product categories and occasions actually generate the most revenue?
Are there seasonal peaks the business should staff and stock for in advance?
How long does it typically take between an order being placed and delivered?
Which cities have the highest order volume, and who are the customers driving it?


Recomputing these answers manually every month was time-consuming and not repeatable.

✅ Solution

Built a Power Query + Pivot Table driven Excel dashboard:


Data cleaning: Consolidated Customers, Products, and Orders (100 customers, 70 products, 1,000 orders) into clean, related tables using Power Query.
Pivot analysis: Built pivot tables summarizing revenue by month, category, occasion, and city, plus average order-to-delivery time.
Dashboard: Added slicers and KPI cards on a dedicated Dashboard sheet so any team member can filter by month, occasion, or category without editing formulas.
Automation: Power Query refresh means the entire dashboard updates in one click when new order data is dropped into the source sheets.


🗂️ Dataset

SheetContentsCustomer100 customers — ID, name, city, contact, email, gender, addressProducts70 products — ID, name, category, price, associated occasionOrders1,000 orders — customer, product, quantity, order/delivery timestamps, location, occasion, revenuePivot Table / DashboardAggregated views and interactive visuals

Categories: Cake, Colors, Plants, Raksha Bandhan, Sweets, Soft Toys, Mugs
Occasions: Anniversary, Birthday, Diwali, Holi, Raksha Bandhan, Valentine's Day, All Occasions

📊 Key Insights


Total revenue: ₹35.2 lakh across 1,000 orders (avg. order value ≈ ₹3,521).
Top categories: Colors, Soft Toys, and Sweets together account for roughly 60% of total revenue.
Seasonality: August and February are the strongest revenue months — useful for pre-season inventory planning.
Occasion performance: Anniversary and Raksha Bandhan orders generate the highest revenue per occasion.
Delivery: Average order-to-delivery time is 5.5 days.


🛠️ Tools Used

Microsoft Excel · Power Query · Pivot Tables · Slicers · KPI Cards

📁 File

Sales_Performance_Analysis.xlsx — open in Excel; refresh Power Query if source data changes.
