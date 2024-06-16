# AirBnb-EDA
## Project Overview
This project aims to analyze Airbnb booking data from New York City (NYC) for the year 2019. The analysis provides actionable insights to hosts, property managers, investors, and Airbnb itself. By leveraging detailed information on listings, bookings, and reviews, the project seeks to enhance market understanding, optimize pricing strategies, improve guest experiences, and support informed decision-making.

## Problem Statement
The NYC Airbnb dataset contains approximately 49,000 listings with detailed information on property details, pricing, availability, reservation dates, length of stay, and guest feedback. The goal of this analysis is to explore and understand the dynamics of Airbnb listings in NYC, focusing on several key areas:

**.Room Type Analysis:** Understanding the distribution and performance of different room types.

**.Geographic Analysis:** Examining the geographic distribution of listings and identifying popular neighborhoods.

**.Pricing Strategy Analysis:** Analyzing pricing patterns and strategies to optimize revenue.
**.Availability and Engagement Analysis:** Investigating booking trends, availability, and guest engagement.

**.Host Optimization:** Providing recommendations for hosts to improve listing performance.

**.Guest Experience:** Enhancing guest satisfaction by understanding their preferences and feedback.

**.Airbnb Strategy:** Guiding Airbnb's marketing and service improvement efforts.

## Define Your Business Objective 
The purpose of this analysis is to derive actionable insights from Airbnb listing data in New York City for the year 2019. These insights will inform strategic decision-making and drive performance improvements for key stakeholders. By enhancing the efficiency and effectiveness of the Airbnb platform, this analysis aims to elevate satisfaction levels for both hosts and guests. Ultimately, the goal is to foster growth and strengthen Airbnb's competitive position within the New York City market.

## Approach to the Problem Statement:

**1.Understanding the Problem Statement:** Clearly define the problem and identify the objectives of the analysis.

**2.Data Collection:** Gather the relevant dataset, ensuring it is comprehensive and relevant to the problem at hand.

**3.Data Cleaning and Preprocessing:** Prepare the data for analysis by handling missing values, correcting errors, and formatting it appropriately.

**4.Exploratory Data Analysis (EDA):** Conduct a thorough analysis to understand the data's structure, relationships, and key characteristics.

**5.Visualization:** Use visual tools to represent the data findings clearly and concisely.

**6.Insights and Recommendations:** Draw meaningful insights and provide actionable recommendations based on the analysis.

## Task 1: Knowing the Data.

**1.Loading the Dataset:** Load the Airbnb NYC 2019 dataset into a Pandas dataframe.

**2.Counting Rows and Columns:** Determine the number of rows and columns in the dataset.

**3.Dataset Information:** Understand the structure and data types present in the dataset.

**4.Handling Missing Values:** Address missing or null values and visualize their distribution using a heatmap.

This dataset contains 48,895 entries and 16 columns, encompassing integer, float, and object data types, facilitating analysis on pricing trends, neighbourhood popularity, host behaviors, and guest preferences.

## Task 2: Understanding Variables.

**1.Column Names:** The dataset includes columns such as id, name, host_id, host_name, neighbourhood_group, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, calculated_host_listings_count, and availability_365.

**2.Dataset Description:** Using df.describe(), we obtain statistical summaries for numerical variables like price, minimum_nights, number_of_reviews, reviews_per_month, calculated_host_listings_count, and availability_365, revealing key metrics such as mean, standard deviation, and quartiles.

**3.Unique Values:** Exploring unique values in categorical variables such as neighbourhood_group, neighbourhood, and room_type provides insights into the diversity and distribution within these categories.

It encompasses a range of data types crucial for analyzing pricing trends, neighbourhood popularity, host activities, and booking availability. These insights are pivotal for enhancing strategic decisions and operational efficiencies across the Airbnb platform.

## Task 3: Data Wrangling.

A copy of the original DataFrame was made to preserve data integrity. Rows with missing 'name' values were dropped to ensure data completeness. Columns with over 50% missing values were removed for enhanced dataset quality.

Numerical columns were filled with the median to handle missing values robustly. Categorical columns were filled with the mode for consistency in data handling.

Outliers in the 'price' column were capped at the 99th percentile to prevent skewing of analyses. 'last_review' dates were converted to datetime format. New columns 'last_review_year' and 'last_review_month' were created for temporal analysis.

## Task 4: Understanding relationship between variables.

It involves exploring relationships between variables in the NYC Airbnb dataset using a range of visualizations. These include histograms, countplots, boxplots, line plots, scatter plots, bar plots, pie charts, and correlation heatmaps. Insights gained cover pricing distributions, neighborhood popularity, room type variations, temporal review trends, booking patterns, and correlations between variables. These visuals inform strategic decisions on pricing strategies, neighborhood targeting, and guest engagement efforts in NYC.

## Solution 

The recommendations aim to optimize Airbnb listings in NYC by focusing on key actions derived from data analysis. These include prioritizing "Entire home/apt" offerings to meet high demand and potentially higher pricing, targeting popular neighborhoods like Manhattan and Brooklyn for new listings, implementing dynamic pricing strategies to maximize revenue across different price ranges, ensuring high availability to boost engagement, enhancing guest satisfaction to drive positive reviews and bookings, and leveraging continuous data analysis for ongoing improvements in pricing, marketing, and guest experiences.

## Conclusion

Hosts should prioritize offering "Entire home/apt" options, particularly in Manhattan and Brooklyn, where demand and prices are highest. Implementing dynamic pricing and ensuring high availability throughout the year can maximize revenue. Encouraging guest reviews enhances credibility, while Airbnb can leverage these insights to refine marketing and service strategies, fostering growth and customer satisfaction.




