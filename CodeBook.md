---
title: "Code Book"
author: "John Nguyen"
date: "10/19/2020"
output: html_document
---


## Summary Analysis
The final output for the analysis is contained in the text file tidydata.txt. This file reveals the aggregate of each activity and each subject for the measurement with mean and standard deviation. 

## 30 Subjects each take 6 activities
The 6 activities are:\
1.WALKING\
2.WALKING_UPSTAIRS\
3.WALKING_DOWNSTAIRS\
4.SITTING\
5.STANDING\
6.LAYING\

## Transformation to Final Data Set
1	actions	\
2	subjectID	\
3	timeBodyAccelerometer-mean()-X	\
4	timeBodyAccelerometer-mean()-Y	\
5	timeBodyAccelerometer-mean()-Z	\
6	timeBodyAccelerometer-std()-X	\
7	timeBodyAccelerometer-std()-Y	\
8	timeBodyAccelerometer-std()-Z	\
9	timeGravityAccelerometer-mean()-X	\
10	timeGravityAccelerometer-mean()-Y	\
11	timeGravityAccelerometer-mean()-Z	\
12	timeGravityAccelerometer-std()-X	\
13	timeGravityAccelerometer-std()-Y	\
14	timeGravityAccelerometer-std()-Z	\
15	timeBodyAccelerometerJerk-mean()-X	\
16	timeBodyAccelerometerJerk-mean()-Y	\
17	timeBodyAccelerometerJerk-mean()-Z	\
18	timeBodyAccelerometerJerk-std()-X	\
19	timeBodyAccelerometerJerk-std()-Y	\
20	timeBodyAccelerometerJerk-std()-Z	\
21	timeBodyGyroscope-mean()-X	\
22	timeBodyGyroscope-mean()-Y	\
23	timeBodyGyroscope-mean()-Z	\
24	timeBodyGyroscope-std()-X	\
25	timeBodyGyroscope-std()-Y	\
26	timeBodyGyroscope-std()-Z	\
27	timeBodyGyroscopeJerk-mean()-X	\
28	timeBodyGyroscopeJerk-mean()-Y	\
29	timeBodyGyroscopeJerk-mean()-Z	\
30	timeBodyGyroscopeJerk-std()-X	\
31	timeBodyGyroscopeJerk-std()-Y	\
32	timeBodyGyroscopeJerk-std()-Z	\
33	timeBodyAccelerometerMagnitude-mean()	\
34	timeBodyAccelerometerMagnitude-std()	\
35	timeGravityAccelerometerMagnitude-mean()	\
36	timeGravityAccelerometerMagnitude-std()	\
37	timeBodyAccelerometerJerkMagnitude-mean()	\
38	timeBodyAccelerometerJerkMagnitude-std()	\
39	timeBodyGyroscopeMagnitude-mean()	\
40	timeBodyGyroscopeMagnitude-std()	\
41	timeBodyGyroscopeJerkMagnitude-mean()	\
42	timeBodyGyroscopeJerkMagnitude-std()	\
43	frequencyBodyAccelerometer-mean()-X	\
44	frequencyBodyAccelerometer-mean()-Y	\
45	frequencyBodyAccelerometer-mean()-Z	\
46	frequencyBodyAccelerometer-std()-X	\
47	frequencyBodyAccelerometer-std()-Y	\
48	frequencyBodyAccelerometer-std()-Z	\
49	frequencyBodyAccelerometerJerk-mean()-X	\
50	frequencyBodyAccelerometerJerk-mean()-Y	\
51	frequencyBodyAccelerometerJerk-mean()-Z	\
52	frequencyBodyAccelerometerJerk-std()-X	\
53	frequencyBodyAccelerometerJerk-std()-Y	\
54	frequencyBodyAccelerometerJerk-std()-Z	\
55	frequencyBodyGyroscope-mean()-X	\
56	frequencyBodyGyroscope-mean()-Y	\
57	frequencyBodyGyroscope-mean()-Z	\
58	frequencyBodyGyroscope-std()-X	\
59	frequencyBodyGyroscope-std()-Y	\
60	frequencyBodyGyroscope-std()-Z	\
61	frequencyBodyAccelerometerMagnitude-mean()	\
62	frequencyBodyAccelerometerMagnitude-std()	\
63	frequencyBodyAccelerometerJerkMagnitude-mean()	\
64	frequencyBodyAccelerometerJerkMagnitude-std()	\
65	frequencyBodyGyroscopeMagnitude-mean()	\
66	frequencyBodyGyroscopeMagnitude-std()	\
67	frequencyBodyGyroscopeJerkMagnitude-mean()	\
68	frequencyBodyGyroscopeJerkMagnitude-std()	\

## Descriptions of Final Data Set
The tidydata.txt contains 180 rows and 68 columns for

*mean(): Mean Value

*std(): Standard Devation 
