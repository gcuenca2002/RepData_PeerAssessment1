GC_RepData_PROJ1
Guillermo Cuenca

23 de junio de 2016

Introduction
R preparations
In this document code will be represented to show how the results have been achieved. Set the default of echo to be true throughout the document:

Load in packages
Working Directory
The data
Tidying the data


What is mean total number of steps taken per day?
For this part of the assignment the missing values can be ignored. 1. Calculate the total number of steps taken per day. 2. Make a histogram of the total number of steps taken each day. 3. Calculate and report the mean and median of the total number of steps taken per day. Then 1. Calculate the total number of steps per day using dplyr and group by date, and store in steps:


Calculate the mean and median of the total number of steps taken per day and store in mean_steps & median_steps:

What is the average daily activity pattern?
Make a time series plot (i.e. type = “l”) of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis).
Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?.
Then


Imputing missing values
Note that there are a number of days/intervals where there are missing values (coded as NA). The presence of missing days may introduce bias into some calculations or summaries of the data.

Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs).
Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.
Create a new dataset that is equal to the original dataset but with the missing data filled in.
Make a histogram of the total number of steps taken each day and calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data 
on the estimates of the total daily number of steps?


 Calculate the mean and median steps with the filled in values:


Are there differences in activity patterns between weekdays and weekends?
For this part the weekdays() will come handy. Use the dataset with the filled-in missing values for this part.

