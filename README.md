# UDACITY_Communicate_Data_Findings
UDACITY Project - Unit 5: Communicate Data Findings

# Ford GoBike System Data Exploration
## by Gabriel Cárdenas


## Dataset

> The dataset that I selected is the Ford GoBike System Data.

> The dataset to be analyzed is based on the ride data of the company Bay Wheels for public use. The dataset before being polished contains the data of 154,967 anonymous trips with 13 features that are:

    - Duration of the ride (seconds)
    - Start time and date (and) - Finish time and date
    - Identification of the starting station (and) - End station identification
    - Departure station name (and) - End station name
    - Departure station latitude (and) - Length of departure station
    - Final station latitude (and) End station length
    - Bike ID
    - Type of user (subscriber or consumer - "Subscriber" = Member or "Consumer" = Casual)

> After cleaning the dataset, this consists of 154771 duration ofrides bikes and their features. The features included the bike type, start date and time, customer type, day_of_the_week, day, duration_min, distance_km). One hundred ninety-six data points were removed from the analysis due to inconsistencies or missing information.

> In this investigation I wanted to look at the characteristics of bike rides that could be used to predict their how long is the average of bike rides, when are most rides taken in terms of the day of the week and hour of the day, and if the cutomer type is relevant about this.

> The average duration of bike rides after cleaning is 20,26 minutes and the average distance traveled is 2,42 kilometers.


## Summary of Findings

> We have a relationship between duration of the bike rides and their distance traveled, which increases positively until 30 minutes and then decreases positively in the same proportion.

> We have a peak of 9 km traveled for a duration of bike read of 30 min.

> All the data is from July of 2020, so htat we can't incorporate these in our statistics.

> The highest number of services in terms of day of the week is on Saturday, and in the second place on Sunday.

> Majority of the users are casual instead of mmember / suscriber, but there don't appears to have a relationship between these and duration or distance traveled of the bike rides.


## Key Insights for Presentation

> The Key insights for the presentation are the following:

- Rides duration in the dataset take on a very large range of values, from 0 minutes at the lowest, to about 1439 at the highest. Plotted on a logarithmic scale, the distribution of duration column takes on a unimodal shape. We observe that there are a big peak of quantity of bike rides with a duration about 12 minutes more or less, and the majority of the bike rides are between 3 minutes and 60 minutes aproximately.

- Distance traveled is a measure of each bike ride. A large proportion of values of distance, from 0 at the lowest, to about 6802 at the highest. Plotted on a logarithmic scale, the distribution of distance column takes on a bimodal shape with a high peak at the beginning. Most of the bikes rides respectively the total of the data have a greater duration of 6 km and the majority of the ride bikes have a very short distance traveled, between 100 and 200 meters.

- `Distribution of the customer type, hour of the day and day of the week:` Three features are categorical, so we see the differences in proportions between them, noting that the majority customer type is of a case type of 92867 records compared to the subscriber with 61904. We also noted that the rush day of the service is on Saturday and a little lower portion on Sunday. We also noted that the rush hour normally is at 5pn.
    - `CUSTOMER TYPE:` We observe that the majority of clients are casual with 50% more than subscribed clients We observe that more or less twice as many electric bikes were used compared to docked bikes.
    - `BIKE TYPE:` We observe that more or less twice as many electric bikes were used compared to docked bikes.
    - `HOUR OF THE DAY:` We observe that the rush hour is at 5 pm and the majority of ride bikes is between the 7 am and 9 pm.
    - `DAY OF THE WEEK:` We bserve that the majority of ride bikes are in Saturday and in second place in Sunday, followin of Friday. During the week there are fewer amounts of bike rides and follows a slightly ascending line from Monday to Friday

- `Duration vs. Distance:` Plotting duration on a scale and taking an approximately linear relationship we note that as in start for short durations the longer duration proportionally the more distance is traveled with high increment, but from about 30 minutes it descends in the same way. We also note that the peak of the relationship indicates that the average of duration for the maximum distance travelled is about 30 minutes with an distance about 9 kilometers. We observe that most of the bike rides are between 0 and 60 minutes and there are an ascending correlation line of distance traveled until reaching the duration of 30 minutes and then comes down, so there are a peak in durations of 30 minutes with a distance travaled of about 9 km more or less.

- `Duration vs. Distance by Customer Type:` We note the interaction effect visible between duration, distance and customer type, where as I could see before the ratio of duration to the distance traveled increases to a maximum peak to 30 minutes of about 10 kilometers traveled and then descends in the same proportion, and it is also noted that this relationship is maintained regardless of the type of customer that is using the service. We observe that the type of client hardly interferes in the relationship between the duration of the bicycle ride and the distance traveled following more or less the same pattern, but would tell although with a greater number of rides for casual clients because they are the ones who use the service the most

- `Duration and Customer Type by Bike Type:` Plotting duration and customer type by bike type we notice there is not a substantial relationship between duration of the ride and if the customer is a member or casual. We also see that this relationship doesn't exist either for the bike type.

