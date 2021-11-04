# Flightfare Prediction App

This webapp is developed to predict the flightfare prices across the Indian cities.
Here the user input details like Dep Date, Arrival Date ,Destination, Source,Stoppages and airline which are useful in predicting the prices.
The app is built using flask and deployed in the web using Heroku.

# Dataset and Modelling 
The dataset for the project is taken from Kaggle, and it is a time-stamped dataset so, while building the model,  pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The various features in the dataset were:

Airline: The name of the airline.

Date_of_Journey: The date of the journey

Source: The source from which the service begins.

Destination: The destination where the service ends.

Route: The route taken by the flight to reach the destination.

Dep_Time: The time when the journey starts from the source.

Arrival_Time: Time of arrival at the destination.

Duration: Total duration of the flight.

Total_Stops: Total stops between the source and destination.

Additional_Info: Additional information about the flight

Price: The price of the ticket
