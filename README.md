# Crawl Wikipedia
I wrote this code for an assignment to crawl through Wikipedia page - Super Bowl.

## Technologies used
I used Python and BeautifulSoup package to crawl through Wikipedia.

## Output File
A CSV file named crawl.csv that contains 100 unique fully-specified (not relative) webpage URL targets from the same web domain, having the headers “url_source”, “url_target”, “page_title_target” where “url_source” is the URL to an HTML page that contains the “url_target” to another HTML page discovered during the crawl.

## Steps
For each page aside from the entry URL entry, I'm collecting:
The source URL (url_source) of an HTML webpage that you gathered the target URL from
The target URL (url_target) to an HTML webpage you discovered through crawling
The title  (page_title_target) of the web page rendered by the (url_target) URL


## Files Description
My Python notebook named WebCrawler.ipynb that implements my web crawler. I'm using Markdown cells to write descriptions about how the notebook is arranged / what the code is doing along with comments in the code itself. 
