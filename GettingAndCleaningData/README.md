Getting and Cleaning Data ReadMe file
---------------------------
1)First Download the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2)Then open R-Studio and use Source("run_analysis.R") command
3)There is going to be 2 output files
-merged_data.txt : contains CleanedData dataframe 
-AvgData.txt: contains result dataframe
4)use avgdata <- read.table("AvgData.txt") command to read the file which is independent tidy data set with the average of each variable for each activity and each subject