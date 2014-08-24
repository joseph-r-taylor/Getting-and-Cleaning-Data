# Getting and Cleaning Data

## Course Project: Goals

Create one R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Course Project: Steps

1. Download the data source and put it into a directory on your local drive so that you have a ```UCI HAR Dataset``` directory in the same directory as your R code.
2. Create ```run_analysis.R``` and save it in the parent directory of ```UCI HAR Dataset```. Set that parent directory as your working directory using the ```setwd()``` function in RStudio.
3. Run ```source("run_analysis.R")```. The R code will generate a new file called ```tiny_data.txt``` in your working directory.

## Package Dependencies

```run_analysis.R``` will help you to install package dependencies automatically. Specifically, the dependencies are the ```reshape2``` and ```data.table``` packages. 