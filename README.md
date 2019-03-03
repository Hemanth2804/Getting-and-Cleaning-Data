# Getting-and-Cleaning-Data
Coursera - Getting and Cleaning Data - Course Project

Course project for the Getting and Cleaning Data Coursera course.
`run_analysis.R`, does the following:

1. Download the dataset
2. Load the activity and feature information
3. This loads both the training and test datasets, keeping only those columns with a mean or standard deviation
4. Load the activity and subject data for each dataset, and merges those columns with the dataset
5. Merge the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is in the file `Hemanth - tidy dataset.txt`.
