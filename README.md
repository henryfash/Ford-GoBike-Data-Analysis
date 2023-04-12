# Ford GoBike system Exploratory Data Analysis and Explanatory Visualization

### Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There are 183412 trips and 16 features in the dataset. Most variables are numeric in nature, but the features start_station_name, end_station_name, user_type and member_gender are qualitative nominal variables. There are two users categories, Subscriber and Customer. <a href = "https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv">Download dataset</a>

### Summary of Findings

1. Univariate exploration: there are more trips during the weekdays and less trips during the weekends. There are more trips in the morning and afternoon than the night. There are more subscribers than customers. For the gender groups, the number of trips in male riders is about 3 times more than the number of trips in females. Most of riders fall into the age bracket 25 to 45 years old and the average duration of trips is around 11 minutes.

2. Bivariate exploration: there is a no significant correlation between age and duration of trips. Weekdays have the most trips than weekends. customers ride longer than subscribers

3. Multivariate exploration: irrespective of the user type, on average users with gender as Other take longer ride than female and male users, with male users taking laging behind female users. Female users above age 60 years take longer ride on average than any other gender.

### Key Insights for Presentation

The stations with the most trips are Market St at 10th St station, San Francisco Caltrain Station 2  (Townsend St at 4th St), Berry St at 4th St, Montgomery St BART Station (Market St at 2nd St), Powell St BART Station (Market St at 4th St), San Francisco Caltrain (Townsend St at 4th St) with over 2500 trips. User types play a key factor on the number of trips. For customers, there are more trips on weekends, and they take longer trips.

### Libraries
pandas, numpy, matplotlib, datetime, seaborn
