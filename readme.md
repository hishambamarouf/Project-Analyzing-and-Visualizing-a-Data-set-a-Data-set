# Exploring the 2019 FordGoBike dataset.
## by HishamBamarouf


## Dataset

> In the FordGoBike dataset, which was provided by udacity, i found various information about FordGoBikes, most notably:
    - duration_sec (Which is the duration of the trip in seconds)
    - user_type (Subscriber or Customer)
    - member_birth_year
    - member_gender (Male, Female or Other)
    - bike_share_for_all_trip (BikeShare is a transportation system that allows community members to quickly and conveniently rent a bicycle for short-distance use)<br><br>
> And to enhance the dataset for further use, we added the following information<br>
    - day_names
    - age
> Most of the issues with this dataset came from wrong datatype but we also found some other problems like:
    - Some entry's ages are more than 100 
    - All the 180k entries are at the date 2019-02 
    - The 'other' gender seems to have the highiest averages across all catagories even though they're the smallest one

## Summary of Findings

> After wrangling the data and visualizing it, we found the following, the bike market is mostly dominated by males at 75%, the average age of the bike user is mostly 25 to 45 with a peak at 34, The most active days in terms of duration are tuesday and thursday and the most inactive days are the weekends (Saturday and Sunday), BikeShare is mostly enabled by Male Subscribers, Customers are usually more active during weekends than subscribers, but subscribers are more active during weekdays, Customers have highier duration than subscribers.

## Key Insights for Presentation

> The most interesting insight i found was the weekday vs weekend activity, i've built heatmaps to compare ride amount and duration for each day of the week and found out that weekdays in general has more rides than weekends, the duration of trips on weekdays are highier than weekends, then i compared in terms of user type and found that customers are more active during weekends than subscribers, assuming they are tourists as compared to subscribers who might use bikes to get to work and school and such.
