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

Decison Tree Regressor and Random Foresrt Regressor were used to use the availabe data and predict the values.
After using the data and checking various metrcis Random Forest Regressor was chosen to be used on the data and the model was saved as pickle file.

# Development and Deployment
The app was developed  with the help of Python for coding and HTML/JS/CSS for Frontend.
The Web Frameworks used was Flask and Deployment in Heroku.

![image](https://user-images.githubusercontent.com/76935226/140321990-66ca178d-fe7c-49a4-abf8-a27f0da6fbc8.png)         ![image](https://user-images.githubusercontent.com/76935226/140322314-34afda85-34fa-4413-be2c-a24ff57c61f6.png)

![image](https://user-images.githubusercontent.com/76935226/140322080-5ddf17b2-b7b6-4724-86d0-16413303dedf.png)



# Chekout the app at the given link.
https://airticketvalue.herokuapp.com
