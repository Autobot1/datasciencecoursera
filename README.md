A. Packages data.table and reshape2 are installed
B. Working directory is set to the place where data is stored
C. Activity and features data is read and the variables containing mean and standard 
deviation is extracted from features
D. X, Y, Subject test and training data is extracted, from X data only variables corresponding
to mean and std are taken, and the activity labels to Y data are assigned
E. All test and train data is combined using cbind and rbind
F. The data is transposed to long format keeping key vairables as subject Activity_ID and
activity_label using melt
G. Lastly, we dcast this data and calculate average value of every variable for 
each subject activity pair.