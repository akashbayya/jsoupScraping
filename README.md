# jsoupScraping
Scraping player data from Espncricinfo using jsoup html parser

Java code for scraping data and storing it in json format.

The code is organized into three functions:
  a. ScrapeTopic - Takes site main page url as input (http://www.espncricinfo.com/indian-premier-league-2015/content/series/791129.html)
  b. ScrapeTeam - Function called for each of the 8 teams with parameter as team url
  c. ScrapePlayer - Function takes player url as input and scrapes data from the webpage. (accessing the html elements)
  
