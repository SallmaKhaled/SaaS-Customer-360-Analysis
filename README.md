# SaaS Customer 360 Analysis

## 📌 Project Overview

This project uses Python to clean, validate, combine, and analyze SaaS customer data to build a **Customer 360 analytical dataset**.

The analysis integrates customer, subscription, transaction, marketing, campaign interaction, and support-ticket data to provide a consolidated view of customer activity and business performance.

## 🎯 Objectives

- Load and inspect multiple SaaS datasets.
- Clean and standardize customer and business data.
- Handle missing values and duplicate records.
- Parse mixed date formats and convert financial fields to numeric values.
- Combine quarterly transaction data.
- Create customer-level analytical metrics.
- Calculate key business KPIs.
- Answer important business questions.
- Visualize revenue, subscriptions, customer performance, and support metrics.
- Produce a final `customer360.csv` dataset.

## 🗂️ Data Sources

The project works with the following datasets:

- `customers.csv`
- `subscriptions.csv`
- `campaign_interactions.csv`
- `marketing_campaigns.csv`
- `support_tickets.csv`
- `transactions_q1.csv`
- `transactions_q2.csv`
- `transactions_q3.csv`
- `transactions_q4.csv`

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – data cleaning, transformation, aggregation, and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – visualization support
- **Jupyter Notebook**

## 🔄 Analysis Workflow

1. Load and inspect all datasets.
2. Standardize text fields and categorical values.
3. Convert dates into consistent datetime formats.
4. Convert monetary and percentage fields into numeric values.
5. Identify and handle duplicate records.
6. Validate missing values and data integrity.
7. Combine the four quarterly transaction datasets.
8. Aggregate transactions, subscriptions, support tickets, and marketing interactions at customer level.
9. Merge the datasets into a unified **Customer 360** dataset.
10. Calculate business KPIs.
11. Answer eight business questions.
12. Create analytical visualizations.
13. Export the final `customer360.csv` dataset.

## 📊 Key KPIs

The notebook calculates:

- Total Customers
- Active Customers
- Gross Revenue
- Refunds
- Net Revenue
- Average Positive Transaction
- Active Subscription Rate
- Average Support Resolution Hours
- Average Support Satisfaction
- Campaign Interaction Conversion Rate
- Average Net Revenue per Customer
- Active Subscription Penetration

## ❓ Business Questions

The analysis answers eight key business questions:

1. Which quarter generated the most net revenue?
2. Which payment method is used most?
3. Which subscription plan has the highest average monthly fee?
4. Which country has the highest net revenue?
5. Which plan has the largest subscriber base?
6. Which support category has the longest average resolution time?
7. Which customer generated the highest net revenue?
8. Which account-status segment has the highest average net revenue?

## 📈 Visualizations

The notebook includes visualizations for:

- Net Revenue by Quarter
- Gross Revenue by Transaction Type
- Subscription Count by Plan
- Top Countries by Net Revenue
- Average Support Resolution Time by Category
- Customer Net Revenue Distribution

## 🔍 Key Findings

- **Q3** generated the highest net revenue, at approximately **$371,618**.
- **Upgrade** transactions generated the largest share of gross revenue.
- **Singapore** generated the highest total customer net revenue, at approximately **$85,272**.
- The **Enterprise** plan had the highest average monthly fee, at approximately **$817.07**.
- **Security** had the longest average support resolution time, at approximately **206.4 hours**.

## 💡 Recommendations

Based on the analysis:

- Prioritize high-value customers with active subscriptions for retention and proactive support.
- Investigate the factors contributing to the strong Q3 revenue performance.
- Maintain an ongoing Customer 360 view combining revenue, subscription, marketing engagement, and support information.

## 📁 Output

The final customer-level analytical dataset is exported as:

`customer360.csv`

This dataset combines customer information with transaction, subscription, support, and marketing interaction metrics for further analysis or dashboard development.

## 👩‍💻 Author

**Salma Khaled**

Data Analysis Portfolio Project
