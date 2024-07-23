# Data Directory

## Overview
This directory contains the dataset used for analyzing the depression status of computer science students.

## Files
- **depression_status_dataset.csv**: The primary dataset used for the analysis.

## Dataset Description
The dataset includes various variables related to the students' demographics, academic performance, and mental health status, including:
- Age
- Gender
- SleepPerDayHours
- NumberOfFriends
- DepressionStatus (Levels: No, Sometimes, Yes)
- Other relevant variables

## Data Source
The dataset was collected from a survey conducted among computer science students to assess their depression status.

## Usage
1. Ensure the dataset is in the same directory as your R notebook.
2. Load the dataset using the following R code:

data <- read.csv("data/depression_status_dataset.csv")
