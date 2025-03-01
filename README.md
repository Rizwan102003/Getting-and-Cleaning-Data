# Peer-graded Assignment: Getting and Cleaning Data Course Project 2025

This repository contains the R script `run_analysis.R`, which processes and cleans data according to the project requirements. The objective of this project is to showcase the ability to gather, process, and tidy a dataset for further analysis. The dataset used in this project originates from the accelerometers of the Samsung Galaxy S smartphone.

**Submitted by:** SK MD RIZWAN

## Repository Contents

1. **`run_analysis.R`**  
   - Merges the training and test datasets into a single dataset.  
   - Extracts only the measurements related to mean and standard deviation.  
   - Assigns descriptive activity names to the dataset.  
   - Labels the dataset with meaningful variable names.  
   - Creates a final independent tidy dataset with the average of each variable grouped by activity and subject.  

2. **`CodeBook.md`**  
   - Provides details about the variables, dataset, and transformations applied during data cleaning.  

3. **`tidy_data.txt`**  
   - Contains the final tidy dataset with averaged values for each activity and subject.  

## Running the Analysis

To execute the script and generate the tidy dataset:

1. **Download the dataset**:  
   If not already available, download it from [this link](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and extract it to your working directory.  

2. **Run the script**:  
   Open R or RStudio and execute the `run_analysis.R` file. This will process the data and create the final `tidy_data.txt` file.  

## Dataset Information

The dataset used in this analysis is sourced from motion sensors embedded in the Samsung Galaxy S smartphone. Further details about the dataset can be found at: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).  

## Code Book

For more details about the dataset, variables, and transformation steps, refer to the `CodeBook.md` file.  

**Thank you!**
