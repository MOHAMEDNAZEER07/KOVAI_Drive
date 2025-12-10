I have created a insight notebook giving insights with visualizations on the dataset to make it easier to understand the data.

there are 5 key insights in the insights.ipynb file.

**1 .Local Route vs Rapid Route Journeys**
**2 . Comparision of Mean and Standart deviation of Peak service and Rapid Route journeys**
**3 .Shcool time analysis**
**4 .Visualizing all services over time**
**5 .Relation between Local and Rapid Route journeys**

* from these insight i have found that the Rapid route journeys are more popular than any other mode of service.
* the peak Servise have a inconsistant ,unpredictability .
* the school time journeys have a significant peak during the school start and end times, indicating that a large number of students rely on public transport for their daily commute to and from school.
* the local and rapid route journey has a strong positive corelation , complement each other as part of the same transport system, and changes in total demand affect both at the same time. so no negative correlation between the two services is observed.




I have also created a time series forecasting script and a notebook to help with forecasting.
where i have analysed the data and chose the best forecasting model for the dataset, which is Sarima because of the seasonality of the data.

and i used the log to stabilize the variance of the data and make the forcasting of total number of journeys more accurate.

from the forecasting process 

first i found the data and the target variable which is the total number of journeys.

also i have find the seasonality of the data with a period of 7 days.

then i split the data into train and test sets.
then i fitted the sarima model on the training data and made predictions on the test data.

finally i evaluated the model using mean absolute error (MAE) and root mean squared error (RMSE) metrics to see how well the model performed.

i have also visualized the actual vs predicted values to see how well the model captured the patterns in the data.


