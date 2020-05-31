# Surfs_up

Surf's Up with Advanced Data Storage and Retrieval

# Challenge

## Objectives

1. Determine key statistical data about the month of June.
2. Determine key statistical data about the month of December.
3. Compare your findings between the month of June and December.
4. Make 2 or 3 recommendations for further analysis.
5. Share your findings in the Jupyter Notebook.

## Instructions

1. Identify key statistical data in June across all of the stations and years using the describe() function.
2. Identify key statistical data in December across all stations and years using the describe() function.
3. Share your findings in the Jupyter Notebook with a few sentences describing the key differences in weather between June and December and 2-3 recommendations for further analysis.

## Analysis

- Share your findings in the Jupyter Notebook with a few sentences describing the key differences in weather between June and December and 2-3 recommendations for further analysis.
- Find the code in climate_analysis (<https://github.com/keyoumao/surfs_up/blob/master/climate_analysis.ipynb>).

1. For temperature (F):

|   | count | mean | std | min | 25% | 50% | 75% | max |
|---|---|---|---|---|---|---|---|---|
| June | 1700  | 74.9 | 3.3 | 64 | 73 | 75 | 77 | 85 |
| December | 1517 | 71.0  | 3.7 | 56 | 69 | 71 | 74 | 83 |

**Q3 - Q1 = 77 - 73 = 4 (June) vs. Q3 - Q1 = 74 - 69 = 5 (December)**

From this table, we can find that June has a higher average temperature, smaller standard deviation, and more data with a higher number of samples at higher temperatures.

2. For precipitation (days):

|   | count | mean | std | min | 25% | 50% | 75% | max |
|---|---|---|---|---|---|---|---|---|
| June | 1574  | 0.14 | 0.34 | 0 | 0 | 0.02 | 0.12 | 4.43 |
| December | 1405 | 0.21  | 0.54 | 0 | 0 | 0.03 | 0.15 | 6.42 |

**Q3 - Q1 = 0.12 - 0 = 0.12 (June) vs. Q3 - Q1 = 0.15 - 0 = 0.15 (December)**

From this table, we can find that June has a lower average precipitation days, smaller standard deviation, and more data with a lower number of samples at lower precipitation days.

3. Base on the analysis on temperature and precipitation days, we recommend the ice cream shop could be open during June due to higher average temperature and lower average precipitation days.
