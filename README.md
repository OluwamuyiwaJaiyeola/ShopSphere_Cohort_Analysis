# ShopSphere Cohort Analysis

**By Oluwamuyiwa Jaiyeola**

A data-driven analysis of customer retention and purchasing behaviour in an e-commerce environment using Cohort Analysis and RFM Segmentation.
The goal of this project is to identify customer engagement patterns and translate analytical insights into actionable retention strategies.

---

## Business Problem

E-commerce businesses often struggle to understand how customer engagement evolves after the first purchase. Without clear retention insights, companies risk losing valuable customers and misallocating marketing resources.

This project analyses historical transaction data to answer key questions:

– **How does customer engagement change after the first purchase?**

– **Which customer groups generate the most value?**

– **Which customers are at risk of churn?**

– **How can businesses design targeted retention strategies?**

---

## Dataset Overview

The analysis uses the ShopSphere e-commerce transaction dataset.

**Dataset scale:**

– 385,314 transaction records

– 20,990 unique orders

– 4,372 unique customers

**Key variables include:**

– Invoice number and purchase date

– Product identifiers and descriptions

– Quantity purchased

– Unit price

– Customer ID

– Country of purchase

---

## Analytical Approach

The project combines customer retention analysis and behavioural segmentation.

**1. Cohort Analysis**

Customers are grouped by the month of their first purchase and tracked over time.

This helps identify:

– Customer retention patterns

– Engagement decline over time

– Lifecycle behaviour after acquisition

The results are visualised using a Cohort Retention Heatmap.

**2. RFM Segmentation**

Customers are segmented using Recency, Frequency, and Monetary (RFM) metrics.

These metrics measure:

– Recency: how recently a customer purchased

– Frequency: how often they purchase

– Monetary: total spending value

K-Means clustering is then applied to identify distinct behavioural segments.

---

## Key Insights

The analysis identified four primary customer segments.

**V-VIPs (Top Spenders)**

– Low recency and high purchase frequency

– Highest spending behaviour

– Best retained customers

**Recommended action:**
Maintain loyalty with exclusive rewards and premium experiences.

**VIPs (Consistent Buyers)**

– High purchase frequency

– Reliable repeat customers

**Recommended action:**
Encourage continued engagement through targeted promotions.

**Loyal Regulars**

– Moderate purchase activity

– Consistent but lower spending behaviour

**Recommended action:**
Increase purchase frequency with loyalty incentives.

**At-Risk / Lost Customers**

– Long time since last purchase

– Previously active but now disengaged

**Recommended action:**
Deploy targeted win-back campaigns.

---

## Business Recommendations

Based on the segmentation analysis, companies can improve customer lifetime value through targeted strategies:

– Reward V-VIP customers with premium loyalty programmes.

– Encourage VIP customers with personalised purchase incentives.

– Increase engagement among Loyal Regulars through reward programmes.

– Reactivate At-Risk customers with targeted win-back campaigns.

---

## Tools Used
The analysis was conducted using the following tools:

**Python**, **Jupyter Notebook**, **Pandas**, **Matplotlib**, **Seaborn**, **Scikit-Learn**, **Yellowbrick**, **Git**, **GitHub**

---

## Repository Structure

**My_Cohort_Analysis.ipynb**

Main notebook containing the full cohort and RFM analysis.

**ShopSphere_Dataset.csv**

Transaction dataset used for analysis.

**COHORT_ANALYSIS.pptx**

Presentation slides summarising key findings and insights.

**README.md**

Project documentation.

---

## How to Run the Project

**Clone the repository**

git clone https://github.com/oluwamuyiwajaiyeola/ShopSphere_Cohort_Analysis.git

**Install required libraries**

pip install pandas numpy matplotlib seaborn scikit-learn yellowbrick

**Open the notebook**

My_Cohort_Analysis.ipynb

**Run the cells sequentially to reproduce the analysis.**

---

## Project Outcome

This project demonstrates how customer behavioural analytics can help businesses:

– understand retention patterns

– identify high-value customers

– detect churn risk

– design targeted marketing strategies

Such insights allow organisations to make data-driven decisions that improve customer lifetime value (CLV).

---

**jaiyeolaoluwamuyiwa1@gmail.com**
