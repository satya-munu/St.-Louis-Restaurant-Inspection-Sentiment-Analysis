# St.-Louis-Restaurant-Inspection-Sentiment-Analysis
What does a 4-star rating for a restaurant really mean? Inspired by my own food adventures, I decided to web scrape health department inspection scores and perform a sentiment analysis of Yelp reviews to help consumers make more informed choices on where to eat. Currently, I created a dashboard for restaurants in St. Louis. Check it out [here.](https://public.tableau.com/app/profile/satya.munugoti/viz/St_LouisRestaurants_17368002838420/DashboardSt_Louis)

## Project Overview
This project combines official St. Louis [health inspection data](https://www.healthspace.com/StLouis-MO/) with customer sentiment from Yelp reviews to provide a more comprehensive view of dining establishments in St. Louis. By analyzing both official health scores and customer experiences, the project aims to give diners a more complete picture when choosing where to eat.

## Tools Used
- Selenium for web scraping St. Louis Department of Health website
- Beautiful Soup for parsing inspection details
- spaCy for text preprocessing
- NLTK (VADER) for sentiment analysis

## Challenges
- The health department's website had slow loading times, which required careful handling in the web scraper to avoid timeouts and ensure reliable data retrieval.
- Parsing HTML was a non-trivial task due to complex structure and nested elements
- Data availability - not all the restaurants I had Yelp reviews for could be found in the city health department's database

## Future improvements
- Listing the top items ordered at a restaurant by using fuzzy text matching or named entity recognition
- Topic modeling to understand reasons behind positive/negative sentiment (is the service, food, or location?)





