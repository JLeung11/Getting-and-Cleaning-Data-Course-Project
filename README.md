# Getting-and-Cleaning-Data-Course-Project
This repository hosts the course project for the "Getting and Cleaning Data" course.  The source file is "run_analysis.R". Below is an overview of the R script:
  1.  Download the zip data set from "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip" and save it       to your local directory.
  
  2.  Unzip the file.
  
  3.  List all the files of UCI HAR Dataset folder.  The files used to load data are as follows: 
          a) test/subject_test.txt 
          b) test/X_test.txt 
          c) test/y_test.txt 
          d) train/subject_train.txt 
          e) train/X_train.txt 
          f) train/y_train.txt
          
  4. Load, read, and check the properties of the activity, subject and feature files.
  
  5. Merge the test and train sets to create a single data set by concatenating the data tables by rows, setting names to the variables,        and merging the columns to get the data frame Data for all data.
  
  6. Extract only the measurements on the mean and standard deviation for each measurement through subseting Name of Features by                measurements on the mean and standard deviation and subsetting the data frame Data by selected names of Features.
  
  7.  Use descriptive activity names to name the activities in the data set from "activity_labels.txt" file.
  
  8. Appropriately label the data set with descriptive variable names and create a independent tidy dataset that consists of the average        value of each variable for each subject and activity pair.

  9. Final data set is outputted as "tidydata.txt".
