# IBM Data Analytics with Excel and R Professional Certificate
## Data Science with R Capstone Project

This repository contains the various notebooks and the final presentation completed during the course Data Science with R Capstone Project for IBM's Data Analytics with Excel and R Professional Certificate on Coursera. The Capstone project utilizes publicly available biking data for Seoul and other cities to determine the impact of weather and other factors on bike rentals.

### 1-1-data-collection-apicall
Current weather data for several cities as well as weather forecasts for the next 5 days are collected from the OpenWeather API. The data received from the API is processed so that it is ready for use in the laer stages of the project.

*Tools: httr*

### 1-2-data-collection-webscraping
Bike rental data for several cities is webscraped and stored for future processing.

*Tools: rvest*

### 2-1-data-wrangling-with-regex
Bike rental data that was webscraped previously is cleaned and processed for later use in the project by making use of regular expressions.

*Tools:stringr, tidyverse*

### 2-2-data-wrangling-with-dplyr
The Seoul bike-sharing demand dataset for the project is wrangled for missing values, normalization and for replacement of categorical variables with indicator variables with dlyr from the tidyverse package.

*Tools: dplyr, tidyverse, caret*

### 3-1-ggplot2-EDA
The Seoul dataset is explored using data visulaiations from ggplot2. The Exploratory Data Analysis (EDA) provides important insights about data distribution and correlations between features in the dataset.

*Tools: ggplot2, tidyverse*

### 3-2-SQL-EDA_SQlite
The Seoul dataset present in a database is queried using sqlite through R. SQL Queries are run on the dataset to draw important insights.

*Tools: RSQLite*

### 4-linear-models-baseline
The dataset is analysed using linear regression models to determine the impact of various weather and date factors on the number of bike rentals for seoul using the tidymodels package. The results are visualized for ease of understanding.

*Tools: tidymodels, tidyverse, stringr*

### Final Presentation
The Final Presentation includes all relevant aspects of the project, starting from the initial thought process, to the various stages of data collection, wranglig, EDA and modeling. The final results and insights drawn are also prsent along with an appendix including all the relevant code snippets.
