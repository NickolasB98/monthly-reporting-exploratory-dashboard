# Monthly Reporting Exploratory Dashboard (Excel)


**Excel Link:** https://1drv.ms/x/s!AgWuMp-n2Drdgkts8rjY0NLNnxCD?e=iydUvY&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMjAwLTAwMDAwMDAwMDAwMH0

# Short Description: 

This project involved the development of an interactive sales dashboard in Excel. Leveraging pivot tables, charts, and conditional formatting, the dashboard provides a dynamic overview of sales performance across various dimensions, including sales by month, state, product, salesperson, and customer. Interactive features, such as state-based filtering, enable users to explore data and gain valuable insights into sales trends and performance. The dashboard is designed to be refreshed with new data updates, ensuring the information remains current and relevant.

<img width="1094" alt="image" src="https://github.com/user-attachments/assets/4afba4fb-a18b-4388-8dca-b1f068e6fc6c" />

## Dashboard Purpose

To provide an interactive overview of sales performance, enabling analysis of trends, identifying key areas of strength and weakness, and supporting data-driven decision-making. The dashboard is getting refreshed every time the data source updates.

## Dataset

The project utilizes a [sales dataset](https://1drv.ms/x/s!AgWuMp-n2Drdgkts8rjY0NLNnxCD?e=MiBtUX&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMDAwLTAwMDAwMDAwMDAwMH0) containing detailed information on individual sales transactions. 

# **Key Requirements**

### **Sales Performance**

- **Sales by Month:**
    - Display monthly sales revenue for the current and previous years.
    - Visualize the trend using a line chart with clear markers.
- **Sales by State:**
    - Show the revenue contribution of each state.
    - Allow users to filter the dashboard by selecting states using an interactive slicer.
- **Sales by Payment Type:**
    - Visualize the distribution of sales across different payment methods (Cash, Credit Card, Check).

### **Product Performance**

- **Top 10 Products:**
    - Display the top 10 revenue-generating products.
    - Show key metrics like quantity sold, revenue, and sales percentage.
    - Use in-cell bars to visually represent sales performance within each product category.

### **Salesperson Performance**

- **Top Salespersons:**
    - Display the top-performing salespersons based on revenue and quantity sold.
    - Show key metrics like quantity sold, revenue, and percentage of total sales.
    - Utilize in-cell bars to visually compare sales performance across salespersons.

### **Customer Analysis**

- **Top Customers:**
    - Display the top customers by revenue.
    - Show key metrics like quantity sold, revenue, and number of orders.

### **Transaction Analysis**

- **Sales Distribution:** Analyze the distribution of transactions by revenue range.
    - Use a histogram showing grouped transactions based on revenue, to visualize the distribution.


# **Insights Deep Dive**

**Category 1: Sales Performance by Sales Person**

**Main Insight 1: Top Performing Sales Persons**

- **Finding:** Gerry Spring and Ted Richards are the top-performing salespersons in terms of revenue.
- **Supporting Data:** The "Sales Person" table shows Gerry Spring and Ted Richards with the highest "Rev" values.
- **Implication:** These salespersons are key contributors to the company's revenue and should be recognized and potentially used as models for others.

**Main Insight 2: Revenue Distribution**

- **Finding:** The revenue is distributed among several salespersons, with a clear drop-off after the top two.
- **Supporting Data:** The "Rev" column in the "Sales Person" table shows a gradual decline after Gerry Spring and Ted Richards.
- **Implication:** This indicates a need to analyze the performance of lower-performing salespersons and provide additional support or training.

**Category 2: Top 10 Products by Revenue**

**Main Insight 1: Dominant Product Categories**

- **Finding:** Coffee and Curry Sauce are the top-selling products, contributing significantly to the company's revenue.
- **Supporting Data:** The "Top 10 Product" table shows Coffee and Curry Sauce with the highest "Rev" values.
- **Implication:** These products are essential for the company's sales and should be prioritized in inventory and marketing strategies.

**Main Insight 2: Revenue Contribution Percentage**

- **Finding:** Coffee and Curry Sauce each contribute over 26% to the total sales revenue.
- **Supporting Data:** The "Sales %" column in the "Top 10 Product" table shows 26.4% and 26.3% for Coffee and Curry Sauce, respectively.
- **Implication:** This highlights the concentration of sales in these two product categories.

**Category 3: Top Customers by Revenue**

**Main Insight 1: Major Revenue Contributors**

- **Finding:** Treakle Inc, Lol & Beard, and Fruit Bowl are the top customers, contributing significantly to the company's revenue.
- **Supporting Data:** The "Customers" table shows Treakle Inc, Lol & Beard, and Fruit Bowl with the highest "Rev" values.
- **Implication:** These customers are crucial for the company's business and should be given priority in customer relationship management.

**Main Insight 2: Revenue Concentration**

- **Finding:** The top three customers contribute over 16% each to the total sales revenue.
- **Supporting Data:** The "Sales %" column in the "Customers" table shows percentages above 16% for the top three customers.
- **Implication:** This indicates a high dependency on a few key customers.

**Category 4: Sales by Month**

**Main Insight 1: Monthly Sales Trends**

- **Finding:** The "Sales by Month" line chart shows the sales trend throughout the year, with visible fluctuations.
- **Supporting Data:** The line chart displays sales figures for each month.
- **Implication:** This helps in identifying peak and low sales periods and planning accordingly.

**Main Insight 2: Monthly Sales Values**

- **Finding:** The chart provides specific sales values for each month.
- **Supporting Data:** The chart includes numerical sales values for each month.
- **Implication:** This allows for a detailed analysis of monthly sales performance.

**Category 5: Count of Transactions**

**Main Insight 1: Transaction Count Distribution**

- **Finding:** The majority of transactions fall within the 0-1000 range, with a significant number in the 1000-2000 range.
- **Supporting Data:** The bar chart shows the highest bars in the 0-1000 and 1000-2000 ranges.
- **Implication:** This indicates that most transactions are of smaller volumes.

**Category 6: Top 5 by Category**

**Main Insight 1: Category Revenue Comparison**

- **Finding:** Beverages and Sauces are the top-performing categories in terms of revenue.
- **Supporting Data:** The bar chart shows Beverages and Sauces with the highest bars.
- **Implication:** These categories are key revenue drivers and should be prioritized.

**Category 7: Revenue by State**

**Main Insight 1: Dominant States**

- **Finding:** NSW and QLD are the dominant states in terms of revenue.
- **Supporting Data:** The chart shows the highest percentages for NSW and QLD.
- **Implication:** These states are key markets and should be given priority in sales and marketing efforts.

**Category 8: Sales by Payment Type**

**Main Insight 1: Credit Card Dominance**

- **Finding:** Credit Card is the most preferred payment type.
- **Supporting Data:** The chart shows the highest value for Credit Card.
- **Implication:** This indicates that credit card payments are a major driver of sales.

## **Recommendations**

- **Sales Strategy:** Implement targeted training and support for lower-performing salespersons to improve their sales techniques and product knowledge.
- **Product Management:** Ensure adequate stock levels and develop targeted marketing campaigns for top-selling products like Coffee and Curry Sauce.
- **Customer Relationship Management:** Implement a robust CRM strategy and loyalty programs for top customers like Treakle Inc, Lol & Beard, and Fruit Bowl.
- **Seasonal Planning:** Develop seasonal sales strategies and promotional activities to capitalize on peak sales periods and mitigate low sales periods.
- **Transaction Optimization:** Implement upselling and cross-selling strategies to increase the value of each transaction.
- **Category Expansion:** Explore opportunities to expand the product offerings within the Beverages and Sauces categories.
- **Regional Marketing:** Develop targeted marketing campaigns for each state based on their specific market characteristics.
- **Payment Processing Optimization:** Ensure efficient and reliable credit card payment processing and explore opportunities to diversify payment options.

# **Design & Interactivity**

- **Clean and Intuitive Layout:** Organize dashboard elements for easy readability and navigation.
- **Consistent Color Scheme:** Use a limited color palette for a professional and cohesive look.
- **Interactive Slicers:** Implement slicers for filtering data by state and other relevant criteria.
