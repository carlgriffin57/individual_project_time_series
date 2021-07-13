# individual_project_time_series 
## Analysis of Global Mean Surface Levels (GMSL) from 1880 - 2013 (monthly)

### PROJECT DESCRIPTION (taken from the source listed under Project Planning):
Global Average Absolute Sea Level Change, 1880-2014 from the US Environmental Protection Agency using data from CSIRO, 2015; NOAA, 2015.

Also NASA measures sea level around the globe using satellites. The Jason-3 satellite uses radio waves and other instruments to measure the height of the ocean's surface – also known as sea level. It does this for the entire Earth every 10 days, studying how global sea level is changing over time.

This data contains “cumulative changes in sea level for the world’s oceans since 1880, based on a combination of long-term tide gauge measurements and recent satellite measurements. It shows average absolute sea level change, which refers to the height of the ocean surface, regardless of whether nearby land is rising or falling. Satellite data are based solely on measured sea level, while the long-term tide gauge data include a small correction factor because the size and shape of the oceans are changing slowly over time. (On average, the ocean floor has been gradually sinking since the last Ice Age peak, 20,000 years ago.)”

### GOALS
To be able to make predictions of future GMSL

### DATA DICTIONARY
| Attribute | Definition                                      | Data type |
|-----------|-------------------------------------------------|-----------|
| GMSL      | Global Mean Sea Level in mm converted to inches | Float64   |


### PROJECT PLANNIG
- Data is acquired through a .zip file that was downloaded from https://www.kaggle.com/somesh24/sea-level-change

- Data was clean from the source.  No nulls, missing data, etc.

- Explore the data through visualizations.

- Train models.

- Evaluate models on train and validate datasets.

- Choose the model that performs the best.

- Evaluate the best model (only one) on the test dataset

### AUDIENCE - Fellow Data Science students

### INSTRUCTIONS FOR RECREATING PROJECT
- Read this README.md
 
- Download the modeling.py and final_notebook_time_series.ipynb into your working directory
 
- Run the final_notebook_time_series.ipynb notebook
 
### Takeaways

Of the 5 modeling techniques: 
- Last observed value
- Simple Average
- Moving Average
- Holt's Linear Trend
- Predict Based on Previous Cycle

The Predict Based on Previous Cycle performed the best with a RMSE of 0.
