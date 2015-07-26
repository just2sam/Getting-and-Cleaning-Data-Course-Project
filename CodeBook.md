# Codebook for Getting and Cleaning Data Course Project


### Getting started

## Basic Assumption

The R code in run_analysis.R proceeds under the assumption that the zip file available at https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip is downloaded and extracted in the R Home Directory.

## Data Acquisition & Analysis process
* Read Supporting Metadata from the UCI HAR data set
* Read training data from the UCI HAR data set
* Read test data from the UCI HAR data set
* Merge the training and the test data sets into one data set
* The data columns are then given names based on the `features.txt` file.
* The activity identifiers are replaced with the activity labels based on the `activity_labels.txt` file.
* Appropriately labels the data set with descriptive variable names.
* The data is then grouped by subject and activity, and the mean is calculated for every measurement column.
* Finally, the summary dataset is written to a file, `dtTidy.txt`.

## More information
For more details, kindly refer to the `run_analysis.R`(run_analysis.R) file.






