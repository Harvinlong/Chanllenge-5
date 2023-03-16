# PyBer City Type Analysis

## Purpose of this project:

Using both Pandas and Matplotlib to create a multiple-line graph that shows the total weekly fares for each city type. Then summarized the differences in data by city type and how those differences can be used by PyBer decision-makers.

## Process:
This set of instructions provides a clear and concise guide for manipulating ride-sharing data using the groupby() function and various methods in Pandas. The goal is to create a PyBer summary DataFrame that contains data on ride counts, the driver counts, total fares, and average fares by city type. 

<img width="617" alt="data-Module-5-Challenge-Challenge_Summary_DataFrame" src="https://user-images.githubusercontent.com/111480084/225506089-d96d8213-63d8-428c-b345-eae80d291bad.png">


The groupby() function is used to create a new DataFrame that shows the total fare amount for each date, followed by resetting the index and pivoting the DataFrame.

Then create a new DataFrame by using the loc method on a date range, resetting the index to a datetime data type, and checking the date data type. 

Finally, create a new DataFrame using the resample() function and graphed using the df.plot() method.

The y-axis label and the title are annotated, and the figure is saved in the "analysis" folder.

![data-5-1-challenge-total-fare-for-each-week-in-each-cell](https://user-images.githubusercontent.com/111480084/225506668-9376443e-e4b7-4fd4-9249-d2502c1bef45.png)

![data-5-1-challenge-average-fare-each-city](https://user-images.githubusercontent.com/111480084/225506690-18287bb0-4b3d-42ab-8193-2d79537193bc.png)

