#Food Delivery Data Integration & Analysis
#Project Overview
This project shows a real-world data engineering and analytics workflow by
integrating data from multiple sources and formats into a single dataset.

#Data Sources used
- orders.csv – Transactional order data
- users.json – User master data
- restaurants.sql – Restaurant master data (SQL)

#Data Integration Logic
- orders.user_id → users.user_id
- orders.restaurant_id → restaurants.restaurant_id
- Join Type: LEFT JOIN (to retain all orders)

#Output
- final_food_delivery_dataset.csv

#Tech Stack
- Python
- Pandas
- SQLite
- Jupyter Notebook

#Key Learning Outcomes
- Multi-format data handling (CSV, JSON, SQL)
- Real-world joins and data modeling
- Business-driven data analysis
