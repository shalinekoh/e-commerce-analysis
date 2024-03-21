# E-Commerce Public Dataset Data Analysis

## Business Problem
In this rapidly evolving landscape of e-commerce, maintaining competitiveness and profitability requires a deep understanding of consumer behavior and market trends. Prevalent challenges faced by e-commerce companies are optimizing product recommendations and sales strategies to enhance customer satisfaction and increase sales.

## Objective
The objective of this data analysis project is to gain insight into the sales data to improve and optimize sales strategies and product recommendation. By leveraging historical transaction data, user behavior patterns, and sales trend of different product lines, we aim to provide recommendations on how to enhance shopping experience and drive revenue growth.

## Dataset Description
The dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and consists of real commercial data. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.

The following schema describes the relationship of the multiple datasets. ![Schema](images/schema.png)

## Business Questions to Address:
1. How many unique cities and states are present in the dataset?
   - This question helps in understanding the geographical distribution of customers, which can inform marketing strategies and logistics planning.
2. Which city and state have the highest order count?
   - Knowing where the highest order counts originate from can help in focusing marketing efforts and optimizing inventory management in those regions.
3. Can we identify any patterns in user engagement over time? (e.g., daily, weekly, seasonal)
   - Understanding user engagement patterns over time can help in scheduling promotions, managing staffing levels, and optimizing resource allocation.
4. How many unique product lines does the dataset have?
   - Knowing the diversity of product lines can inform product assortment decisions and identify potential gaps in the product offerings.
5. What are the most popular categories on the platform?
   - Identifying popular categories can help in prioritizing marketing campaigns, optimizing product recommendations, and expanding product offerings in high-demand areas.
6. How many unique methods of payment are there?
   - Understanding the variety of payment methods used by customers can help in ensuring a seamless checkout experience and optimizing payment processing systems.
7. What are the preferred types of payment?
   - Knowing the preferred payment methods can inform partnership decisions with payment processors and guide the development of payment-related features on the platform.
8. Do customers prefer installment plans?
   - Understanding customer preferences for installment plans can inform pricing strategies, payment options, and promotional offers tailored to customer needs and preferences.

## Approach Used:
1. Data Pre-processing:
   - Clean and pre-process the raw dataset to ensure data quality.
   - Handle missing values to prevent any bias in the analysis.
2. Feature Engineering:
   - Extract timestamps from the dataset to analyze temporal trends.
   - Create new columns such as Hour, Day, and Month to understand the distribution of sales over different time periods.
   - This step enriches the dataset with additional features that can provide valuable insights into user behavior and seasonal trends.
3. Exploratory Data Analysis (EDA):
   - Conduct comprehensive EDA to explore the dataset and uncover insights.
   - Analyze user behavior patterns, such as purchase frequency, popular products, and preferred payment methods.
   - Examine product popularity across different categories and identify any trends or patterns.
   - Utilize the engineered features (Hour, Day, Month) to identify peak sales periods, weekly trends, and seasonal variations.
4. Conclusion:
   - Summarize the findings and insights obtained from the analysis.
   - Present visualizations, such as charts and graphs, to effectively communicate key trends and patterns.
   - Provide actionable recommendations based on the analysis to improve business strategies and decision-making.
