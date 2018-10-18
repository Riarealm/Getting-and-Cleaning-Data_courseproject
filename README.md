---
title: 'Getting and Cleaning Data : Course Project "README"'
author: "Marina. K"
date: "2018.10.18"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is the course project assinment for Getting and Cleaning Data course in Coursera.
In this project, 

This repositry contains the following files;
    -README.md : Explaining the overview of the data set. (This file)
    -run_analysis.R : The R code that implement preparing tidy data from raw data.
    -CodeBook.md : Introducing the script "run_analysis.R"
    -tidy_data.txt : The output of merged and extracted data set by implementing "run_analysis.R"

The data was collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Steps for preparing "tidy data"
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names.
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.