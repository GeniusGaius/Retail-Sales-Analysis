# Retail-Sales-Analysis
Power BI retail analytics project uncovering trends in customer behavior and sales performance. Insights driven by demographic, seasonal, and product data.

> “Data doesn’t lie—but sometimes, it flirts before revealing the truth.”

This project began with a spreadsheet — but it evolved into a deep dive into customer behavior, purchase trends, and surprising demographic insights.

---

## Business Problem & Project Objective

The goal was to answer critical retail questions:
- Who’s really spending?
- What influences purchase decisions?
- When is the best time to launch promotions?

By answering these questions, the business could better align marketing, inventory, and sales strategy to the actual behavior of its customers.

---

## About the Dataset

The dataset was sourced from a retail analytics case study and provided during training with **Quantum Analytics NG**. It contained anonymized transaction-level data across:
- Product categories (beauty, clothing, electronics)
- Purchase dates
- Customer age groups
- Revenue 
- Transactions
- Date
- Quantity

---

## Data Preparation (Power Query)

Using Power BI’s **Power Query Editor**, the dataset underwent the following transformation steps:

- ** Data Cleaning:** Removed rows with missing or null values in key fields (e.g., revenue, customer age, transaction ID)
- ** Duplicate Handling:** Identified and removed duplicate entries based on unique transaction IDs
- ** Data Correction:** Corrected outliers and invalid entries (e.g., negative revenue)
- ** Data Type Conversion:** Ensured proper data types (e.g., date, numeric, categorical)
- ** Feature Engineering:** Created new columns such as:
  - Age group classification
  - Month and season of transaction
  - High-LTV customer flag

  ## Key Performance Indicators (KPIs)

| KPI | Purpose |
|-----|---------|
|  **Total Sales Revenue** | Measure overall business performance |
|  **Average Revenue per Transaction** | Assess depth of individual purchases |
|  **Product Category Performance** | Identify high- and low-performing segments |
|  **Seasonal Shopping Trends** | Spot patterns in monthly or seasonal demand |
|  **Demographic Spending Behavior** | Understand who your real customers are |
|  **High-LTV Customers** | Focus on your most valuable customer segments |

---

## Key Findings

- **Electronics** generated more revenue than any other category
- **Beauty** was most popular among **Gen Z**
- **Fashion and Tech** were favored by **older generations**
- **Women aged 50+** were the **highest-spending group**
- **May, August, and October** had unexpectedly high sales spikes

---

## Strategic Recommendations

1. **Segment customers by age group** to create detailed buyer personas  
2. **Focus campaigns around high-performing months** (e.g., May, August)  
3. **Double down on customer lifetime value** — prioritize retention  
4. **Bundle products by demographic trends** — tailor offers to different age groups

---

## Final Note

This project demonstrates the value of digging deep into **customer behavior** and letting the data guide **real-world decisions**. Whether you're in retail, marketing, or strategy — knowing **who buys, when, and why** is where the smart money is.

