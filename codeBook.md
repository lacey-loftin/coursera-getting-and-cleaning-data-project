## Getting and Cleaning Data Project

Lacey Loftin

## Codebook

This codebook explains the code in run_analysis.R

### Description
Peer-graded assignment for the Getting and Cleaning Data Project 

### Source Data
A full description of the data used in this project can be found at [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

[The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)


## Here are the main steps in the code


- loading libraries

Read only the feature names that are required

- Read in the activity labels

- read test data 

- read train data

- bind all columns 

- bind all rows 

- label columns

- set descriptive activity labels

- select columns with Mean() and Std() only.

- create second tidy data of grouped means

- write grouped means to mytidydata.csv

###Output File:
### mytidydata.csv
