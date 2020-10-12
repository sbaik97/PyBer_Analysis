# PyBer_Analysis
Creating and annotating graphs and charts using the Matplotlib library.

## Project Background

* Matplotlib has a rich set of features for creating and annotating charts that visualize data in a Data Series or DataFrame.
* This is a data analyst project at PyBer, a ride-sharing app company valued at $2.3 billion and we need to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization using Matplotlib and SciPy statistics.

* Here is the list of deliverables for the analysis of the PyBer analysis:

    - Perform exploratory analysis on data from large csv files.
    - Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
    - Determine the mean, median, and mode and create box-and-whisker plots that visualize the number of rides, the fares, and the number of drivers for each city type.
    - Create a pie chart that visualizes each of the percent of total fares, total rides, and total drivers for each city type.

* This analysis improves the access to ride-sharing service and determining the affordability for underserved neighborhoods.

## The process of project

* Read raw data in csv file.
* Clean and inspect data, correct inappropriate data.
* Merge datasets to create new DataFrame gathering more information.
* Perform calculations for key metrics use groupby() function.
* Visualize data with tables to tell story and showcase trends.

## Software/Tools/Libraries
* Python 3.7.6, Jupyter Notebook 6.1.4 with PanDas, NumPy, Matplotlib, and SciPy statistics.
* Data Source: city_data.csv, ride_data.csv.

## Results of project
1. The mean, median, and mode of the number of rides, the fares, and the number of drivers for each city type and create box-and-whisker plots



## Challenge

#### Challenge Goal

Create an overall snapshot of the ride-sharing data with key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type

#### Summary Table

![summary_table.JPG](/analysis/summary_table.JPG)

Summary Table Conclusion:
By comparing the average fare per rides between each city type, rural cities have highest average fare per ride than suburban and urban by around four dollars and 10 dollars, respectively.
For the column of average fare per driver, rural cities also perform well than suburban and urban cities by 40% and 230%. The reason is that the rides and drivers count of rural cities, significantly lower than urban and suburban cities. It leads to average values greater than urban and suburban.

#### Multiple-line Chart

![Challenge_Fig.png](/analysis/Challenge_Fig.png)

Multiple-Line Plot conclusion:
This multiple-line charts showcases the total fare per city type changes by times. The X axis shows date from 1/1/2019 to 4/28/2019, and total fare in Y axis. In that line chart, Urban cities have highest total fares all the time, and Rural cities are lowest all over time. Suburban's line is in the middle.

Furthermore, the urban's line shows there are several peaks in March and April. At the same time, the line of rural shows some correlation to Urban's line. For example in the first week of March, urban's total fares are over 2,500 dollars. In parallel to that, rural's line reaches the lowest point, less than 360 dollars.
