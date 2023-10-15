# Capital Bikeshare: Bikesharing Analysis and Dashboard

## Analysis with Jupyter Notebook
### Defining Question
1. How is the trend in the number of bike-sharing rides in recent years?
2. What is the usage pattern of bike-sharing rides based on time of day?
3. What season has the highest bike-sharing rides?
4. What is the usage pattern of bike-sharing rides based on day of the week?
5. Are there any correlations between temperatures that indicate conditions when bike-sharing rides are high?
6. Does weather affect bikeshare usage?

### Insights and Findings
1. Count of bikeshare rides in 2012 are higher than in 2011. Both shows the same trend and seasonality, where count of bikeshare rides increased in the middle of the year and decrease at the beginning and end of the year.
2. For registered users rides, the count of rides shows peak at 8.00 and 17.00, indicating that registered users maybe used the bike to commute to work. For casual users rides, the count of rides starts to increase during the day and decrease during the night.
3. Bikeshare rides are the highest during summer season, and lowest during winter season
4. For registered users, the count of rides are higher during weekdays. In line with findings in question 2, registered users probably used the bike for commuting to work. For casual users, the count of rides are higher in weekend compared to weekdays, indicating casual users are using the bike for casual leisure on weekend.
5. Yes, there is moderate correlation between temperature and count of bikesharing rides. Count of rides are lowest during colder temperatures, which happen during winter, and the count of rides starts to increase as the temperature increase, which happened in summer. However, there is a "sweet-spot" or temperature condition when the count of rides are the highest, which happened between between 20 degC and 30 degC; this is mostly occured during Summer and Fall season. During the days with those temperature conditions, we can expect the count of bikeshare rides will be high.
6. Yes, during clear weather, the count of rides are significantly higher compared to during more violent weather.

## Dashboard with Streamlit

View the dashboard on streamlit could on this link: https://capital-bikeshare-alfikri.streamlit.app/

The dashboard shows the count of total rides across the year and season. It also shows the difference casual riders and registered rides use of the bikesharing service, based on hour and day of the week.
