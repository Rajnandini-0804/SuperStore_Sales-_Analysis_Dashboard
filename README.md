# SuperStore_Sales-_Analysis_Dashboard
This project is a Power BI dashboard created using the Superstore Sales Dataset. It provides insights into sales, profit, quantity, shipping time, category performance, regional performance, and customer behavior.


## ✅ Key Insights from Dashboard
- Total Sales, Profit & Quantity Overview  
- Region-wise Sales & Profit comparison  
- Monthly Sales Trend (Time Series)  
- Top & Bottom Product Categories  
- Average Shipping Days Calculation using DAX  
- Customer Segment Analysis  
- Profitability across different states

---

## 🔧 Tools & Technologies Used
| Tool / Tech | Purpose |
|-------------|----------|
| Power BI Desktop | Dashboard & Visualization |
| DAX | Calculated Columns & Measures |
| Data Cleaning | Power Query Editor |
| CSV / Excel | Source Dataset Format |

---

## 📌 DAX Example Used in Project

```DAX
AvgDeliveryDays = DATEDIFF(
    'SuperStore_Sales_Dataset'[Order Date],
    'SuperStore_Sales_Dataset'[Ship Date],
    DAY
)
🏁 Project Goal

The main objective of this dashboard is to help businesses:

Identify profit-driving categories

Monitor regional performance

Reduce shipping delays

Improve sales strategies using data insights

👩‍💻 Author

Rajnandini Bhosale
Data Analytics Enthusiast | Power BI Learner
