run_analysis.R
==============

This is a program submitted as course project for the Coursera course, Getting and Cleaning Data. This program analyses Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.  
First the row testing and training data is read and merged into a dataset. The original column names are replaced with the feature names and two additional columns are added: activity and subject. Subjects are the 30 volunteers carrying out activities of daily living, while activity refers on the six types of activities that each volunteers performed. 
The program extracts only the measurements on the mean and standard deviation for each measurement.
The tidy data set contains only the average of each variable for each activity and each subject.
Finally, a text file is created containing the tidy dataset (tidy.txt).
