# Exploration-Analysis

The 2008 flight dataset contains reports of flights in the United State incorporating features like Year,Month,Day of Month,Day of Week,Departure time,CRS departure time.,Arrival time,CRS Arr time,Unique Carrier,Flight number etc. Initially this dataset first consisted of 2389217 entries with 29 features. The interesting features for this investigation only needs 12 variables therefore extracting this features from the flight data was necessary for the simplification of the process. The new data named as new_flight embodies the same number of entries with 12 columns.


## Summary of Findings

In the exploration process, The 6 columns ActualElapsedTime,AirTime,Origin,Dest,Distance and Diverted doesn't have relation with the analysis main feature which is arrival delay. From the other 6 columns,I understood arrival delay of a flight have a strong relationship with departure delay. As it can be seen under the bivariate section the scatter plot of these two variables shows a correlation. Arrival delay also show a correlation with weather delay, security delay, NAS delay and late aricraft delay. It's relation with these 4 variables wasn't easily identified as it was with departure delay. Finding the relation with these 4 features needed more exploration. I have used boxplot to explore more which resulted the distribution of the variables within there ranges have a correlation with the delay of flight arrival. 

Since arrival delay showed more correlation with departure delay, in the multivariate section, the plots show the weather delay, NAS delay,secuirty delay and late aricraft delaty with respect to the two variable(ArrDelay and Depdelay). On each plots in this section it resulted a correlation of the features on the graph.


## Key Insights for Presentation

For the presentation I would be polishing the distribution of each variables shown under the univarite section. Then I would show the bivariate relation of the features that result in have a relation with the main interest variable which is arrival delay using scatter plot since these variables are numerical. To add more information, illustrating the correlation of arrival delay and departure delay with weather delay, NAs delay,security delay and late aircraft delay using scatter plot for the two variables and non-positional encoding color for the third variable will show case more understanding of all the 6 variables.
