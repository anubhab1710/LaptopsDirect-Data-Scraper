# <p align = "center">  Web Scraper To Generate Product Database from eCommerce Site and Exporting to .xlsx Format </p>
This project is aimed to implement basic web scraping using Python's BeautifulSoup library to create an informative dataset of available products. The e-commerce website targetted in the notebook is laptopsdirect.uk, with primary focus on the available laptops being sold. The project is divided into two parts - the first part scrapes only the first result page of the concerned product while the second part fetches all the available results from multiple pages. The scraped data is formatted using pandas library and exported in .xlsx format.  


<img src = "https://miro.medium.com/max/512/1*nHfayfdmxAApbg84iMrJqQ.gif" align = "right" width = "250px">
 
 The following data points were fetched in this project:
* Product Name
* Price
* Rating
* Review Count
* Product Details
* Relative URL


## Libaries Required
The project requires `BeautifulSoup`, `requests`, `pandas` and `urllib` Python library toolkits to be installed.    

To install the libraries, the following lines of commands can be used in Command Prompt  
  `pip install beautifulsoup4`  
  `pip install pandas`  
> Note: If you are using Anaconda Distribution, pandas and urllib will pre-installed with the package  

## Importing the Libraries
```python
from bs4 import BeautifulSoup           
import requests
import pandas as pd
import urllib.parse
```

## Using the Scraper
The notebook is divided into two parts corresponding to whether one wishes to scrape a single page of results or all of them. Part 1 is meant for scraping the first page of the targeted result site and Part 2 is attributed for all pages. You have to run each cell starting from the library imports and move down sequentially from your desired Part. 

## Exporting the Results
We utilise the pandas library to format all fetched results into a data frame. In this notebook, the results were exported to a MS-Excel file (.xlsx format) using the followung lines of code:

```python
product_overview.to_excel("ResultAll.xlsx", index = False)
```


### <p align = "center"> Improvements in the code and enhancement of the notebook are always welcome!  ❤ </p>
 
