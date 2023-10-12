### Power BI Project: Sentiment Analysis for Olist

## Dataset

This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on our website: www.olist.com

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

## Data Wrangling
I initiated the data wrangling process in Power BI by importing the dataset files, configuring the correct schema, establishing necessary relationships, and ensuring data cleanliness. Additionally, I imported a supplementary table from [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-2:BR) containing state names and ISO codes for enrichment.

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
