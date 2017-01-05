##Instructions for the usage of the code
#### This project is submitted for the final submission for the *Getting and the Cleaning Data*


The script in the submission does the following:

*Download the file if it is not already available in the folder.
*Load the activity and features info from the files.
*Loads both the training and test datasets from the directory, keeping only those columns which reflect a mean or standard deviation
*Loads the activity and subject data for each dataset, and merges those columns with the training and testing datasets
*Merges the two datasets from step 4
*Converts the activity and subject columns into factors from the features table specified
*Creates a tidy dataset that consists of the mean value of each variable for each subject and activity pair.
 

 The end result is  saved into the ***tidy.txt*** file in the same working directory.