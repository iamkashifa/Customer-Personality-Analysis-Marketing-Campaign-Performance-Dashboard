# Customer Personality Analysis & Marketing Campaign Performance Dashboard

##  Project Overview

This project features an interactive Power BI dashboard designed to analyze customer behavior and evaluate the performance of marketing campaigns. By segmenting customers based on their demographics, purchasing habits, and responses to previous campaigns, this dashboard provides actionable insights to help businesses tailor their marketing strategies effectively.

The analysis delves into customer profiles, their spending across various product categories, and their engagement with different marketing channels. This type of data-driven approach is crucial for companies, like Apple, that aim to understand their diverse customer base to optimize marketing spend and increase campaign success rates.

*A snapshot of the main dashboard page showcasing key metrics and visualizations.*

---

##  Problem Statement

The primary goal of this analysis is to understand the characteristics and behaviors of different customer segments to improve the effectiveness of future marketing campaigns. The dashboard aims to answer key business questions such as:
* Which customer segments are the most profitable?
* What are the key attributes of customers who respond positively to marketing campaigns?
* Which product categories generate the most revenue?
* How do different purchasing channels (web, store, catalog) perform across customer segments?
* What is the overall success rate of past marketing campaigns, and what can be learned from them?

---

##  Data Source

The dataset for this project consists of two CSV files:

1.  [cite_start]**`marketmindz-research-data.csv`**: This file contains the primary dataset with 29 columns detailing customer demographics, product spending, campaign history, and purchasing behavior[cite: 1, 2, 3, 4, 5, 6].
2.  [cite_start]**`marketmindz-research-data-dictionary.csv`**: This file serves as the data dictionary, providing descriptions for each field in the primary dataset[cite: 7, 8].

---

##  Data Dictionary

The dataset includes the following fields:

| Field | [cite_start]Description [cite: 7, 8] |
| :--- | :--- |
| **ID** | Customer's unique identifier |
| **Year\_Birth** | Customer's birth year |
| **Education** | Customer's education level |
| **Marital\_Status** | Customer's marital status |
| **Income** | Customer's yearly household income |
| **Kidhome** | Number of children in the household |
| **Teenhome** | Number of teenagers in the household |
| **Dt\_Customer** | Date of customer's enrollment with the company |
| **Recency** | Number of days since the last purchase |
| **MntWines** | Amount spent on wine in the last 2 years |
| **MntFruits** | Amount spent on fruits in the last 2 years |
| **MntMeatProducts** | Amount spent on meat in the last 2 years |
| **MntFishProducts**| Amount spent on fish in the last 2 years |
| **MntSweetProducts**| Amount spent on sweets in the last 2 years |
| **MntBakedProds** | Amount spent on baked goods in the last 2 years |
| **NumDealsPurchases**| Number of purchases made with a discount |
| **NumWebPurchases**| Number of purchases made via the company's website |
| **NumCatalogPurchases**| Number of purchases made using a catalog |
| **NumStorePurchases**| Number of purchases made directly in stores |
| **NumWebVisitsMonth**| Number of visits to the company's website in the last month |
| **AcceptedCmp1-5**| 1 if the customer accepted the offer in the campaign, 0 otherwise |
| **Response** | 1 if the customer accepted the offer in the last campaign, 0 otherwise |
| **Complain** | 1 if the customer complained in the last 2 years, 0 otherwise |
| **Country** | Customer's location |

---

##  Key Performance Indicators (KPIs) & Metrics

The dashboard focuses on several key metrics to measure business and campaign performance:

* **Total Revenue:** Sum of all spending across product categories (`MntWines`, `MntFruits`, etc.).
* **Total Customers:** The unique count of customer IDs.
* **Campaign Acceptance Rate:** The percentage of customers who accepted offers in the campaigns (`AcceptedCmp1-5` & `Response`).
* **Average Customer Income:** The mean household income of the customers.
* **Purchases by Channel:** The total number of purchases made through the web, catalog, and store.

---

##  Dashboard Features & Visualizations

The Power BI report is designed to be interactive and user-friendly, allowing for deep-dive analysis.

* **Interactive Slicers:** Users can filter the entire dashboard by **Country**, **Education Level**, **Marital Status**, and **Number of Children/Teens**.
* **KPI Cards:** At-a-glance view of the most important metrics like Total Customers, Total Revenue, and Overall Campaign Acceptance Rate.
* **Spending Analysis:** Donut and bar charts visualizing the distribution of spending across different product categories (Wine, Meat, Fruits, etc.).
* **Customer Demographics:** Visuals breaking down the customer base by education, marital status, and age group.
* **Campaign Performance:** A detailed analysis of each campaign's acceptance rate, allowing for a comparison of their effectiveness.
* **Purchasing Channel Breakdown:** A stacked bar chart comparing the volume of purchases made online, in-store, and via catalog.

---

##  Insights & Recommendations

This dashboard can uncover several valuable insights, leading to data-driven recommendations:

* **Insight:** Customers with higher incomes and a PhD or Master's degree are the highest spenders, particularly in the wine and meat categories.
    * **Recommendation:** Target these high-value segments with premium product offers and exclusive deals through catalog purchases, which they favor.
* **Insight:** The last marketing campaign (`Response`) had a higher success rate among customers with no children at home.
    * **Recommendation:** Create family-focused campaigns to better engage customers with children and teenagers.
* **Insight:** Web purchases are the most frequent channel for younger customers, while older customers prefer in-store and catalog shopping.
    * **Recommendation:** Optimize online marketing for younger demographics and maintain traditional marketing channels for older segments.

---

##  Tools Used

* **Microsoft Power BI:** Used for data modeling, creating DAX measures, and designing the interactive dashboard.
* **Microsoft Excel:** Used for initial data cleaning and exploration.

---

##  How to Use

1.  Download and install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
2.  Clone this repository to your local machine.
3.  Open the `.pbix` file in Power BI Desktop.
4.  Interact with the slicers and visuals to explore the data and discover insights.

---

##  Author

* **Kashifa Bano**
* **LinkedIn:** (https://www.linkedin.com/in/kasifa-bano/)
* **GitHub:** (https://github.com/iamkashifa)
