# Getting-and-Cleaning-Data-Course-Project

This R script, run_analysis.R,  is to create a tidy data set required by the following instructions:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The following variables are used in the R script:
1. x_train, y_train, subject_train: three tables read from the folder "train" of the dataset provided
2. x_test, y_test, subject_test: tables from the folder "test"
3. subject: column name of the subject tables
4. code: column name of the y tables
