# Data Scraping for Restaurant Location Selection Project

## Executive Summary

This project, developed in a team of three individsuals, is aimed at addressing a pertinent business challenge for a real estate company planning to open a new restaurant in San Francisco. The objective was to identify the optimal location for a restaurant with a specific cuisine while ensuring robust customer engagement. To achieve this goal, data gathering techniques from Yelp and Uber Eats were employed to analyze the performance, ratings, and cuisine offerings of existing restaurants in the city.

## Background, Context, and Domain Knowledge

In the context of this project, we are focused on the real estate industry, specifically catering to a client who is a real estate developer with aspirations to venture into the restaurant business in San Francisco. Its vibrant culinary scene, diverse population, and high tourist influx make it an attractive yet competitive market for restaurant establishments.

The real estate developer seeks to leverage data-driven decision-making to identify the most suitable location for a new restaurant establishment. This entails understanding the dynamics of the local restaurant market, including consumer preferences, existing competition, and areas with high customer engagement. Success in this depends heavily on selecting the right location that aligns with the desired cuisine offerings and attracts the target customer base.

In this domain, comprehensive data analysis plays a crucial role in informing strategic decisions. By leveraging data from platforms like Yelp and Uber Eats, insights can be gathered regarding the performance, ratings, and reviews of existing restaurants. This information serves as a valuable foundation for identifying market gaps, understanding consumer preferences, and optimizing business strategies.

At the intersection of real estate, hospitality, and data analytics, this project made use of advanced technologies like Selenium and BeautifulSoup in Python to efficiently collect and process extensive data from online platforms. This enabled the creation of a comprehensive dataset for analysis, empowering the team to generate actionable insights.

## Introduction of the Data Sources

This project relies on two primary data sources: Yelp and Uber Eats. Yelp provides a wealth of information on restaurants, including ratings, reviews, cuisine types, and location data. Uber Eats offers insights into the cuisine offerings, pricing, and customer engagement metrics of restaurants in the area. By combining data from these sources, this project aims to conduct a comprehensive analysis to support the client’s decision-making process in selecting the optimal location for their restaurant venture.

## Data-Scraping Routine

### Uber Eats
For Uber Eats, Selenium was used to access the website and filter restaurants based on price range. After downloading the page as an HTML file, BeautifulSoup and regular expressions were used to extract relevant information such as restaurant name, location, cuisine, reviews, and ratings. This data was stored in MySQL and exported to Excel for further analysis.

### Yelp
For Yelp data, the Yelp API was accessed to retrieve information on the top 20 restaurants in San Francisco for each price category. This data was stored in a MySQL database and exported to CSV files. By integrating Yelp and Uber Eats data, a comprehensive dataset was created for analysis.

## Dataset and Database Design Choices

The dataset includes attributes such as restaurant ID, name, address, city, zip code, review count, categories, ratings, price level, and geographical coordinates. This design prioritizes simplicity and efficiency to effectively manage restaurant data for analysis. The primary key is ID, facilitating seamless data retrieval and manipulation. The project was completed using collaborative efforts in a team of three individuals.

## Business Relevant Questions and Efficient Use of Data

This project's dataset can be used to answer key questions such as optimal location identification, consumer preferences and behavior analysis, and competitive landscape analysis. By leveraging data analytics and machine learning, this project aims to provide actionable insights for the client's restaurant venture.

## Summary and Conclusions

This project, completed by a team of three individuals, combines data scraping techniques with machine learning to identify the ideal restaurant location in San Francisco. By analyzing data from Yelp and Uber Eats, valuable insights were provided to empower the client's decision-making process. This data-driven approach enhances the likelihood of success in San Francisco's competitive restaurant market.

