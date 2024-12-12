# 11_scrape_analyze-challenge

## Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## What You're Creating
This new assignment consists of two technical products. You will submit the following deliverables:

- Deliverable 1: Scrape titles and preview text from Mars news articles.

- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

# Requirements

## Part 1: Scrape Titles and Preview Text from Mars News
- Automated browsing with Splinter was used to visit the Mars news site, and the HTML code was extracted with Beautiful Soup.

- The titles and preview text of the news articles were scraped and extracted.

- The scraped information was stored in the specified Python data structure, specifically a list of dictionaries.

## Part 2: Scrape and Analyze Mars Weather Data
- The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.

- The data was analyzed to answer the following questions:

    - How many months exist on Mars?

    - How many Martian days' worth of data are there?

- The data was analyzed to answer the following questions, and a data visualization was created to support each answer:

    - Which month, on average, has the lowest temperature? The highest?

    - Which month, on average, has the lowest atmospheric pressure? The highest?

    - How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

- The DataFrame was exported into a CSV file.


--------------------------------------------------------------------------------------------------

## CODING_PROCESS

Overall Approach - used code and concepts from previous activities and challenge assignments as references.

 Part 1
- Used Xpert Lerarning Assistant for gudiance with exporting the scraped data to a JSON file. 

 Part 2
- Used Xpert Learning Assistant for guidnace on looping through the scraped data to create a list of rows
- To determine the number of terrestrial days in a Martian year, I used the matplotlib widget we learned in class and I asked ChatGPT for assistance with creating a graph that would have dates on the x axis so I could better visualize the temperature cycles.

