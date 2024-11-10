# data-class-project1
Duplicate repo of our original project files

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
