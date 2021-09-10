# <p align = "center">  Web Scraper To Generate Product Database From E-Commerce Site and Exporting to .xlsx Format </p>
This project is aimed to implement basic web scraping using Python's BeautifulSoup library to create an informative dataset of available products. The e-commerce website targetted in the notebook is laptopsdirect.uk, with primary focus on the available laptops being sold. The project is divided into two parts - the first part scrapes only the first result page of the concerned product while the second part fetches all the available results from multiple pages. The scraped data is formatted using pandas library and exported in .xlsx format.

 
 The following data points were fetched in this project:
 <img src = "https://miro.medium.com/max/512/1*nHfayfdmxAApbg84iMrJqQ.gif" align = "right" width = "250px">
 * Product Name
* Price
* Rating
* Review Count
* Product Details
* Relative URL


## Libaries Required
The main Python libraries required for this project are `BeautifulSoup`, `requests`, `pandas` and `urllib`

## Importing the Libraries
```python
from bs4 import BeautifulSoup           
import requests
import pandas as pd
import urllib.parse
```
