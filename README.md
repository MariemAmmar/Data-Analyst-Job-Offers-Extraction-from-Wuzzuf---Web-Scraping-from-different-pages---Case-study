# Data Analyst Job Offers Extraction from Wuzzuf
This repository contains Python code for extracting Data Analyst job offers posted on Wuzzuf, an employment website. The code scrapes job titles, company names, and job types from multiple pages and saves the data in a CSV file. The CSV file can be further processed for analysis and visualization.

## Libraries Used
* numpy and pandas for data manipulation and analysis.
* matplotlib and seaborn for data visualization.
* requests for sending HTTP requests to the web page.
* BeautifulSoup for parsing HTML content.

## How to Use the Code
* Clone the repository to your local machine.
* Install the required libraries (numpy, pandas, matplotlib, seaborn, requests, and BeautifulSoup).
* Open the Python script (wuzzuf-data-analyst.py) in an IDE or text editor.
* Change the urls variable to the Wuzzuf pages that you want to scrape.
* Run the code and wait for it to finish.
* The output will be saved as a CSV file (wuzzuf-data-analyst.csv) in the specified directory.

## Limitations
The code only extracts job titles, company names, and job types. If you need more information, you will need to modify the code accordingly.
