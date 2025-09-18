# Customer_Segmentation_Using_RFM_Analysis

**Customer Segmentation Using RFM Analysis**
This project applies RFM (Recency, Frequency, Monetary) analysis on the Online Retail dataset (UCI)
to understand customer behavior and segment them into groups for targeted marketing.

** What is RFM?**

Recency (R): How recently a customer made a purchase

Frequency (F): How often a customer purchased

Monetary (M): How much money a customer spent

**Steps Performed**

Loaded and cleaned the dataset (removed missing values, cancellations).

Created new features:

TotalPrice = Quantity × UnitPrice

Converted InvoiceDate to datetime format.

Calculated RFM metrics for each customer.

Assigned R, F, M scores (1–5) using quantiles.

Built combined RFM scores and grouped customers into segments:

Champions

Loyal Customers

Potential Loyalists

New/Promising Customers

At Risk

Lost Customers

Suggested marketing strategies for each group.

Visualized results with:

Bar chart (customer count per segment)

Heatmap (average spend across R and F scores)

Exported the final RFM table as CSV.

**Tools & Libraries**

Python

Pandas

Matplotlib & Seaborn

Google Colab

**Insights & Marketing Ideas**

Champions: Reward with exclusive offers and early access.

Loyal Customers: Encourage repeat purchases through loyalty programs.

Potential Loyalists: Nurture with personalized recommendations.

At Risk: Win back with discounts or surveys.

Lost Customers: Try re-engagement campaigns.
