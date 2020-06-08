# Getting and Cleaning Data Week 4 Project

This repository contains the R script and documentation for Coursera "Getting and Cleaning Data" Week 4 project.

## Code explaination:

The five steps:

1. Merges the training and the test sets to create one data set.
  - Reads the training an test datasets and merge them into one set
2. Extracts only the measurements on the mean and standard deviation for each measurement.
  - Creates a vector with the data from features.text (variables labels)
  - Filters variables based on "mean" and "std" measurements
  - Subsets dataset based on filtered variables
3. Uses descriptive activity names to name the activities in the data set
  - Merges selected variables, activity and subject columns 
  - Reads activity labels
  - Replaces activity codes by labels
4. Appropriately labels the data set with descriptive variable names.
  - Use colnames()
5. From the data set in step 4, creates a second, independent tidy data set with the average of each       variable for each activity and each subject.
  - Makes and writes a tidy data set, ordering columns by SubjectID and activityID
  
## Containded Files:
  - "Codebook.md": describes variables and data
  - "tidyData.txt": output
  - "run_analysis.R": code with explaination