# Project 1 - Group 12: Airbnb Analysis

## Research Questions
- Host Analysis
  - How have Airbnb hosts joining airbnb increased or decreased over time (by year)?
  - What are the most popular Metro Areas to host in? What is the share of Hosts & Superhosts?
  - What are the most popular Property Types by Metro Area?
- Price Analysis
  - What are price statistics for listings between the years 2008 and 2020?
- Amenities Analysis
  - What are the most common amenities? Do they fall in specific categories?
  - Does offering luxury items boost the price of a listing?
  - Are the most expensive neighborhood/cities also the most luxurious?
  - Does superhost increase the listing price?
- Historical Trends Analysis
  - How have average prices for listings changed over the years in different cities and metros?
  - Are there consistent peak and low seasons for Airbnb bookings in specific cities?
 

## Dataset
We used a dataset created by a data sciences student (using InsideAirbnb.com), that presents data from nine major locations in the United States: California, Washington, DC, Florida, Hawaii, Illinois, Nevada, New York, Tennessee, and Washington state. The data presents property information for between the years 2008-2020 that includes:
- host information, qualities, and history
- property location by metro areas (cities or counties) and further organized by neighborhoods within those metro areas
- property amenities

## Data Exploration and Cleaning

- We removed columns that we would not be using.
- We removed rows for which site availability was 0/365 days and for which site price was $0.
- We edited location column names for clarity and neater visualizations: (‘neighbourhood_groups’ to ‘metro’ and ‘neighborhood’ to ‘city’); changed state names to an abbreviations; concatenated metro and state abbreviation.
- We formatted date information as dates were in two different formats.
- We generated a variety of DataFrames and visualizations to uncover trends and outliers.

## Conclusions
- There are extreme outliers in this dataset. However, for the years 2008-2020, the majority of prices per night lie around the median of $125/night.
- Hosts joining the platform peaked in 2014, similar to prices, increased each year until 2016 due to regulatory pressure leading to changes in how many properties a single host could manage and for how long renters could stay. Then, there was a downturn in both the number of hosts and price per listing in 2020 due to the COVID pandemic.
- There were strong seasonal booking trends from July to October with a small trend in February-March.
- When a property contains luxury amenities it increases the average price significantly, where properties with luxury amenities on average cost $100 more.
  - The most expensive cities are completely different than the ones with the most luxury amenities. For example, Las Vegas had the most luxury amenities by far, but is not one of the most expensive cities.
  - Luxury amenities increase the price, but are not as impactful on price as location.
- The Los Angeles metro area leads in the number of hosts (and superhosts), property types, price per neighborhood/city (i.e. Rolling Hills, Bel Air, Malibu) and highest seasonal bookings in October.

## Implications
- Investigate how national health crises or economic regulation affect short-term rental property pricing trends.
- Find a dataset with additional data (such as booking records) to explore:
  - Are bookings tied to leisure travel?
  - Are travelers from out of town or traveling locally?
  - Do these factors correlate to seasonal trends?
- Potential hosts could use seasonal data to identify most profitable rental periods


