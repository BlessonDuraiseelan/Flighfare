# Flightfare Prediction App

This webapp is developed to predict the flightfare prices travelled across the Indian cities.
Here the user inputs details like Departure Date, Arrival Date ,Destination, Source,Stoppages and airline which are useful in predicting the prices.
The app is built using flask and deployed in the web using Heroku.

# Dataset and Modelling 
The dataset for the project is taken from Kaggle, and it is a time-stamped dataset so, while building the model, pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The various features in the dataset were:

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

After importing the data and applying pre processing techniques in the dataset we drew insight by plotting various graphs and visualisations that provided the information required to understand the data. The pre processing included converting the data columns into categorical columns as the date parameter cannot be used to predict. The pre processing was done on both train as well as test data. We also drew much insight on the type of information and the co relation of the data related to airlines and other parameters.

Since we have to predict a continous variable we need to use a regression algorithm. Decison Tree Regressor and Random Forest Regressor were used to use the availabe data and predict the values. Random Forest Regrssor gave the better score.
After using the data and checking various metrcis using Cross Validation Random Forest Regressor was chosen to be used on the data and the model was saved as pickle file.
The pickle file will be further used for processing in the flask file.

# Development and Deployment
The Programming language used was Python.

The Web Framework used was Flask.

Deployment in the web was done by Heroku.

![image](https://user-images.githubusercontent.com/76935226/140321990-66ca178d-fe7c-49a4-abf8-a27f0da6fbc8.png)                     ![image](https://user-images.githubusercontent.com/76935226/140322314-34afda85-34fa-4413-be2c-a24ff57c61f6.png)
![image](https://user-images.githubusercontent.com/76935226/150634420-34207f18-c7c7-4694-b08b-e5d02dc78d41.png)
![image](https://user-images.githubusercontent.com/76935226/140322080-5ddf17b2-b7b6-4724-86d0-16413303dedf.png)  
![image](https://user-images.githubusercontent.com/76935226/140322396-2eebd843-25cc-4ce9-bb3b-9060f59e5ee4.png)




# Chekout the app at the given link.
https://airticketvalue.herokuapp.com

![Screenshot (166)](https://user-images.githubusercontent.com/76935226/148753234-6726bee3-b57e-4562-87da-653f5a83a1d0.png)
![Screenshot (167)](https://user-images.githubusercontent.com/76935226/148753251-6f0e1f60-5da1-4b61-8368-086f3f7c2520.png)


