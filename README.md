---
title: "Getting and Cleaning Data - Course Project - Readme"
---
##

Main script file is run_analysis.R

The script read in training datasets under ./train/

X_train.txt - measurement datasets
y_train.txt - subject data for measurement
subject_train.txt - subject identifer, each row identify the activity performed by the subjects, Range from 1 to 30.
files under ./train/Inertial Signals contains raw data 

Test datasets are under ./test/ with the same file structure.

activity_labels.txt - contains description labels for the activity data.
features.txt - contains variable names of the measurement variable.
features_info.txt - contains descriptions of the variables.

The filename of the tidy processed data is "UCI_HAR_tidy.csv" which is a csv file.