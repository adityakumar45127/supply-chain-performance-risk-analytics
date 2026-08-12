# 📊 Supply Chain Performance & Risk Analytics

> Interactive Power BI dashboard for analyzing supply chain performance, profitability, operational risk, lead times, supplier performance, and product quality.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-5E5E5E?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Analytics-0078D4?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-0A66C2?style=for-the-badge)

---

## 🎯 Project Overview

This project is an interactive **Supply Chain Performance & Risk Analytics dashboard** developed using Microsoft Power BI.

The dashboard transforms supply chain data into meaningful business insights across:

- Revenue
- Gross Profit
- Total Cost
- Profit Margin
- Orders
- Suppliers
- Locations
- Product Types
- Quality Risk
- Lead-Time Risk
- Defect Rate

The project contains two analytical pages:

**Page 1 — Supply Chain Performance**

**Page 2 — Risk Analysis**

---

## 💼 Business Problem

Supply chain operations involve multiple interconnected factors including financial performance, supplier activity, product quality, order volume, and delivery lead times.

This dashboard provides a centralized analytical view to help answer:

- What is the overall revenue and profitability?
- Which product types generate the most revenue?
- Which locations contribute the most revenue?
- Which suppliers generate significant revenue?
- How are orders distributed across quality-risk levels?
- How many orders have high lead-time risk?
- What is the average lead time?
- Which product types have higher defect rates?

---

# 📈 Page 1 — Supply Chain Performance

### KPIs

- 💰 Total Revenue
- 📈 Gross Profit
- 💵 Total Cost
- 📊 Profit Margin %

### Visualizations

- Total Revenue by Product Type
- Total Revenue by Location
- Total Revenue by Supplier
- Total Orders by Quality Risk
- Total Orders by Lead-Time Risk

### Filters

- Location
- Product Type

---

# ⚠️ Page 2 — Risk Analysis

### Risk KPIs

- ⚠️ High Quality Risk Orders
- 🚚 High Lead-Time Risk Orders
- ⏱️ Average Lead Time

### Visualizations

- Total Orders by Quality Risk
- Total Orders by Lead-Time Risk
- Total Orders by Supplier
- Average Defect Rate by Product Type

---

# 🧮 DAX Measures

### Total Revenue

```DAX
Total Revenue =
SUM('Supply_Chain_Performance_Risk_Dataset'[Revenue])
