# indeed_scrapy_spider
Python Scrapy spider that scrapes Jobs data from Indeed.com. 

Scrapes Job Summary Data: The scraper will query the Indeed search page with your query parameters and extract the job data directly from the search results.
Scrapes Full Job Data: The scraper will crawl the Indeed search pages with your query parameters, then send a request to each individual job page and scrape all the job data from the page.
Both of these scrapers only scrape some of the available data, however, you can easily expand them to scrape other data that is available in the response.

These scrapers extract the following fields from Indeed jobs pages:

Company Name
Company Location
Job Title
Job Description
Job Salary
Job Location
Etc.
