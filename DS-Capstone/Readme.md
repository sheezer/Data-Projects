# IBM Data Scientist Professional Certificate
## Applied Data Science Capstone Project

This repository contains the various notebooks and the final presentation completed during the course Applied Data Science Capstone Project for IBM's Data Scientist Professional Certificate on Coursera. The Capstone project revolves around rocket launches of SpaceX. The data from different rocket launches and their success and failure is used to find the relatonship between launch success and different data features.


### 1-1-spacex-data-collection
Uses the request library to request launch data on SpaceX launches from the SpaceX API. Once the data has been acquired, it is parsed and added to a dataframe. Subsequently, the parsed data is filtered for specfic data values and wrangled to make sure it can be used for further processing afterwards.

*Tools: requests, Pandas, Numpy, datetime*

### 1-2-webscraping
Uses the requests library to scrape data about SpaceX launches from an external url (SpaceX launch table from wikipedia). The scraped data is then processed using Beautiful Soup to render it in a usable form. The dat is then turned into dataframes with the Pandas. Finally, the dataset is generated as a csv file.

*Tools: requests, Beautiful Soup, Pandas, Numpy*

### 1-3-spacex-data-wrangling
Extracted dataset on SpaceX launches is processed in this lab. First, Exploratory Data Analysis (EDA) is done on the dataset with additional data wrangling to make sure it is ready for subsequent processing by machine learning models. Then, some feature engineering is conducted to ensure that the dataset includes features that make machine learning tasks later more fruitful.

*Tools: Pandas, Numpy*

### 2-1-eda-dataviz
The dataset is further explored using different visualizations to plot relationships between different features. Important relationships re noted and then some further feature engineering is done.

*Tools: Plotly, Seaborn, Matplotlib, Pandas, Numpy*

### 2-2-eda-sql
The SpaceX dataset is explored further by making use of a sqlite database version of it. The sqlite version is queried using sql in Python to understand important aspects of the dataset.

*Tools: sqlite, Pandas*

### 3-launch_site_location
The data from different launch sites is plotted on Folium to better illustrate the relationship between launch success or failure and the location of the launch site. Important features around the launch site are noted.

*Tools: Folium, Pandas*

### 4-SpaceX_Machine Learning Prediction
The SpaceX dataset is run through different Machine Learning algorithms. The algorithms used are Decision Trees Classifier, Logistic Regression Classifier, Support Vector Machine and K-Neighbors Classifier. The accuracy for each algorithm is calculated and saved.

*Tools: Pandas, Numpy, Scikit-Learn, Matplotlib*

### Final Presentation
The final presentation which involves all the details of the processes and insights for the capstone project.
