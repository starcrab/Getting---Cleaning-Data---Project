---
title: "Getting & Cleaning Data - Course Project - CodeBook"
---

##

Main script file is run_analysis.R
----
Training datasets are under ./train/

X_train.txt - measurement datasets, contain 561 different measurements. Measurement is normalized with value from -1 to 1.
y_train.txt - subject data for measurement
subject_train.txt - asubject identifer, each row identify the activity performed by the subjects, Range from 1 to 30.
Files under ./train/Inertial Signals contains raw data

Test datasets are under ./test/
Structure is the same as training set

activity_labels.txt - contains description labels for the activity data.
features.txt - contains variable names of the measurement variable.
features_info.txt - contains descriptions of the variables.
----
run.analysis.R do the following 

1.Read in training & testing test, combine them into a full dataset.
2.Read in descriptive variable names from features.txt and add the variable names to the full dataset.
3.Subset meansurements on the mean and standard deivation for each measurement.
3.Read in subject & activity data, replace the activity variable with descriptive activity names.
4.Create a new tidy dataset that contain the average of each variable for each activity and each subject.
5.Merge subject, activity and the average variables into the tidy dataset.
6.Write the new tidy dataset to "UCI_HAR_tidy.csv" csv file.