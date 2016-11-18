Background
==========

The information in this code book describe the tidy.txt, which was
produced as a result of the Getting and Cleaning Data course on
Coursera.

Datasets and data cleaning procedures
=====================================

The files x\_train, y\_train, x\_test, y\_test, subject\_train and
subject\_test contain the data from the downloaded files.

The features file contains the column names which is used to label the
datasets. Then, the column search using grepl function is performed,
leaving only the appropriate columns.

The resulting file - allData.mean contains the relevant averages and
standard deviations which will be later stored in a tidy.txt file.

Data identifiers
================

Identifiers

subject - The ID of the subject test activity - The type of activity
performed when the corresponding measurements were taken

Activity Labels
===============

WALKING: 1 WALKING\_UPSTAIRS: 2 WALKING\_DOWNSTAIRS: 3 SITTING: 4
STANDING: 5 LAYING: 6
