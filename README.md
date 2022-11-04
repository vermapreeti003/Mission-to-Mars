# Overview
SpaceForward is an ambitious aerospace company that’s doing research about resource extraction from nearby planets. In this project we will be gathering information about the climate of Mars by performing full web-scraping and data analysis.

## Aim
The aim of this project is to apply full web-scraping for the mission to Mars by collecting data, organizing and storing data, analyzing data, and then visually communicating our insights.
## Analysis of Data and Results

1. Scrape Titles and Preview Text from Mars News

Using Splinter an automated browsing was used to visit the Mars news site. Then, we have extracted the HTML code with Beautiful Soup. After that, we have scraped and extracted the titles and preview text of the news articles and we have stored them in a dictionary.

2. Scrape and Analyze Mars Weather Data
Using Splinter an automated browsing was used to visit the Mars temperature data site. Then, we have extracted the HTML code with Beautiful Soup and we have scraped and extracted the Mars temperature table into a Pandas DataFrame and we have cleaned the table data by editing its data types.

After extracting Mars temperature table, we used this table to analyze and visualize the data by finding answers to the following questions:

* How many months exist on Mars?

  There are 12 months on Mars
  
* Which month, on average, has the lowest temperature? The highest?
  
  The month 3 is the warmest 
  The month 8 is the coldest.
  
* Which month, on average, has the lowest atmospheric pressure? The highest?
 
 The month 6 have lowest pressure.
  The month 9 have highest pressure
  
* How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
 
 Mars circles the Sun 3 times in 2000 days. so 2000/3=666. Martial year is approx 666 terrestrial days.
  
 ## Summary
As we have seen, Web scraping automates the tasks of extracting online data for analysis. Instead of manually visiting each website, copying the data, and then pasting that data into a file, a web-scraping script automatically performs all those actions which made our analyzing easier and faster. 
