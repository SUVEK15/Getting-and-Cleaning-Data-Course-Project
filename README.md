# Getting-and-Cleaning-Data-Course-Project
This is the project on Getting and Cleaning Data using dplyr and tidy packages

Following is the flow structure of the program being built

First by initialising the directory, the raw data is extracted into a data frame format into 9 different objects

Two sets of train and test data and subject_train and subject_test data are created

The next step is to bind these two data frames together by using the rbind function

The messy data is then converted into a tidy data package by using the tidy package functions

For better understanding of the tidy data table, the columns are renamed using the gsub function. The variables related to mean and standard deviation are extracted from the tidydata set and mean and standard deviation values are calculated for the same.

