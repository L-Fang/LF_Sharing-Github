# A Web Scraping Journey into LEGO® Jurassic World and Technic
## Introduction:
- In this project, two main tasks are completed, web scraping and data analysis. 
- The first part is web scraping from the Lego website to receive the data related to Lego products. In this step, two libraries in python, requests and json, were used to execute web scraping from the backend of Lego official website. After being scraped, the data was saved as csv file. For analysis purposes, I chose to get the data for products of two themes, Jurassic World and Technic. Four requests were sent to scrap the data and then the data was written into csv files.
- The second part is the analysis and visualization of scraped data. Some basic statistics were collected after the preprocessing of data. Tables, visuals such as heatmap, scatter plot, bar chart, line chart, pie chart, box plot were shown to see the correlation between variables and the density of Age, Price, and so on.
## Libraries:
- import requests
- import json
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns 
- from pandas import json_normalize
- import warnings
## Conclusion:
- There is a very strong positive correlation between price and pieces or age and pieces. From the scatter plot of Price vs. Pieces, it is also shown the price will increase with pieces count. The heatmap confirmed this correlation as well. 
- From the pie charts, it is shown the most products are for ages from 6 to 16. People whose age are in this range are more likely to play Lego. This is proved by the visual of Density plot for Age.
- The Density plot for Price tells us that most Lego products are selling for the price under $400 and some of them are selling under $1,000.
- Compared with the theme of Jurassic World, the theme of Technic has more kinds of products and higher average price. For both the theme of Jurassic World and Technic, the price has a positive change with the increase of pieces count.
