# Support Vector Machines #

## Notes from StatQuest [video](https://www.youtube.com/watch?v=efR1C6CvhmE) ##

### Definitions ###

- **Soft Margin**: Classifier boundary/threshold that allows for misclassification of observations/data points.
- **Cross Validation**: Allows for testing how many misclassifications result in better classification in the long run.
- **Support Vector Classifier (SVC)**: Observations on the edge and within the Soft Margin are called **Support Vectors**
  - When the data are _1-Dimensional_ the SVC is a single point on a 1-Dimensional number line.
  - When the data are _2-Dimensional_ the SVC is a line and the _Soft Margin_ is measured between those data points closest to it.
  - When the data are _3-Dimensional_ the SVC is a plane, instead of a line and classifications of new observations are determined by which side of the plane they're on.
 