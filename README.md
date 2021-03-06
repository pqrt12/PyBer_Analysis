# PyBer_Analysis

# PyBer_Challenge

There are two parts of this new challenge:
- create a Summary table
- visualize total fares by city type.
## Part 1, Create PyBer Summary

- Read city, ride data files and store in panda DataFrames.
- combine DataFrames to a new DataFrame pyber_data_df.
- get total_rides, total_drivers, total_fares for each city type.
- calculate average fare per ride, average fare per driver for city type.
- create a summary DataFrames, formatted and display it.
## Part 2, Visualize Weekly Fares by City Type

Data processing and visualizing.
### data processing (and excises per instructions)
- per instructions, rename the DataFrame columns.
- per instructions, set the index to "Date" Column
- per instructions, create a new DataFrame with "Date", "City Type" and "Fare" columns.  
    note: column "City" is included, just for column delete excise next.
- delete Column "City" in the new DataFrame.
- create a DataFrame groupby() "City Type" and "Date", sum up "Fare"
- create a pivot table with index being "Date"
- keep given date range, and resample to weekly.
    note: 1st week is adjusted to 7 days.
### multi-line plot of weekly fares
- use specified style.
- use object-oriented interface.
- try to match existing color scheme.
- plot.  
    note: Date is week ending date.  

![PyBer Weekly Fares (2019)](https://github.com/pqrt12/PyBer_Analysis/blob/master/analysis/Fig8.png)

## Summary
From the summary table, about 80% of PyBer drivers work in Urban cities, close to 20% of drivers work in Suburban cities, a few percent of drivers work in rural cities.
The total rides, total fares are similarly decreasing among the three types of cities, in the order.
However, the decreasing rates are subsequently reduced (drivers, rides and fares). 
This pattern could also be seen from the average fare per ride and average fare per driver. Both increase in the order of urban cities, suburban cities, and rural cities.

For the first four month of 2019, PyBer's total fare for all cities types are relatively stable. Urban cities are the most important markets.


