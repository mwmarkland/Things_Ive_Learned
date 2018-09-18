# Support Vector Machines

## Overview

A favorite tool for classification and regression problems. Also used for outlier analysis and ranking.

About 50 years old.

SVMs try to find a separator (line or hyperplane) which are less risky by trying to stay evenly spaced between the clusters of data. To do this they

1. Find lines that correctly classify the training data.
2. Pick the line which has the greatest distance to the points closest to it.

The points closest to the line are called *support vectors*. The region they define around the line is the *margin*.

Data that can be separated by a line or hyperplane is known as *linearly separable* data.

SVMs are good at finding hyperplanes. But what if the data is not liearly separable? Then you can project the data into a space where it is linearly separable and find a hyperplane there.

So, you could take 2D data and project it into 3D using a different set of coordinates. Then find a hyperplane that fits. When you go back to the 2D plot the hyperplan will not be represented by a straight line, but will do what the SVM should do.

What is cool is that the SVM does the projection for you. SVMs use *kernels* to do said projections.

## Kernels
"The secret sauce that makes SVMs tick."

In all the math, the exact projection or number of dimensions does not show up. It's all processed as *dot products* between various data points represented as vectors. I won't reproduce math here.

A *kernel* or *kernel function* takes two points in the original space and directly gives us the dot product in the projected space.

Three popular kernel functions: *polynomial*, *Radial Basis Function (RBF)*, and *Sigmoid*. There is also a *linear* kernel usually.

Each of these kernels will have some set of parameters which tune their behavior.

## Parameters

### C

**C** has to do with how you deal with the errors (i.e. the data that just doesn't fit). **C** dictates the trade-off between:
1. Having a wide margin.
2. Correctly classifying **training** data.

A higher value of C implies you want lesser errors on the training data.

Values of **C** are often chosen using *cross-validation*.

## Resources

[KDnuggets Support Vector Machine Tutorial ](https://www.kdnuggets.com/2017/08/support-vector-machines-learning-svms-examples.html)
