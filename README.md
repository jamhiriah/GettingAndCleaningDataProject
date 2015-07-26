Getting and Cleaning Data Course Assignment
---------------------------------------------------------------

Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 
<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>. 

Here are the data for the project: 
<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>.
The purpose of this project is to demonstrate an ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.
An R script called run_analysis.R is created that does the following. 
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

In this project, you find:

- *run_analysis.R* : the R-code run on the data set

- *tidy_data.txt* : the clean data extracted from the original data using *run_analysis.R*

- *CodeBook.md* : the CodeBook reference to the variables in *tidy_data.txt*

- *README.md* : the analysis of the code in *run_analysis.R*

##Basic Assumption
The R code in *run_analysis.R* proceeds under the assumption that the zip file available at <https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip> is downloaded and extracted in the working directory
