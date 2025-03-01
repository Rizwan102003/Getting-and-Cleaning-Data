# Project Code Book

This document serves as a reference for the project, outlining how to access the dataset, execute the R script, and understand the transformations applied throughout the process.

## Accessing the Data

1. **Download the Dataset:**  
   - Retrieve the dataset from: [Human Activity Recognition Using Smartphones Data Set](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).  
   - Extract the downloaded file into your R working directory.  

2. **Running the R Script:**  
   - Execute the `run_analysis.R` script to process and clean the data.  

## Source Data Overview  

The dataset used in this project originates from the Human Activity Recognition Using Smartphones initiative. A complete dataset description is available at the official site: [Human Activity Recognition Using Smartphones Data Set](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).  

Direct download link: [UCI HAR Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).  

## Overview of the R Script  

The `run_analysis.R` script follows these key steps to process the dataset:  

1. **Loading and Merging Data:**  
   - Reads the training and test datasets along with associated feature vectors and activity labels.  
   - Assigns meaningful variable names.  
   - Merges all data into a single dataset.  

2. **Extracting Key Measurements:**  
   - Filters only the measurements related to mean and standard deviation.  

3. **Assigning Descriptive Activity Labels:**  
   - Maps numerical activity codes to human-readable activity names.  

4. **Renaming Variables for Clarity:**  
   - Updates dataset column names with descriptive variable names.  

5. **Creating a Tidy Dataset:**  
   - Generates a clean, independent dataset containing the average of each variable for each activity and subject.  
   - Saves the tidy dataset as `tidy_data.txt`.  

**Note:** The script assumes that all data files are extracted into the working directory without renaming.  

## Variable Descriptions  

- `x_train`, `y_train`, `x_test`, `y_test`, `subject_train`, and `subject_test` store raw data extracted from the source files.  
- `x_data`, `y_data`, and `subject_data` consolidate the training and test sets for analysis.  
- `features` contains descriptive names for `x_data`, which are assigned to the dataset columns.  

This document serves as a reference for understanding the dataset, transformations, and analysis steps.  
