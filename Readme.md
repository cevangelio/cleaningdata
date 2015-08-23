The script run_analysis.R

    downloads the data from UCI Machine Learning Repository
    merges the training and test sets to create one data set.
    replaces activity values in the dataset with descriptive activity names.
    extracts only the measurements (features) on the mean and standard deviation for each measurement.
    appropriately labels the columns with descriptive names.
    creates a second, independent tidy dataset with an average of each variable for each each activity and each subject. In other words, same type of measurements for a particular subject and activity are averaged into one value and the tidy data set contains these mean values only. The processed tidy data set is also exported as csv file.

The script is parititioned into functions such that each function performs one of the steps described above. 
To run whole cleaning procedure, call clean.data function. 
The script also assumes that plyr library is already installed.
