# final_project_group_45

New York City publishes a number of open datasets for public consumption or use. Amongst them is a dataset consisting of calls to the 311 phone number for non-emergency services. Each call to 311 has a number of datapoints tracked and aggregated. 

In the first Jupyter notebook called Top10.ipynb, we presented the top 10 causes of calls to 311 are in ZIP code area 100019, and calculated how many total incidents of each of these 10 types there have been in the year 2020. We first filtered rows with zip code 10019 and get 'df_10019'. Then, we used the groupby function and sort value functions to rank the complaint type count in a descending order. Then we used `[:10]` to get our `top10`.

In the second Jupyter notebook called Parking.ipynb, we analyzed whether illegal parking incidents are a larger fraction of total 311 incidents in 10019 than they are in general. Specifically, we computed the total number of parking incidents `total_parking_count`, and the total number of all incidents `total_incident_count` across all ZIP codes, as well as the number of total incideng in ZIP 10019 `zip_incident_count` and the number of parking incidents in ZIP 10019 `zip_10019_count`. The fraction within ZIP 10019 is smaller than the total fraction of parking incidents across all ZIP codes, hence the bool `higher_parking_proportion`, which shows if the ZIP area has higher proportion of parking incidents than the global value, is False.


Group Name: Yibaifen
IEOR 4501 E  sec 002
Group members:
Meixuan Li-ml4550
Shulu Fu-sf3038