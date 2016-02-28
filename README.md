# Run-Analysis

####################################################################
INTRODUCTION
####################################################################
The Run-Analysis script was an assignment for the Coursera Getting and Cleaning Data course. The purpose of this script is to get and clean data wearables data.

####################################################################
REQUIREMENTS
####################################################################
library(data.table)
library(reshape2)

####################################################################
SCRIPT EXPLANATIONS
####################################################################
The run_analysis.R script follows a simple flow: 
1) Load all the required libraries needed.
2) Read/load the data from the data supplied by UCI - activity_labels.txt, features.txt, x_test.txt, y_test.txt, and subject_test.txt
3) Get the standard deviation and mean per the instructions for the assignment
4) Once the above is accomplished, combine the required data into test_data and apply the appropriate labels.
5) Finally, once all the data is extracted, labels applied, etc, write the file.
