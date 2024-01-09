## Support Vector Machine
In machine learning, Support Vector Machines are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis. 
Owing to its robustness, it’s generally implemented for solving classification tasks. In this algorithm, the data points are first represented in an n-dimensional space. The algorithm then uses statistical approaches to find the best line that separates the various classes present in the data.
<img width="741" alt="Screenshot 2024-01-08 at 9 25 44 PM" src="https://github.com/ColleenJung/Social-Network-Ads_SVM/assets/119357849/810ff3c3-0d2e-496b-89df-fd54cf61453b">


## 1. Support Vectors
The objective of a support vector machine algorithm is to find a hyperplane in an n-dimensional space that distinctly classifies the data points. The data points on either side of the hyperplane that are closest to the hyperplane are called Support Vectors. T

## 2. Hyperplane
If the data points are plotted in a 2-dimensional graph, then the decision boundary is referred to as a straight line. However, if there are more than two dimensions, these are referred to as hyperplanes.
Hyperplanes are decision boundaries that is used to predict the continuous output. The data points on either side of the hyperplane that are closest to the hyperplane are called Support Vectors. 

## 3. Kernel
A kernel is a set of mathematical functions that takes data as input and transform it into the required form. 
<img width="722" alt="Screenshot 2024-01-08 at 9 24 17 PM" src="https://github.com/ColleenJung/Social-Network-Ads_SVM/assets/119357849/525c596f-417d-4b4a-9e5b-6aa6d78bf591">
The most widely used kernels include Linear, Non-Linear, Polynomial, Radial Basis Function (RBF) and Sigmoid. By default, RBF is used as the kernel. Each of these kernels are used depending on the dataset.

## 4. Boundary Lines
These are the two lines that are drawn around the hyperplane at a distance of ε (epsilon). It is used to create a margin between the data points.

## Advantages of Support Vector Regression
Although Support Vector Regression is used rarely it carries certain advantages that are as mentioned below:

1. It is robust to outliers.
2. Decision model can be easily updated.
<img width="456" alt="Screenshot 2024-01-08 at 9 27 32 PM" src="https://github.com/ColleenJung/Social-Network-Ads_SVM/assets/119357849/2135bd46-2e76-4b3d-a455-7b2f39506f64">
## Disadvantages of Support Vector Regression
Some of the drawbacks faced by Support Vector Machines while handling regression problems are as mentioned below:

1. They are not suitable for large datasets.
2. In cases where the number of features for each data point exceeds the number of training data samples, the SVM will underperform.
