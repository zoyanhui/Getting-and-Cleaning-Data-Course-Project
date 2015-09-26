# Getting and Cleaning Data Course Project
*For* [course project](https://class.coursera.org/getdata-032/human_grading/view/courses/975116/assessments/3/submissions) *of Getting and Cleaning Data in Coursera.*


R script for course project is in run_analysis.R file, created following the steps:
1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Instruction
1. Download [the data]( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) for the project

2. Unzip the zip data file in your work directory. There will be a directory called 'UCI HAR Dataset', and don't change any data in it.

3. Put the 'run_analysis.R' script file directly in the work directory.

4. Run the script, by ```source("run_analysis.R")```, after waiting for a while, a output file called 'tidy_data.txt' will be created in the work directory.

## Library Dependencies
The script 'run_analysis.R' needs two library, ```data.table``` and ```reshape2```.

If they are not in your R's installed packages,
will be installed automatically by the script.
Also, you can install the two packages before running the script by yourself.
