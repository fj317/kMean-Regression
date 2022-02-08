# kMean & Regression
## Image Segmentation with kMeans
This program is located in the segmentationKMeans.ipynb file. It takes in an image and computes [posterisation](https://en.wikipedia.org/wiki/Posterization) on the image to transform the image.
To compute the posterisation, I designed my own kMean function (rather than using sklearn's).

## Linear Regression
This program is located in the regressionRANSAC.ipynb file. This task involved performing linear regression on a collection of randomly created data in order to predict where new values would be located.  Linear regression involves using minimising the objective function to produce a closed form solution.

## Linear Regression using RANSAC
This program is also located in the regressionRANSAC.ipynb file. This tasks invovled improving the linear regression task by implementing RANSAC to prevent outliers from affecting the prediction. RANSAC works as follows:
- pick 2 data points
- compute the parameters, m and c for these data points
- classify all remaining data points as either outliers or inliers
- repeat from beginning, N times
- select the parameter pair with the fewest outliers and thus the smallest error.


## Setup
Load the desired file in Jupyter Notebook and restart to run each program.
