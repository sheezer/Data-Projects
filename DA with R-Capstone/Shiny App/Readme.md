## Data Science with R Capstone Project

## R Shiny App for Predicted Bike Rental Demand

An R Shiny app that uses OpenWeatherAPI data along with the regression model created in the project to forecast bike rental demand. The app displays a city map along with plots for its forecasted weather, bike rental demand and impact of forecasted humidity on bike demand for the next 5 days. The app can be accessed at: https://sheezer.shinyapps.io/BikeRentalPredictionwithWeatherForecast/ . The app will time out after 15 minutes. It can be reaccessed through the link if that happens.

### model.csv
Contains coefficients for various factors impacting bike demand obtained through linear regression model during the project.

### model_2.csv
Contains coefficients for various factors impacting bike demand obtained through linear regression during the project. Includes polynomial terms as well.


### model_prediction.R
R file that has the code for running the linear regression model to predict bike demand.

### selected_cities.csv
Contains data on the cities displayed in the app.

### server.R
The server file for the R Shiny app.

### ui.R
The user interface file for the R Shiny app.
