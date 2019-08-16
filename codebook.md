run_anlysis.R script downloads and processes the data for the Getting Data and Cleaning data project

The data is downloaded and assigned to the file named Coursera_DS3_Final.zip

A series of read.table commands are executed to load in following data 
features 
activities 
subject_test 
x_test 
y_test
subject_train 
x_train 
y_train

The rbind funciton is used to merge the X and Y values from the training and test sets

The mean and std dev for each subject are extracted

The codes for each activty updated to full names

The output in FinalData.txt which is exported

