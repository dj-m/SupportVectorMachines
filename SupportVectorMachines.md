# Support Vector Machines #

## Notes from StatQuest [video](https://www.youtube.com/watch?v=efR1C6CvhmE) ##

### Definitions ###

- **Soft Margin**: Classifier boundary/threshold that allows for misclassification of observations/data points.
- **Cross Validation**: Allows for testing how many misclassifications result in better classification in the long run.
- **Support Vector Classifier (SVC)**: Observations on the edge and within the Soft Margin are called **Support Vectors**
  - When the data are _1-Dimensional_ the SVC is a single point on a 1-Dimensional number line.
  - When the data are _2-Dimensional_ the SVC is a line and the _Soft Margin_ is measured between those data points closest to it.
    - The SVC is a _1-Dimensional_ line in a _2-Dimensional_ space.
  - When the data are _3-Dimensional_ the SVC is a plane, instead of a line and classifications of new observations are determined by which side of the plane they're on.
    - The SVC is a _2-Dimensional_ plane in a _3-Dimensional_ space.
  - When the data are in 4 or more Dimensions, the SVC is a _hyperplane_.
- **Support Vector Machines**: 

The main ideas behind Support Vector Machines:
| ![x](images/svm_1.png) |
| :-: |
| ![x](images/svm_2.png) |
| :-: |
| ![x](images/svm_3.png) |