# Project 1 - Group 12: Airbnb Analysis

## Research Questions
- Location  
- Historical 
- Price: What are price statistics for sites between 2008 and 2020?
- Amenities  

## Dataset
We used a dataset created by a data sciences student (using InsideAirbnb.com), that presents data from nine major locations in the United States: California, Washington, DC, Florida, Hawaii, Illinois, Nevada, New York, Tennessee, and Washington state. The data presents property information for between the years 2008-2020 that includes:
- host information, qualities, and history
- property location by metro areas (cities or counties) and further organized by neighborhoods within those metro areas
- property amenities

## Data Exploration and Cleaning

- We removed columns that we would not be using, such as:
- We removed rows for which site availability was 0/365 days and for which site price was $0.
- We edited location column names for clarity and neater visualizations: (‘neighbourhood_groups’ to ‘metro’ and ‘neighborhood’ to ‘city’); changed state names to an abbreviations; concatenated metro and state abbreviation.
- We formatted date information as dates were in two different formats.

## Historical 

## Amenities
- First we determined the most popular amenities and arranged them into a bar chart 
- Grouped all of the amenities into basic, luxury, and safety. We assessed if luxury amenities increase the price of a listing. We analyzed the impact on the average price and used visualizations to plot it. 
- Utilized t-stats and p-Values to assess if the difference in price was statistically significant. 
- Determined the cities with the most luxury amenities and the cities with the highest prices. We then compared the two lists. 
- Plotted the luxury amenities percentage and average price by neighorhood then used linear regression in our visualization. 
- Listed the top 10 amenities by each neighhorhood for comparison. We assebled these values into a bar graph and heat map. 
- Analyzed the listings and divided them into two categories- listings by superhosts and non-superhosts. These values were assembled into a pie chart. 
- Used boxplosts to show a price comparision between superhosts and non-superhosts. Used violin plot to visualize price distribution adjusted for outliers. 
- Assessed the total and monthly review total for superhosts vs non-superhosts. Assessed for frequency of review.

  ## Conclusions and Implications
