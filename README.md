Getting and Cleaning Data Course Project

This is the course project for the Getting and Cleaning Data Coursera course.

Dataset: Human Activity Recognition Using Smartphones

The included R script, run_analysis.R, conducts:

    1) Download the dataset from web if it does not already exist in the working directory.
    2) Read both the train and test datasets and merge them into x(measurements), y(activity) and   
       subject, respectively.
    3) Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 
       'standard'(-std). Also, modify column names to descriptive. (-mean to Mean, -std to Std, and 
       remove symbols like -, (, ))
    4) Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, 
       replace y(activity) column to it's name by refering activity label (loaded step 3).      
    5) Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and 
       each activity. The result is shown in the file tidy_dataset.txt.

The files of this repository are: 

    - CodeBook.md: A code book that describes the variables, the data, and any transformations or work 
      that I performed to clean up the data.
    - run_analysis.R performs the data preparation and then followed by the 5 steps:
          - Merges the training and the test sets to create one data set.
          - Extracts only the measurements on the mean and standard deviation for each measurement.
          - Uses descriptive activity names to name the activities in the data set.
          - Appropriately labels the data set with descriptive variable names.
          - From the data set in step 4, creates a second, independent tidy data set with the average of 
            each variable for each activity and each subject.
    - FinalData.txt is the exported final data.
