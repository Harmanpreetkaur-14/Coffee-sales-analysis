 ☕ Coffee Sales Analysis (EDA Project)

This project performs Exploratory Data Analysis (EDA) on daily coffee sales from a vending machine between March 2024 and July 2025. The goal is to uncover customer behavior patterns, sales trends, and key business insights to support smarter inventory and marketing decisions.

📁 Dataset Description

- Source: Vending machine transaction logs  
- Time Period: March 2024 – Present  
- Columns:
  - `date` – Transaction date  
  - `datetime` – Timestamp of the order  
  - `cash_type` – Payment method (`cash` or `card`)  
  - `card` – Card transaction details (if applicable)  
  - `money` – Revenue per order  
  - `coffee_name` – Type of coffee ordered  



🔍 Key Analysis Performed

- ✅ Missing value treatment & data cleaning  
- ✅ Conversion of date and time into meaningful features (hour, weekday, month)  
- ✅ Coffee popularity percentage  
- ✅ Payment method breakdown  
- ✅ Average orders per day and total revenue  
- ✅ Heatmap of order volume by **day of week and hour**  
- ✅ Monthly revenue trend  
- ✅ KPI metrics like AOV (Average Order Value), peak hours, and more


 📈 Visualizations Included

- Bar plots of coffee popularity  
- Line and bar plots of monthly revenue  
- Heatmap of order frequency by hour and day  
- Pie chart of revenue by payment method  



🛠️ Tools & Libraries Used

- Python  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook



📌 Conclusion

This analysis helps understand when and how customers purchase coffee, which products are most profitable, and how payment trends are shifting. These insights can be used to:
- Optimize restocking and inventory
- Offer targeted promotions
- Improve customer experience



