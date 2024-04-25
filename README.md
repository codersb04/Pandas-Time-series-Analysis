# Pandas-Time-series-Analysis

This repository contain different functions and procedure to handle date and time using Pandas

### Date Time Index
- How we can convert an date time column to index column and plot the data for better understanding.
- Date file is 'aapl.csv'</br></br></br>

Reference: Pandas Time Series Analysis Part 1: DatetimeIndex and Resample, codebasics, https://www.youtube.com/watch?v=r0s4slGHwzE&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=1</br></br></br>

### Date Range
- Creating a Series of date and Time using date range with start and end date or with start data and number of periods
- Data used "aapl_no_dates.csv"</br></br></br>

Reference: Pandas Time Series Analysis Part 2: date_range, codebasics, https://www.youtube.com/watch?v=A9c7hGXQ5A8&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=2</br></br></br>

### Handling in between week holidays with date range
- Customizing the calender with Bank Holidays and weekends according to different Country.
- We can do this by updating the freq function of date_range according to the requirement
- Also we can use customised country calender and supply that as frequency</br></br></br>

Reference: Pandas Time Series Analysis 3: Holidays, codebasics, https://www.youtube.com/watch?v=Fo0IMzfcnQE&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=3
</br></br></br>

### Formatting different date time to single format
- Making use of 'to_datetime' method of pandas to format the date
- How to get Epoch time(Number of seconds passed since Jan 1,1960) from date and reverse</br></br></br>

Reference: Pandas Time Series Analysis 4: to_datetime, codebasics, https://www.youtube.com/watch?v=igWjq3jtLYI&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=4</br></br></br>

### Period and Period Index
- Creating a Period with year or set of date range
- We can get the start time end time of the period also if we can do maths on period with adding 1 or 2 which will gives us that number of months
- We can also make period Quaterly
- Performed an analysis on Walmart data 'wmt.csv'</br></br></br>

Reference: Pandas Time Series Analysis 5: Period and PeriodIndex, codebasics, https://www.youtube.com/watch?v=3l9YOS4y24Y&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=5</br></br></br>

### Time Zone Handling
- Two type of Date time Objects in Python
1. Naive (No timezone awareness)
2. Time Zone aware datetime
- we can get all the time zone from pytz library
- Also can use dateutil for getting the time according to zone. Difference between dateutil and pytz is pytz use zone from its library and dateutil uses all the time zone available in our system.</br></br></br>

Reference: Pandas Time Series Analysis 6: Timezone Handling, codebasics, https://www.youtube.com/watch?v=9IW2GIJajLs&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=6</br></br></br>

### Shifting and Lagging
- Using shift from pandas dataframe we can shift the data points forward or backward by giving positive and negative desired value respectively
- Use of shift is to calculate the percentage change or change in data in a range.
- We can also shift the date index forward or backward by giving freq='D' with shift
- Date used for practice is 'fb.csv'</br></br></br>

Reference: Pandas Time Series Analysis 6: Shifting and Lagging, codebasics, https://www.youtube.com/watch?v=0lsmdNLNorY&list=PLeo1K3hjS3uvMADnFjV1yg6E5nVU4kOob&index=7</br></br></br>







