# Web Scraping Challenge

### Mars Weather: Part 1
* Use automated browsing to visit the Mars NASA news site Links to an external site.. 
* Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to extract text elements from the website.
* Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures
* Store each title-and-preview pair in a Python dictionary. And, give each dictionary two keys: title and preview. 
* Print the list in your notebook.


### Mars Weather: Part 2
* Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. 
* Inspect the page to identify which elements to scrape. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.
* Create a Beautiful Soup object and use it to scrape the data in the HTML table. 
* Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 

#### Analyze your dataset by using Pandas functions to answer the following questions:

* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
* Find the average the minimum daily temperature for all of the months.
* Plot the results as a bar chart.
* Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
* Find the average the daily atmospheric pressure of all the months.
* Plot the results as a bar chart.
* About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
* Consider how many days elapse on Earth in the time that Mars circles the Sun once.
* Visually estimate the result by plotting the daily minimum temperature.
* Export the DataFrame to a CSV file.
