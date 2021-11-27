# Getting-and-Cleaning-Data-Project
At the first step should create one run_analysis.R that does the following :
1. Create one datasets wwhich merges the training and the test sets
2. Extracts only the measurements on the mean and standard deviation for each measurement
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names
5. reates a second, independent tidy data set with the average of each variable for each activity and each subject

Step by step
1. Download the data source and put into a folder
2. Put run_analysis.R in the parent folder of UCI HAR Dataset
3. Then set it as your working directory using setwd() function in RStudio.
4. Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
