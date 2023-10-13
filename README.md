# Power BI Project: Sentiment Analysis for Olist

## Brazilian E-Commerce Public Dataset by Olist

I used the public dataset provided by Olist Store on [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. 

I built a 6-page report that looks into reviews, sales, products and delivery performance.

## Data Wrangling
I initiated the data wrangling process in Power BI by importing the dataset files, configuring the correct schema, establishing necessary relationships, and then cleaned the data. Additionally, I imported a supplementary table from [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-2:BR) containing state names and linked it olist_customers_dataset based on state codes.

## Overview of Reviews 

In this section, I delved into comprehensive review analysis, encompassing the following tasks:

- Calculated the Average Review Score.
- Counted Total Reviews based on their scores.
- Classified reviews into three sentiment categories (positive, neutral, negative) and visualized the distribution with a donut chart.
- Developed tables and maps illustrating Total Reviews and Sales by Customer State to identify top and bottom performers.
- Constructed a map highlighting the Top 10 Cities based on Sales and Sentiment.


## Reviews & Sales
This segment focused on the relationship between reviews and sales:

- Generated a line chart for a detailed examination of review and sales trends.
- Utilized a Combo chart to scrutinize the correlation between the average price and the average review score.
- Employed a bar chart to conduct sentiment analysis within product categories by sales.
- Created another bar chart to analyze sentiment in the context of the most expensive products.

## Keyword Clustering
Keyphrase extraction from customer reviews was facilitated using Azure AI Language, enabling the identification of prominent topics. Additionally:

As delivery was a common theme, I calculated shipping times and categorized delivery performance into "On Time" and "Late."

## Key Influencers
I incorporated a Key Influencers visual to gain insights into the factors driving both negative and positive reviews. These factors were explained by variables such as delivery performance, shipping time, state, month of the year, and the quantity of product photos.

## ForecastQA
In this section, sentiment scores from customer messages were calculated using Text Analytics and compared to review scores for consistency. The process included:

- Generating a sentiment score forecast for the next two years.
- Identifying key months with critical negative scores.

Detailed Analysis
A treemap was developed to provide a granular examination of delivery performance and shipping time, categorized by state, product category, and sentiment.

Q&A Support
For further data exploration, I created a Q&A section to assist the client in conducting in-depth inquiries.

## Next Steps
After conducting thorough exploratory data analysis and creating informative visualizations, I have compiled a summary of the key insights and practical recommendations for Olist.
