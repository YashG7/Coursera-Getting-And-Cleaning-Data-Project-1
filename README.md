# Coursera-Getting-And-Cleaning-Data-Project-1
This is the project for the Getting and Cleaning Data course at Coursera.The objective is to prepare a tidy dataset that can then be used for later analysis and processing.The code for preparing data is in the run_analysis.R file.The final tidydata is in the tidydataset.txt file.   
The script run_analysis.R does the following:  
1. Download Samsung dataset and unzip it.
2. Reads the test and training datasets.  
3. Merges both the training and test data into a new data set.  
4. Subsets the dataset for only mean and standard deviation columns.  
5. Uses descriptive activity names to name the activities  present in the data set.  
6. Renames the columns of the dataset with appropriate names.  
7. Creates a new dataset with mean of each column for each activity and each subject  
8. Write the output in tidydataset.txt file  
