# Exploration-Analysis

The 2008 flight dataset contains reports of flights in the United States, including features like Year, Month, Day of Month, Day of Week, Departure time, CRS departure time, Arrival time, CRS Arr time, Unique Carrier, Flight number, etc. Initially, this dataset first consisted of 2389217 entries with 29 features. The main features for this investigation only need 12 variables; therefore, extracting these features from the flight data was necessary to simplify the process. The new dataset new_flight embodies the same number of entries with 12 columns.


## Summary of Findings

In the exploration process, the six columns ActualElapsedTime, AirTime, Origin, Dest, Distance, and Diverted have no relation with the main feature. For the other six columns, I understood arrival delay of a flight has a strong relationship with departure delay, as shown in the bivariate section. The scatter plots and the added box plots result in arrival delay correlating with the weather delay, security delay, NAS delay, and late aircraft delay results in correlation. 

Since arrival delay showed more correlation with departure delay, in the multivariate section, the plots convey the relation of the weather delay, NAS delay, security delay, and late aircraft delay concerning the two variables (ArrDelay and Depdelay). Each plot in this section resulted in a correlating relation.


## Key Insights for Presentation

In the presentation, I would be polishing the distribution of each variable shown under the univariate section. Then I would indicate the outcome of the bivariate relation of the features with arrival delay using a scatter plot since these variables are numerical. To add more information, illustrating the correlation of arrival delay and departure delay with the weather delay, NAs delay, security delay, and late aircraft delay using a scatter plot for the two variables and non-positional encoding color for the third variable will showcase more understanding of all the six variables.
