## Module 11 Challenge - Data Collection
## Author : Jyothi Palle

## The challenge has two deliverables 

# Part 1: Scraped Titles and Preview Text from Mars News

* Utilised Splinter for automated browsing and Beautiful soup to extract html code
* Using beautifulsoup html parsed and created soup object
* The titles and preview text of the news articles were scraped and extracted.
* The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. 

# Part 2: Scrape and Analyze Mars Weather Data 

* Import relevant packages and launch chrome browser
* Created beautiful  soup object and scrape html table data 
* The HTML table was extracted into a Pandas DataFrame. Beautiful Soup used to scrape the data
* Examined the data types of each column using info() function and modified the data types to match the data format  
* In the next steps the data was analyzed to answer the following questions:
  * How many months exist on Mars? Totak 12 Months
  * How many Martian days' worth of data are there? Total 1967 martian days of worth of data present in the sample 
  * Which month has the coldest and hottest lowest temperature?  Month 3 has coldest temperature and month 8 is hottest
  * Which month, on average, has the lowest atmospheric pressure? Month 6 has lowest and month 9 is highest
  * How many terrestrial days exist in a Martian year? Based on daily min temp plot high peaks are approx at 1425 and 750m which is 675 days
  * Based on statiscal calcuation using sol data arrived the number of days in a year on mars is approx 675  
* DataFrame was exported into a CSV file and closed the browser