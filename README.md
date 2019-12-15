# spare_parts_price_prediction
Spare parts price prediction

Imagine you are into the business of selling spare parts across different locations in the world and want to manage your inventory efficiently to minimize costs.
The objective of the excercise is to help us build a model (statistical or machine learning) to predict next year's weekly demand.

Data
----
I have provided 5 <partid>_<locationid>.csv named files. 
Here, <partid> refers to an internal id of a part you sell. <locationid> refers to an internal id of a location where you sell this part.
Each row in the .csv file represents weekly demand of a spare part at a given location.
The first column partid represents an internal id of the part.
The second column locid represents an internal id of the location where part is sold.
The third column historybegdate represents the date in mm/dd/yyyy format.
The fourth column historyamount represents the demand of the given part at the given location for a given week.

Model Building
--------------
Please make sure you are able to predict future demand in multiple weeks at each step using your model 
Python as programming language.
Clean and really well documented code.
It would be nice to see the final approach and the intermediate approaches, models and experiments you did to get to the final model.

Submission
----------
Please plan to provide:
Forecast of weekly demand for next year in csv's named <partid>_<locationid>_forecast.csv for the 5 input csv files. 


Evaluation
----------
We will use below metrics to compare your model's performance. The lower these are the better.
Root mean square deviation (RMSE) https://en.wikipedia.org/wiki/Root-mean-square_deviation
Mean absolute percentage error (MAPE): https://en.wikipedia.org/wiki/Mean_absolute_percentage_error





