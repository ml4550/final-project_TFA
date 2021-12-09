# final_project_group_45

New York City publishes a number of open datasets for public consumption or use. Amongst them is a dataset consisting of calls to the 311 phone number for non-emergency services. Each call to 311 has a number of datapoints tracked and aggregated. 

In the first Jupyter notebook called Top10.ipynb, we presented the top 10 causes of calls to 311 are in ZIP code area 100019, and calculated how many total incidents of each of these 10 types there have been in the year 2020. We first filtered rows with zip code 10019 and get 'df_10019'. Then, we used the groupby function and sort value functions to rank the complaint type count in a descending order. Then we use `:10` to get our `top10`.

In the second Jupyter notebook called Parking.ipynb, we analyzed whether illegal parking incidents are a larger fraction of total 311 incidents in 10019 than they are in general. Specifically, we computed the total number of parking incidents in your ZIP, and the total number of all incidents -- is this fraction greater than or smaller than the total fraction of parking incidents across all ZIP codes? Your answer should be in the form of a single bool called `higher_parking_proportion` which is True if your ZIP contains a higher proportion of parking incidents than the global value, and False otherwise. For instance, if there were 200 parking incidents in your ZIP, and 1000 total incidents in your ZIP, a rate of 20%, but the global parking incident rate was 3000 parking incidents out of 10000 total, a ratio of 30%, you would assign higher_parking_proportion = False.


```import pandas as pd```

Group Name: Yibaifen
IEOR 4501 E  sec 002
Group members:
Meixuan Li-ml4550
Shulu Fu-sf3038