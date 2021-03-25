DYNAMIC PRICE PREDICTION OF AIRLINES
Problem Statement:
	Develop a machine learning model to predict the airline price using the features provided in the dataset. 
Problem Overview:
Airline companies are following the dynamic pricing model. They have fixed number of seats in their plane. They are following the dynamic pricing strategy for selling seats to increase the revenue. The pricing will change based on the demand. The demand is dependent on many factors such as holiday, peak time, short/long route, number of stops, economy class etc,. Airlines have to model the demand, so that they can sell all the seats with more profit. Modelling the demand is critical because poor modelling may leave more seat empty or lead to less revenue. 
The objective of this project is to model the airline price change using the different features.  This predictive model will help the passenger to make purchasing decisions by predicting how air ticket prices will evolve in the future.
The following three files will be provided to work on this project

Train data : TRAIN.xlxs
Test data: TEST.xlxs
Submission data format: OUT_SAMPLE.xlsx

9000 observations are used for training and 1683 data is provided for testing the model. This dataset contains 10 following independent features to train a predictor (Price).

Airline: The name of the airline.
Date: The date of the journey
Departure Station: The source from which the service begins.
Arrival Station: The destination where the service ends.
Route map: The route taken by the flight to reach the destination.
Departure Time: The time when the journey starts from the source.
Arrival Time: Time of arrival at the destination.
Journey Time: Total duration of the flight.
Stops: Total stops between the source and destination.
Extra_Info: Additional information about the flight

Perform EDA and Feature Engineering:
Exploratory Data Analysis and Visualizations need to perform on the input features, to understand the characteristics of data. One can also think of extracting/deriving few more features from the data. Also, at the same time, the unwanted features can be dropped.  Proper pre-processing (treating NaN, cleaning, structuring, scaling/normalizing) will lead to better prediction.  Statistical testing and correlation analysis will help to understand the significance of feature sets. 
Apply Machine Learning Algorithms:
At the end of performing the EDA, one must get the clarity over which predictive Machine Learning algorithm can be applied on the data to predict the airline price. Applying all the possible ML techniques and tabulating the results in-terms MSE, RMSE, R-square etc., will give the understanding about how different ML algorithms are performing on this dataset. Compare the typical traditional algorithms output versus the tree and boosting based techniques. 
Regularization and Parameter Tuning
The prediction model output reliability can be improved using regularization techniques and parameter tuning. One can play with the different parameters for each algorithm, using GridSearchCV and RandomSearchCV packages to identify the optimal values which produce the maximum performance. 

Save and Load the Predictive Model:
Finally, the developed predictive model can be permanently saved in hard-drive and whenever the new data to be tested, this saved model alone can be loaded and applied on test data to predict the output. 


