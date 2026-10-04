# ecommerce-sales-customer-analytics
End-to-end e-commerce sales and customer analytics project using Python, SQL, data visualisation, and time-series forecasting to uncover business insights from 49,222 transactions.


## Key Findings & Conclusions

### Key Findings

The analysis of 49,222 customer orders revealed several important patterns across sales, customers, products, locations and order behaviour.

* **Electronics was the strongest-performing category**, generating approximately **1.75 million in total sales**, followed by Accessories at approximately **553,000**. This indicates that Electronics is the primary revenue-generating category in the dataset.

* **Tehran generated the highest sales across the cities analysed**, with Electronics being particularly strong. This suggests that Tehran represents an important market and that Electronics contributes substantially to its sales performance.

* The **35–44 age group generated the highest sales** among the main age groups, with approximately **775,854**, followed by the 25–34 and 45–54 groups. This suggests that customers in these age ranges represent important customer segments.

* **Gateway was the most frequently used payment method**, accounting for approximately **48.5% of all transactions**. CardToCard accounted for approximately 23.9%, followed by Wallet at 17.6% and Cash at 10.0%.

* The dataset contained **45,276 completed orders**, compared with **2,438 cancelled orders** and **1,508 returned orders**. Overall, cancellations and returns represent a relatively small proportion of transactions but are still important operational metrics to monitor.

* **Cancellation rates were relatively consistent across categories**, ranging from approximately 4.6% to 5.0%. Return rates showed slightly more variation, with Stationery having the highest return rate at approximately **3.58%** and Wearables the lowest at approximately **2.73%**.

* The overall **average sales value per order was approximately 69.99**. Comparing average sales with total sales and order volumes provides a better understanding of whether strong-performing categories and customer groups are driven by transaction volume or higher-value purchases.

### Business Conclusions

The analysis suggests that the business is heavily dependent on the Electronics category for revenue generation. This makes Electronics an important category to monitor in terms of inventory, pricing, promotions and customer demand.

Tehran also stands out as a particularly important market. Further investigation into customer behaviour, product preferences and order frequency in this city could help identify opportunities for targeted marketing and sales strategies.

The relatively consistent cancellation rates across categories indicate that cancellations are not concentrated within one particular product category. However, the variation in return rates suggests that certain categories may require further investigation, particularly Stationery, which recorded the highest return rate.

The comparison between total sales, order volumes and average sales per order is also important. High total sales do not necessarily mean that customers are placing higher-value orders; a category may generate high revenue simply because it has a much larger number of transactions. Analysing these metrics together provides a more complete view of business performance.

### Data Quality Findings

The dataset contained **49,222 records and 17 variables**, with no missing values identified across the columns.

However, the analysis identified negative sales and quantity values. These were not automatically removed because they may be associated with returned or cancelled transactions. Instead, these observations were investigated in the context of the order status to avoid incorrectly altering the underlying business data.

### Technical Skills Demonstrated

This project demonstrates practical experience with:

* **Python** – data manipulation, analysis and visualisation
* **Pandas** – data cleaning, aggregation and exploratory analysis
* **Matplotlib** – data visualisation
* **SQL** – aggregation, filtering, grouping and business analysis within Python
* **Statistical analysis** – descriptive statistics and correlation analysis
* **Time-series analysis** – monthly sales trends and forecasting
* **Business analytics** – customer, product, geographic and operational analysis
* **Data quality analysis** – missing values, duplicates, outliers and invalid values

### Overall Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow, beginning with data quality assessment and progressing through descriptive analysis, SQL-based business analysis, visualisation and sales forecasting.

The analysis shows how transactional data can be transformed into actionable business insights by examining not only total sales, but also order volumes, average transaction values, customer segments, product categories, geographic performance and operational outcomes.

The project ultimately demonstrates the ability to use **Python and SQL together to investigate business performance and communicate data-driven findings**.
