# Airbnb Market Analysis: Columbus vs New York

## Author
SM Tanvir Bin Azad

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to focus on the most optimal location with the best price point, demand, type of property and ROI for people who are planning to invest in a property and list it up on the Airbnb market.

## Research Questions

1. What neighborhood provides the best value when it comes to pricing, review score, and the number of reviews?
2. What type of homes generate the most occupancy (private or entire home) generally?
3. What neighborhood has the highest demand?
4. What price point should the listings be in the city and neighborhood to generate the most interest?
5. Does more reviews make the listing price higher/lower/not affected compared to the average price in the neighborhood?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | [Question 1] | neighbourhood, price, number_of_reviews | listings.csv | Structured |
| 2 | [Question 2] | room_type, number_of_reviews, reviews_per_month | listings.csv | Structured |
| 3 | [Question 3] | neighbourhood, number_of_reviews  | listings.csv | Structured |
| 4 | [Question 4] | neighbourhood, price, number_of_reviews, reviews_per_month | listings.csv | Structured |
| 5 | [Question 5] | price, number_of_reviews, reviews_per_month, neighbourhood | listings.csv | Structured |

## Data Overview
- **Columbus, Ohio:** [X] listings (as of Sept 26, 2025)
- **New York City:** [X] listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created