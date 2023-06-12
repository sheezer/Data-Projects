# IBM Data Scientist Professional Certificate
## Applied Data Science Capstone Project

This repository contains the various notebooks and the final presentation completed during the course Python Capstone Project for IBM's Data Scientist Professional Certificate on Coursera.


### 1-1-spacex-data-collection
Uses the request library to request launch data on SpaceX launches from the SpaceX API. Once the data has been acquired, it is parsed and added to a dataframe. Subsequently, the parsed data is filtered for specfic data values and wrangled to make sure it can be used for further processing afterwards.

*Tools: requests, Pandas, Numpy, datetime*

### 1-2-webscraping
Uses the requests library to scrape data about SpaceX launches from an external url (SpaceX launch table from wikipedia). The scraped data is then processed using Beautiful Soup to render it in a usable form. The dat is then turned into dataframes with the Pandas. Finally, the dataset is generated as a csv file.

*Tools: requests, Beautiful Soup, Pandas, Numpy*

### 1-3-spacex-data-wrangling
Extracted dataset on SpaceX launches is processed in this lab. First, Exploratory Data Analysis (EDA) is done on the dataset with additional data wrangling to make sure it is ready for subsequent processing by machine learning models. Then, some feature engineering is conducted to ensure that the dataset includes features that make machine learning tasks later more fruitful.

*Tools: Pandas, Numpy*

### 2-1 eda-dataviz
The dataset is further explored using different visualizations
