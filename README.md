# Pizza_sales_Dashboard-
# 🍕 Pizza Sales and Order Analysis Dashboard

This Power BI project analyzes pizza sales and order trends using a simulated dataset. The dashboard provides key insights into sales performance, customer ordering behavior, and best-selling pizza categories.

---

## 🎯 Objectives

* Analyze overall pizza sales and customer order patterns
* Identify peak hours, days, and time segments for orders
* Determine best-performing pizza categories, sizes, and types
* Calculate total revenue and top revenue-generating items
* Provide interactive visuals for business decision-making

---

## 📊 Dashboard Features

* **Total Orders & Revenue** (KPI Cards)
* **Orders by Hour and Day of Week**
* **Sales by Pizza Category and Size**
* **Most Ordered & Highest Revenue Pizzas**
* **Sales by Daytime (Morning, Afternoon, Evening, Night)**
* **Interactive Slicers** for time, category, and pizza size

---

## 📁 Dataset Overview

The project uses four CSV files:

| File Name           | Description                                     |
| ------------------- | ----------------------------------------------- |
| `orders.csv`        | Contains order timestamps                       |
| `order_details.csv` | Contains pizza IDs and quantities , pizza sales |
| `pizzas.csv`        | Maps pizza IDs to types , size and prices       |
| `pizza_types.csv`   | Contains pizza names, categories, etc.          |

---

## 🔗 Relationships Between Tables

* `order_details[pizza_id]` → `pizzas[pizza_id]`
* `pizzas[pizza_type_id]` → `pizza_types[pizza_type_id]`
* `orders[order_id]` → `order_details[order_id]`

---

## 📈 Key Insights

* 🍕 **Total Orders:** 21,350
* 💰 **Total Sales:** \$817,860.75

- 🍕 **Most Ordered Pizza:** Identified by total quantity
- 💰 **Top Revenue Pizza:** Based on price × quantity
- 🕒 **Peak Order Hours:** Time slots with highest volume
- 📆 **Hot-Selling Days:** Days with maximum sales
- 📦 **Top Category:** Most popular pizza type by orders

---

## 🛠 Tools Used

* **Power BI Desktop**
* **DAX for Measures and Calculations**
* **Power Query for Data Transformation**

---

## 📂 How to Use

1. Clone this repository
2. Open the `.pbix` Power BI file
3. Refresh the data and explore the dashboard

---

## 📸 Preview

![Screenshot 2025-06-16 112731](https://github.com/user-attachments/assets/b4858a0c-1df1-4d0a-adaf-24dfc5dc8976)

---

## 📬 Contact

**Ashish Patel**
`B.Tech IT Student | Data Analytics Enthusiast`
📧 [ ashishpatel19535@gmail.com ]
🌐 [ https://www.linkedin.com/in/ashish-patel-ankit/ ]

---

## ⭐️ If you find this useful, feel free to star the repo and share!
