# mars_data_collection

## Overview
The purpose of this challenge is to learn more about data scraping in an educational setting. You will find Part 1, Part 2, Saved CSV in the 'Mars' folder. This module is comprised of two parts:
  1. Scrape titles and preview text from Mars News
  2. Scrape and analyze Mars Weather Data

## Part 1
Part 1 is broken down into three steps:
  1. Visit the website:
     - Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape
  3. Scrape the website:
     - Create a Beautiful Soup object and use it to extract text elements from the website
  5. Store the results:
     - Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structure
    
## Part 2
Part 2 is broken down into six steps:
  1. Visit the website:
  2. Scrape the table:
  3. Store the data:
  4. Prepare date for analysis:
  5. Analyze the data:
     - Analyze your dataset by using Pandas functions to answer the following questions:
         How many months exist on Mars?
         How many Martian (and not Earth) days worth of data exist in the scraped dataset?
         What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
            - Find the average the minimum daily temperature for all of the months.
            - Plot the results as a bar chart.
         Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
            - Find the average the daily atmospheric pressure of all the months.
            - Plot the results as a bar chart.
         About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
            - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
            - Visually estimate the result by plotting the daily minimum temperature
  7. Save the data:
     - Export the DataFrame to a CSV file
