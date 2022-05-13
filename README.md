# Project: Abnormal-Vertebral
  
  Goal: build KNN from scratch

## Data set info.
Data set: [Vertebral Column Data Set](https://archive.ics.uci.edu/ml/datasets/vertebral+column#)<br />
Consists of 6 biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (in this order):
* pelvic incidence
* pelvic tilt
* lumbar lordosis angle
* sacral slope
* pelvic radius
* grade of spondylolisthesis<br />

## Packages
There are 5 packages that I use in this project
* panda
* seaborn
* numpy
* scipy
* sklearn

## Explore and Preprocessing
*  Explore the independent variable in the data set by ploting scatter plot
*  Detect the outliers by ploting the boxplot
*  Drop out outliers by using interquartile range 
*  Split train and test set

## Build KNN from scratch
* There are several ways to calculate the distance between observations, but here euclidean distance is used
* I use Majority voting to decide the target

## Validation 
* I verify my own knn by implement the knn in sklearn to check whether the accuracy of the model are the same or not

## Further work
* Find the suitable k
* Implement other distance
* Implement weighted decision


