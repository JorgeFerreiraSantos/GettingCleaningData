README.md

Course design Obtaining and clearing data.

This repository is a submission by Jorge Ferreira Santos for the Obtaining and Clearing Data course project. 
It has instructions on how to perform the analysis on the Human Activity recognition data set.

Data set
Recognition of human activity using smartphones

A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

files
CodeBook.md a code book that describes the variables, the data and any transformations or work that has been done to clear the data

run_analysis.R performs data preparation and follows the 5 necessary steps, as proposed:

1. Merges training and test sets to create a data set.
2. Extract only the measurements in the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name activities in the data set
4. Properly labels the data set with descriptive variable names.
5. From the data set in step 4, it creates a second organized and independent data set with the average of each variable for each activity and each subject.

*. FinalData.txt is the final data exported after going through all the strings described above.# GettingCleaningData
