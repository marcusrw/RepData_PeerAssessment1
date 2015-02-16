# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

First, let's extract activity.csv from activity.zip, if we haven't already done
so.


```r
dataFilePath = "./activity.csv"
dataZipFilePath = "./activity.zip"

if (!file.exists(dataFilePath)){
    unzip(dataZipFilePath)
}
```

```r
## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
```
