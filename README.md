# Predicting Heterogenous Human Activity using Smartphone Senor Data

Project by 

Sushrutha Dhummi Thrilochana ( MM73053 )

## Abstract
Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.


## Problem  Statement
In today's world, many people die as a result of disease outbreaks and bad lifestyles. People have become more conscious of their lifestyle choices and are attempting to improve their fitness. As a result, any digital companion that supports human fitness, such as recording calories burned, sleep cycle, and other records, is an added benefit. As an athlete, I believe it is critical to keep track of all of these factors in order to live a healthy lifestyle.

## Motivation
When I was 21, I got my first Fitbit watch, and I was constantly curious about the amazing function that had been released. Activity tracking was one of the features. When the same feature was released in Apple and later Android devices, I was perplexed. This kept me on my toes, and I learned that the data came from the sensors, but I had no idea what types of sensors there were or what the underlying mechanism was. I was taught all of the necessary topics to develop the same underlying technology that I fantasized about throughout my late childhood thanks to Prof. Christopher McGraw's course.

## Objectives
1. To use classification models to classify multinomial variables that is 6 degrees
2. Use of  dimension reduction techniques on models

## Data Description
The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) . Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also, the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). These signals were used to estimate variables of the feature vector for each pattern:'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:
gravityMean
tBodyAccMean
tBodyAccJerkMean
tBodyGyroMean
tBodyGyroJerkMean

## Methodology 
![Picture2](https://user-images.githubusercontent.com/45795026/146113336-cc7fa5ca-03ed-4e80-9d73-b2a70d269064.png)

## Exploratory Data Analysis
1. The Left gaussian peaks shows stationary Activities , where the Body accelerometer value is more; Vice Versa.
2. The Right Gaussian peaks shows Non-Statinary Activities, here the Body accelerometer value is less and Vice Versa.
3. High peaks of gaussian curve is of Stationary activities of Body gravity acceleration values
4. Low Peaks are of Non-Stationary Actvity of Body gravity acceleration values.

## Conclusion 

## Reference





