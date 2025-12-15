# Clickstream E‑Commerce Analytics Dashboard

## 📌 Project Overview

This project focuses on analyzing **clickstream data from an e‑commerce platform** to understand user behavior, sessions, devices, and purchasing patterns. The analysis is visualized using an **interactive Power BI dashboard** that helps stakeholders make data‑driven decisions.

The dataset follows a **star schema** design with fact and dimension tables, enabling efficient analytical queries and reporting.

---

## 🧠 Objectives

* Analyze user navigation and engagement behavior
* Track sessions, devices, and user activity
* Understand product performance and order trends
* Identify conversion patterns from web events to orders
* Build an interactive and insightful Power BI dashboard

---

## 🗂️ Project Structure

```
📁 clickstream-ecommerce-dashboard
│
├── 📊 click stream e commerce dashboard final1.pbix
│
├── 📁 data
│   ├── dDate_clickstream.csv
│   ├── dDevice_clickstream.csv
│   ├── dProduct_clickstream.csv
│   ├── dSession_clickstream.csv
│   ├── dUser_clickstream.csv
│   ├── fOrders_clickstream.csv
│   └── fWebEvents_clickstream.csv
│
└── README.md
```

---

## 🧱 Data Model

### Fact Tables

* **fWebEvents_clickstream** – Records user web interactions (page views, clicks, etc.)
* **fOrders_clickstream** – Contains order and transaction details

### Dimension Tables

* **dUser_clickstream** – User information
* **dSession_clickstream** – Session‑level details
* **dDevice_clickstream** – Device and platform data
* **dProduct_clickstream** – Product metadata
* **dDate_clickstream** – Date and time attributes

---

## 📊 Dashboard Features

* User & session analysis
* Device and platform insights
* Funnel analysis from visits to purchases
* Product‑level performance
* Time‑based trends (daily, monthly)
* Interactive filters and slicers

---

## 🛠️ Tools & Technologies

* **Power BI** – Data modeling and dashboard creation
* **CSV Files** – Source data
* **Star Schema Modeling** – Analytical efficiency

---

## 🚀 How to Use

1. Clone this repository
2. Open `click stream e commerce dashboard final1.pbix` in **Power BI Desktop**
3. Ensure CSV files are correctly mapped if prompted
4. Refresh data and explore the dashboard

---

## 📈 Insights You Can Derive

* Which devices generate the highest conversions
* User drop‑off points in the browsing journey
* Best‑performing products
* Peak traffic and sales periods

---

## 📌 Future Enhancements

* Add real‑time data integration
* Include customer segmentation
* Advanced funnel and cohort analysis
* Deploy dashboard to Power BI Service

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

