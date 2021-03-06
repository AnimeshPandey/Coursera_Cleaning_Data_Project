# Getting and Cleaning Data Final Project

This is the course project for the Getting and Cleaning Data Coursera course.

## Human Activity Recognition Using Smartphones Dataset

The data has been collected from a group of 30 volunteers within a range of age from 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist and different signals were recorded.

## The analysis of tidy data generation

The R script named `run_analysis.R` does the following tasks:

1. Download the dataset which represents the data collected from the accelerometers from the Samsung Galaxy S smartphone, if it does not already exist in the working directory
2. Load the activity and feature information
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is displayed in the file `tidy.txt` created by this script.
