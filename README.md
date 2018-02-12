# getting-and-cleaning-data-coursera

This is the peer reviewed course project for the coursera course: Getting and Cleaning Data Coursera. The R script, run_analysis.R, 
does the following:

1) Downloads the dataset from the provided URL if it does not already exist in the working directory
2) Load the activity and feature info from the downloaded file
3) Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4) Loads the activity and subject data for each dataset, and merges those columns with the dataset
5) Merges the two datasets together to form one complete dataset
6) Converts the activity and subject columns into factors
7) Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8) The end result is shown in the file tidy.txt.
