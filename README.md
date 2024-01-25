# BigDataAnalysisUsingPySpark

- Project Overview
In the evolving landscape of e-commerce, online retailers can expand local businesses into international markets. The ability to extract actionable insights from vast transaction records becomes crucial. Our project aims to discover the layers of information within the dataset of a UK-based and registered non-store online retail entity. This dataset encompasses transactions conducted from December 1, 2009, to December 9, 2011. With a specialty in selling unique all-occasion giftware, this company’s customer base includes many wholesalers.

This dataset contains Invoice details, StockCodes, Product Descriptions, Quantity, Invoice Dates, Prices, Customer IDs, and Country. In the overview of our project, we delve into data analysis and insights across three significant dimensions of our dataset: Country, Product, and Customer. This detailed understanding could provide the company with a comprehensive understanding of its operations and customer interactions.

- An example from the notebook:

  Customer Segmentation (Pie Chart)
Analyzing the revenue contribution from an online store's customers, it is evident that a small fraction of clients, the top 5, are responsible for a substantial portion of the revenue, making up approximately 22% of total sales. This significant concentration of spending within such a limited customer base suggests a heavy reliance on these top spenders, underlining the quintessential Pareto Principle, or the 80/20 rule, where a small percentage of customers generate a large percentage of revenue. It highlights the importance of customer loyalty programs and personalized marketing strategies to maintain the business these key clients provide.

As we expand our focus to the top 25 customers, the pie chart reflects a more distributed but still notably skewed revenue contribution. The difference in revenue between each customer beyond the top 5 becomes less pronounced, indicating a more uniform spending pattern among the wider customer base. This tiered distribution of customer value emphasizes the need for segment-specific engagement strategies. While the top customers warrant tailored high-value customer service, the broader base requires a different approach, perhaps focusing on increasing the transaction frequency or upselling to elevate their revenue contribution closer to that of the top tier. It is crucial for the online store to diversify its revenue sources to mitigate risks associated with over-reliance on a small customer group while nurturing the potential of the broader customer base to move up the value ladder.

<img width="1309" alt="Screenshot 2024-01-25 at 2 59 49 AM" src="https://github.com/eren-bardak/BigDataAnalysisUsingPySpark/assets/138029233/12f836be-942b-4d9e-94af-6872349df081">

- Next Step Project Goals

The primary objective of this project is to further the exploratory data analysis (EDA) performed on the online store's data using PySpark. Thus far, we have revealed insights related to the store's total revenue, customer demographics by country, key revenue-generating customers, popular products, product performance, and sales distribution across various regions. The forthcoming phase involves developing a refined data processing workflow, utilizing Spark’s robust data handling and the GPT API’s product classification based on textual descriptions. Such categorization will facilitate a structured organization of products and enable a detailed examination of sales patterns within each product group. Our goal is to provide the online store with an enhanced perspective on their product turnover, pinpointing in-demand products and their seasonal trends. This might help an online store better manage their stock and plan their sales promotions, without jumping right into complex sales forecasting.
