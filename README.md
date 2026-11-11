# Amazon India Sales Dashboard (Excel)

An interactive Excel dashboard that gives a non-technical manager a one-page view of sales, profit, products, order status, payments, fulfilment and state-wise performance for Amazon India orders. Built as a project for the **Sapphire IQ Data Analytics Internship**.

## Business Problem

Manoj needs to submit a performance report to his manager, Ravi, who has no technical background. The raw order data is too large to read directly, so the goal was a single dashboard that answers four questions in plain language, using simple KPIs and charts.

## Dataset

- **Size:** 10,000 orders, 1 Jan 2024 to 30 Aug 2026
- **Scope:** 5 categories, 25 products, 10 ship-to states
- **Key fields:** Order Date, Category, Product, Quantity, Unit Price (INR), Discount %, Total Sales (INR), Profit (INR), Payment Method, Fulfilment, Order Status, Ship State

## Objectives

1. **Overall sales and profit:** total sales, profit, orders, units sold, average order value, profit margin and monthly trend
2. **Category and product performance:** sales, profit and units by category, top 10 products, and products needing attention
3. **Order status and revenue loss:** delivered, shipped, returned and cancelled orders, return and cancellation rates, and the revenue lost to them
4. **Payment, fulfilment and geography:** sales and profit by payment method, fulfilment method and state

## Key Findings

- **Overall:** Sales of ₹15.58 Cr and profit of ₹3.32 Cr, a **21.3% profit margin**
- **Trend:** The latest 6 months average ₹53.5 lakh a month, **up 13.9%** on the previous 6 months (+7.5% sales and +9.6% profit versus the same months last year)
- **Concentration risk:** Electronics & Mobiles generates **79.3% of sales and 79.3% of profit**. Laptop Backpack alone is 17.0% of sales, and the top 5 products make up 79.3% of sales
- **Needs attention:** Filter Coffee Powder and Assorted Dry Fruits 500g have the lowest sales (about ₹2.5 lakh and ₹2.9 lakh)
- **Revenue loss:** 81.5% of orders were delivered and 8.7% are still in transit. Returns (4.9%) and cancellations (5.0%) lose **₹156.5 lakh, or 10.0% of sales**
- **Where losses sit:** Electronics & Mobiles has the highest return rate (5.4%) and Apparel & Fashion the highest cancellation rate (5.7%)
- **Channels:** UPI accounts for 50.4% of sales and Amazon FBA for 69.0%
- **Markets:** Maharashtra is the top state at 19.0% of sales, followed by Karnataka and Delhi

## Dashboard Features

- Year selector that updates every KPI and chart
- KPI cards for sales, profit, orders, units, average order value and margin
- Monthly sales and profit trend
- Category, product, payment, fulfilment and state-wise charts
- Order status breakdown with return and cancellation rates
- Auto-updating written insight under each section

## Data Notes

- Total sales and orders include every order as recorded. Returned and cancelled orders are shown as lost sales in the order status section.
- Profit is recorded only for Delivered and Shipped orders in the source data.
- Amounts are in Indian rupees (₹ L = lakh, ₹ Cr = crore).

## Workbook Structure

| Sheet | Purpose |
| --- | --- |
| Dashboard | Management view with year filter, KPIs, charts and insights |
| Sales_Profit | Calculations for overall sales and profit |
| Category_Product | Category and product tables |
| Order_Status | Order status, return and cancellation analysis |
| Pay_Fulfil_Geo | Payment, fulfilment and state-wise tables |
| Data | Source data (10,000 orders) |

## Tools

Microsoft Excel: formulas (SUMIFS, COUNTIFS, COUNTIF), data validation dropdown, charts and KPI cards.

## Files

- [Amazon_India_Dashboard.xlsx](Amazon_India_Dashboard.xlsx): full workbook with dashboard and analysis sheets
- [Amazon_India_Dashboard_Sapphire_IQ.pdf](Amazon_India_Dashboard_Sapphire_IQ.pdf): original project brief from Sapphire IQ
- [Amazon_Sales_Data_India.xlsx](Amazon_Sales_Data_India.xlsx): original dataset

## Author

**Anmol Kumar**, Data Analyst
[LinkedIn](https://www.linkedin.com/in/anmol-kumar-245493425) | [Portfolio](https://anmolswebiste.lovable.app)
