# **PYBER ANALYSIS**

## **Overview and purpose the PyBer analysis: 
- Using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. 
- Using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. 
- Write a report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Resources
- File Source: ride_data.csv
- File Source: city_data.csv
- Software: Jupyter Notebook 6.4.8
- Library: Pandas
- Library: MatPlotLib
- Language: Python 3.7.13

## **Results**
	
The Summary DataFrame shows the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 

The Summary DataFrame is quite informative and helps us to draw the following conclusions:
- Urban cities generated the most rides and total fares by a considerable amount followed by Suburban cities and then Rural cities
- Urban cities also had the most drivers followed by Suburban cities then Rural cities. 
- Urban cities are also so heavily saturated by drivers, therefore the average fare per ride and fare per driver are much lower than the Suburban and Rural cities

Summary DataFrame

![Summary DataFrame](https://github.com/veenapu/PyBer_Analysis/blob/main/Analysis/Summary%20DataFrame.png)
 
Possibly due to higher population and higher usage of cabs in Urban cities, Total rides, Total Drivers and Total Fares increased compared to Suburban and Rural cities.

Therefore, Average Fare per Ride and Average Fare per Driver decreased.
The graph below shows that the Total Fare by City Type never intersects. Urban cities are always the highest grossing, followed by Suburban cities, then Rural cities. 

Each city type has an overall positive growth which shows the company is growing.

PyBer Fare Summary
 
![PyBer Fare Summary](https://github.com/veenapu/PyBer_Analysis/blob/main/Analysis/PyBer_Fare_Summary.png))

## **Summary**	

Here are my recommendations to the CEO for addressing any disparities among the city types:

1.	Gather information on ride origins so we can create some kind of a heat map to determine which areas in each city generate the most business. Then, have a feature in the app or resource to notify the drivers of these popular areas so they can arrive for rides in less time. Decrease in wait time will generate even more income for the company and provide a more efficient service.

2.	Research the spikes on the graph to determine the root cause for the increases in volume. Once the reason is narrowed down, resources can be allocated accordingly so that more rides can be made available on these high volume days whether it is due to the time of the day, weather or an event happening in the city.


3.	The company can also offer an incentive like a frequent rider option and get a discounted fare after a certain number of rides or a free ride for ‘x’ no of miles.  This can generate loyal client base for the company, which can be a source of steady income and profit.

With this client data, further studies can be conducted and various other options can be figured out and introduced periodically to increase income and profitability.
