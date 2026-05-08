Green Cart Ltd. – Q2 Business Performance Analysis

Project Overview

This project analyses sales, product, and customer data for Green Cart Ltd. to evaluate business performance during Q2.

The analysis focuses on:

* Revenue performance across regions and product categories
* Customer loyalty behaviour
* Delivery performance and delays
* The impact of discounts on sales
* Customer purchasing patterns

The project combines data cleaning, feature engineering, exploratory data analysis (EDA), and data visualisation to generate actionable business insights and recommendations.

Objectives

The main objectives of this project were to:

* Analyse revenue trends across regions and product categories
* Identify regions experiencing delivery challenges
* Evaluate customer loyalty tiers and purchasing behaviour
* Investigate the relationship between discounts and sales quantity
* Create visual dashboards and business insights
* Recommend improvements to support business growth and operational efficiency

Data Cleaning Process

Several data cleaning steps were performed to improve data quality and consistency:

* Handled missing values using .fillna()
* Replaced missing discount values with 0.0
* Converted date columns into datetime format using pd.to_datetime()
* Removed duplicate records
* Standardised inconsistent text values:
    * gld → Gold
    * silver → Silver
    * femle → Female
    * credit card → Credit Card
    * DELAYED → Delayed

These steps improved the reliability of joins, filtering, and visualisations.


Key Findings

Revenue Performance

* The Cleaning category generated the highest revenue.
* The Personal Care category generated the lowest revenue.
* The East region achieved the highest overall revenue.

Customer Behaviour

* Gold loyalty tier customers generated the greatest customer value.
* Discount levels had minimal influence on quantity sold.

Delivery Performance

High delivery delay rates were identified in:

* West region
* Central region
* South region

The East region demonstrated the best delivery performance.


Recommendations

Based on the analysis, the following recommendations were proposed:

* Increase promotional efforts for Personal Care products
* Introduce bundle offers with Cleaning and Kitchen products
* Improve logistics and shipping reliability
* Consider establishing regional distribution centres
* Strengthen customer communication regarding delivery delays
* Improve data validation processes to reduce missing or inconsistent records


Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


Visualisations Included

The project includes:

* Revenue by region charts
* Revenue by category analysis
* Delivery delay comparisons
* Loyalty tier analysis
* Weekly revenue trends
* Discount vs quantity visualisations

Business Impact

This analysis demonstrates how data-driven decision-making can help Green Cart Ltd.:

* Improve operational efficiency
* Increase customer satisfaction
* Identify revenue growth opportunities
* Enhance fulfilment performance
* Strengthen long-term profitability


Future Improvements

Potential future enhancements include:

* Predictive sales forecasting
* Customer segmentation models
* Delivery delay prediction
* Interactive Power BI/Tableau dashboards
* Automated reporting pipelines


Author

Data Analytics Project by Johnson Taiwo
