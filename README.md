# Get_and_clean_data_assignment
Contains solution for getting and cleaning data course assignment.

Script processing steps:

1. Read feature names, activity names and subjects. Also read activity label data.
2. Use regular expressions to remove parentasis from feature names as well as ',' signs.
3. Read train and test datasets. Use feature names as columns names, add activities and subjects as new columns.
4. Merge train and test datasets.
5. Keep only columns that represent means and standard deviations of measures.
6. Use activity label data to replace numbers with activity names.
7. Group data by subject and activity.
8. Summarize - extract mean of all variables for every combination of mean and activity.


