# Getting_and_cleaning_data
UCI HAR Dataset

## Course Project
You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps for this project

1. Download the data and unzip it. This will create a ```UCI HAR Dataset``` folder.
2. Set your working directory to be: ```UCI HAR Dataset``` in Rstudio.
3. Run ```source("run_analysis.R")```. It will generate a new file ```tidy_data.txt``` in your working directory.

## Dependencies for this project

You must first have installed the packages ```rshape2``` and ```datatable```.
The ```run_analysis.R``` will load the required packages.
 
