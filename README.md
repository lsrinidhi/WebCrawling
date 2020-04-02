This repository describes the steps used to crawl through Wikipedia page - Super Bowl.

I'm using Python and BeautifulSoup package to crawl through Wikipedia.

My Python notebook named WebCrawler.ipynb that implements my web crawler. I'm using Markdown cells to write descriptions about how the notebook is arranged / what the code is doing along with comments in the code itself. 

OUTCOME:
An accompanying CSV file named crawl.csv that contains 100 unique fully-specified (not relative) webpage URL targets from the same web domain.  It should have the following header:
“url_source”, “url_target”, “page_title_target”
Where “url_source” is the URL to an HTML page that contains the “url_target” to another HTML page you discovered in your crawl.

PROCESS:
For each page aside from the entry URL entry, I'm collecting:
The source URL (url_sorce) of an HTML webpage that you gathered the target URL from
The target URL (url_target) to an HTML webpage you discovered through crawling
The title  (page_title_target) of the web page rendered by the (url_target) URL

