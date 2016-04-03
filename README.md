# Coursera Getting and Cleaning Data Project

## Files

1. The R code `run_analysis.R`.
2. The documentation files `README.md` and `CodeBook.md`.
3. The resulting tidy data set `tidy_uci_har.txt` generated through the Coursera "Getting and Cleaning data" project.

## Data source

[Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Description

The R code `run_analysis.R` performs the following jobs:
* Downloads and unzips the data from the above repo in the working directory.
* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names.
* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

* The code book `CodeBook.md` describes the variables is `tidy_uci_har.txt`