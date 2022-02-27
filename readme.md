# (Fordgobike Data exploration)
## by (Mohamed Hossam El_Din)


## Dataset

> This Dataset from February 2019 contains data about bike sharing system trips including the duration, start and end times and locations, riders' birth years and genders, whether they are customers or subscribers, and whether they are inrolled in bike_share_for_all program or not. The wrangling I made before starting included exclusion of 10k data points due to inconsistencies and missing values. I also dropped the columns that are not included in my investigation, so I was left with ( duration_min, start_hour, start_day, weekDay, user_type, member_gender, bike_share_for_all_trip, age).

> my feature of interest was the trip duration and I used the other features to see their impact on it.


## Summary of Findings

> I found that the average duration of customers is longer than that of subscribers in general. This is not affected by different week days, day hours, gender, or bike_share_for_all program. I also found that females consumes more time for their trips than males but not by much.

>  The mean trip duration was steady along weekdays to be around 11 minutes, however, it rises a little bit for weekends to be about 14 minutes. There was a very weak positive correlation between age and trip duration. The time range associated with the most frequent age for each gender is the same. However, I noticed that male age is more broader for that range than female age. Other gender age looks bimodal between 30 and 40.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
For my presentation, I started by showing the duration and day hours distributions. Then I moved to show how the average duration differs from day to day within the week. 

> Afterwards, I highlight the weak positive correlation between age and duration before I show how the mean duration differs by user type when it is plotted against week days or day hours. Finally, I finished by showing how the average duration differs by gender. 