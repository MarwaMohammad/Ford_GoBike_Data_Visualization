# Ford-GoBike-Data-Visualization Project

## Introduction

Ford-GoBike dataset includes information about individual rides made in a Bikesharing system

## Dataset Wrangling
#Here all the required packages.
import seaborn as sns
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline df = pd.read_csv('201902-fordgobike-tripdata.csv')
This dataset has the following columns:,
-  duration_sec: The bike duratio in seconds.,
-  start_time,   
-  end_time,
-  start_station_id,
-  start_station_name,
-  start_station_latitude,
-  start_station_longitude,
-  end_station_id,
-  end_station_name,
- end_station_latitude,
- end_station_longitude,
- bike_id,
- user_type,
- member_birth_year,
- member_gender,
- bike_share_for_all_trip

## Wrangeling
This dataset requires wrangeling since it has the following:
- There are some None values which should be removed.
- The datatype for some columns should fixed.
- Adding some columns which are necessary to do our insights.
- Removing some columns which are not necessary for our analysis

## Questions
- What is the relation between "gender_type, user type, age" and the count of shares. 
- What is the relation between "gender_type, user type, age" and the duration of share.
- What is the names for 1st 10 stations' names.
- The patterns for the duration with each gender male, female, others.
- The discription of share count pattern every day, and every weekday name.


In exploration step I did the following to answer the questions:
- Univariate visualization.
- Bivariate visualization.
- Multivariate visualization.


## Conclusion

From above explorations, we can summerize the followings:
- The Male has higher percentage "74.6%" than Female "23.3%" or other"2.6"  in using the Bikesharing.
- The Subscriber user type has a higher percentage 90.5% than Customer "9.5%" in using Bikesharing.
- More than 70% of ages who use the Bikesharing system is from 20 to 50.
- Most of Rides are on weekdays Monday, Tuesday, Wedensday, Thrusday, Friday but the least Rides on Weekdays Saturday, and Sunday.
- Most of rides between 7 am to 7 pm.
- pepole who was born after 1965 to 2000 who use the Bikesharing system more and longer than who born before that.
- The People from 20 to 55 use Bikesharing System more and loger than older ages.
- Others use the Bikesharing for longer time than males or females.
- Cusotmer user type use the Bikesharing System longer than the Subscriber user type on average.
- Usually Duration avergae for week ends "Saturday and Sunday" is longer than durations on work days.
- The duration on average between 1:30 to 3:30 is longer than the durations at any other hour.
    


```python

```
