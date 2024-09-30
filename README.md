# NewYorkTaxiTripDuration
This project was assigned as a homework task in a Data Science course. It was aimed at analyzing taxi trip duration in New York City and building a model to attempt to predict this duration.

## Instruction for using the model
To use this model on your dataset you just need to run on python Class_Code.txt and load TripDurationPredicter.pkl using pickle. After this you can fit this model on new data, or just predict using model.predict(X).
X structure must be like:

 0   id                  1458644 non-null  object 
 
 1   vendor_id           1458644 non-null  int64  
 
 2   pickup_datetime     1458644 non-null  object 
 
 3   dropoff_datetime    1458644 non-null  object 
 
 4   passenger_count     1458644 non-null  int64  
 
 5   pickup_longitude    1458644 non-null  float64
 
 6   pickup_latitude     1458644 non-null  float64
 
 7   dropoff_longitude   1458644 non-null  float64
 
 8   dropoff_latitude    1458644 non-null  float64
 
 9   store_and_fwd_flag  1458644 non-null  object 
