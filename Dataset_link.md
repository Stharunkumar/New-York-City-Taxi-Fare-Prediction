# New-York-City-Taxi-Fare-Prediction
The dataset here consists of historical data pertaining to fare amounts (inclusive of tolls) for taxi rides in New York City. There are various attributes here including the fare amount, pickup times, pickup and dropoff co-ordinates and the passenger count!
The key idea here is if we can build a model on this datset to predict the potential taxi fare for a future taxi ride in NYC given that we know the other attibutes except fare

Main Objective: Given a ride's pickup time, pickup and dropoff coordinates along with the total passengers riding, build a model to predict the fare for a NYC taxi (regression)

Load and View the Dataset:
There are over 50 million datapoints in this dataset! We load around 10 million datapoints for this case study
The data is available at https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data from where you can download it.
We recommend using the kaggle API and the following command via CLI to get it.
      kaggle competitions download -c new-york-city-taxi-fare-prediction
