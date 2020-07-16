# SUPPORT VECTOR MACHINE

Support vector machines (SVM) are supervised learning models with associated learning algorithms that analyze data used for regression and classification analysis.SVM algorithm is a popular machine learning tool that offers solutions for both classification and regression problems.

The scatter plot given below, has two sets groups. We need to draw a classification boundary to separate these groups. There are many ways to draw a boundary. We can take the nearby data point a measure the distance. We have to maximize the distance between the data points and the margin. We use SVM to do it. The nearby data points is called Support Vectors. Hence the name Support Vector Machine. In a 2D space the boundary is a line, where in case of 3D the boundary is a plane. Hyperplane is a plane in n-dimension that tries to separate out certain classification groups.

![svm](https://user-images.githubusercontent.com/67871795/87669378-7c6b2680-c78b-11ea-8f26-37120bcc339e.png)
 
## Gamma and Regularization(C):
C and Gamma are the hyper-parameters that decide the performance of an SVM model. There should be a fine balance between Variance and Bias for any ML model. For SVM, a High value of Gamma but low bias and vice-versa. The aim is to choose a model with optimum variance and bias leads to more accuracy but biased results and vice-versa. Similarly, a large value of C indicates poor accuracy. 

In addition to performing linear classification, SVM’s can efficiently perform a non-linear classification using what is called the kernel trick, implicitly mapping their inputs into high-dimensional feature spaces. SVM is a discriminative classifier that is formally designed by a separate hyper plane. It is a representation of examples as points of different categories are separated by a gap as wide as possible

## How does SVM work?
The main objective is to segregate the given data in the best possible way. The approach is to select maximum possible margin between support vectors in the given data set.
To select the maximum hyper plane in the given set the SVM follows the following:

•	It generates a hyper plane which segregates the classes in the best possible way and it selects the right hyper plane with maximum segregation from the nearest data points.

•	In some cases where the hyper plane’s is not very efficient, it uses kernel method to transform the input into a higher dimensional space.

•	SVM kernel is basically used to add more dimension to a lower dimensional space make it easier to segregate the data. It adds more dimension to the problem.

•	SVM is always implemented by a kernel. The kernel helps to make a more accurate classifier.

### Different types of Kernels: 
Linear Kernel: It can be used as a dot product between any two given observations

Polynomial Kernel: It is generalized form of linear kernels

Radial Basis Function Kernel: It is commonly used in SVM classification. It can map the space in infinite dimension

## SVM Use Cases: 
•	Face Detection

•	Text and Hypertext Categorization

•	Classification Of Images

•	Bioinformatics

•	Remote Homology Detection

•	Handwriting Detection 

•	Generalized Predictive Control

## How to Implement SVM? 
•	Loading the data to perform the classification of data

•	Exploring the data to see different variables, target variables

•	Split the data into train and test data

•	Generating the model by implementing the support vector machine

•	Evaluate the model

### Advantages: 
•	In high dimensional spaces

•	In cases where the number of dimensions is greater than the number of samples

•	It uses a subset of training points in the decision function that makes it memory efficient

•	Its versatile


### Disadvantages:
•	If the number of the features is much larger than number of samples, we have to avoid overfiting and choosing kernel functions

•	SVM's do not provide probability estimates


The entire code is available at [Github](https://sahasya.github.io/Support-Vector-Machine/).




