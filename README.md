# Flight_Price_Prediction

# Dataset Link

[Flight_Price](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)<br>

# Heroku Deployment link
https://flight-fare-prediction-001.herokuapp.com/


Created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.


Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable.

Optimized multiple Regression models using GridsearchCV to reach the best model.

Built a client facing API using flask

Codes and Resources Used

Python Version: 3.8.5

Packages: pandas, numpy, sklearn, matplotlib, seaborn, flask, json, pickle

For Web Framework Requirements: pip install -r requirements.txt

Problem Statement

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have 

often heard travelers saying that flight ticket prices are so unpredictable. As data scientists, we are gonna prove that given the right data anything can be predicted. Here you 
will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. Size of training set: 10683 records


Size of test set: 2671 records

FEATURES: Airline: The name of the airline.

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

