The code works in a following way.

1. The data was downloaded in the working directory.
2. Load the activity labels and feature info
3. Training and test data sets were loaded and only mean and standard deviation were kept.
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
