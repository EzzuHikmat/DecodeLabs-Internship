# 🛒 E-Commerce EDA Report

An Exploratory Data Analysis (EDA) of an e-commerce order dataset containing **1,200 transactions** spanning January 2023 to June 2025.

## 📁 File

`EDA_Report.xlsx` — A fully formatted Excel workbook with 5 analytical sheets.

## 📊 What's Inside

| Sheet | Contents |
|-------|----------|
| **Overview** | KPIs, descriptive statistics, data quality summary |
| **Product Analysis** | Revenue & order breakdown by product, cross-tab with order status, bar chart |
| **Order Status & Trends** | Status distribution, monthly revenue trend (MoM), trend chart |
| **Customer & Marketing** | Payment methods, referral sources, coupon code usage |
| **Outliers & Insights** | IQR-based outlier detection, price distribution buckets, key observations |

## 🔑 Key Findings

- **41.4%** of orders were either Cancelled or Returned
- **74.25%** of customers used a coupon code — shipping fee sensitivity is high
- **June** consistently peaks in monthly revenue across all years
- **Instagram** is the top acquisition channel at 21.6% of orders
- Average order value: **$1,053.97** with a std dev of $819.86
- Only **8 outlier orders** (0.67%) detected via IQR method

## 🗂️ Dataset Columns

`OrderID`, `Date`, `CustomerID`, `Product`, `Quantity`, `UnitPrice`,
`ShippingAddress`, `PaymentMethod`, `OrderStatus`, `TrackingNumber`,
`ItemsInCart`, `CouponCode`, `ReferralSource`, `TotalPrice`

## 🛠️ Tools Used

- **Python** (pandas, openpyxl) — data analysis & Excel generation
- **Excel** — formatted output with charts and conditional styling

## 📌 Goals

- Calculate basic statistics (mean, median, count)
- Identify trends and outliers
- Summarize key business observations
