#INTRODUCTION
This codebook explains the functions used in run_analysis.R

The code follows the flow:
1) Set the working directory
2) Load needed libraries
3) Read files and store them in variables
4) Extract required data per instructions
5) Combine the data
6) Write the final tidy file


#Load libraries that will be used in the R Script

require("data.table")
require("reshape2")

# Variables used for reading files
activity_labels 
features 
X_test 
y_test
subject_test
X_train
y_train
subject_train

# Other rVariables
id_labels   
data_labels
melt_data 

# Bind data
test_data - cbind of required data
train_data - cbind of required data
data - rbind of the above



