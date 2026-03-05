# AIM: STUDY OF NUMPY LIBRARY


# THEORY:
NumPy is mainly used for working with arrays and matrices. It helps in performing mathematical and statistical operations easily and efficiently.
NumPy (Numerical Python) is a powerful library used for numerical computations. 
It allows us to create arrays, check their dimensions, find their shape, and perform operations on them.
It is faster and more convenient than normal Python lists when working with large data.

# Declaration of NumPy Arrays:
In this experiment, NumPy is imported using import numpy as np. Two arrays are created: one one-dimensional array and one two-dimensional array. 
These arrays store numerical values and are printed to observe their structure. A 1D array is similar to a list and contains elements in a single row.
A 2D array is similar to a matrix and contains rows and columns. NumPy arrays are faster and more efficient than normal Python lists for numerical computations.
Arrays can be created using np.array() by passing a list or nested list as input. NumPy ensures that all elements in an array are of the same data type, which improves performance.

# Dimension of an Array:
The ndim function is used to find the dimension of an array. A one-dimensional array has one axis, while a two-dimensional array has two axes (rows and columns). 
This helps us understand the structure of the data. The dimension of an array is also called the rank of the array.
NumPy can also create 3D or multi-dimensional arrays. Higher-dimensional arrays are useful in machine learning, image processing, and scientific computing.
Knowing the dimension helps in performing matrix operations and reshaping arrays.

# Shape of an Array:
The shape function gives the number of rows and columns in an array. For a 1D array, it shows the number of elements.
For a 2D array, it shows rows and columns in the form (rows, columns). The shape helps in understanding how the data is organized inside the array.
It is useful when performing operations like reshaping or combining arrays. The shape of an array can also be changed using the reshape() function.
Correct shape is important for matrix multiplication and broadcasting operations.

# Data Type of an Array:
The dtype function is used to check the data type of the elements inside the array. If all elements are integers, the type will be integer.
If any value is decimal, NumPy automatically converts the type to float. Common NumPy data types include int32, int64, float32, and float64.
Data type affects memory usage and computation speed. The data type can also be specified manually while creating the array.
Converting data types can be done using the astype() function.

# Built-in Array Creation Functions:
NumPy provides built-in functions like zeros() to create a matrix of zeros, ones() to create a matrix of ones, and eye() to create an identity matrix.
These functions make matrix creation simple and quick. np.zeros() is useful for initializing arrays before filling them with data.
np.ones() is often used in mathematical operations and testing algorithms.
np.eye() creates a square identity matrix where diagonal elements are 1 and others are 0.
Another useful function is np.full() which creates an array filled with a specific value. These functions save time compared to manually creating arrays.

# Range and Spacing Functions:
The arange() function generates numbers within a given range with a specific step value. The linspace() function generates equally spaced numbers between two values.
These functions are useful for creating sequences of numbers. arange() works similar to Python's range() function but returns a NumPy array.
linspace() requires specifying the number of values to generate. linspace() is commonly used in graph plotting and mathematical calculations.
Another related function is logspace() which generates numbers on a logarithmic scale. These functions help in creating numerical sequences efficiently.

# Arithmetic Operations on Arrays:
NumPy allows direct mathematical operations on arrays. For example, adding a number to an array adds that number to every element.
Similarly, multiplying an array multiplies each element individually. This makes calculations easy and efficient.
Operations like addition, subtraction, multiplication, and division can be performed directly.
NumPy performs element-wise operations automatically. This concept is called vectorization, which makes calculations faster.
Arrays can also be added or multiplied with other arrays of the same shape. Broadcasting allows operations between arrays of different shapes in some cases.

# Statistical Functions:
NumPy provides statistical functions such as mean(), median(), max(), min(), sum(), and std(). These functions help in analyzing data quickly without writing complex code.
mean() calculates the average value of the array elements.
median() finds the middle value after sorting the data.
std() calculates the standard deviation, which measures data variation.
max() and min() help identify the largest and smallest values in the dataset.
These functions are widely used in data analysis, machine learning, and statistics.


# CONCLUSION:
This experiment helped in understanding how to create and manipulate arrays using the NumPy library. It showed how to check dimensions, shapes, and data types, and how to perform mathematical and statistical operations.
Overall, NumPy makes numerical computations simple, fast, and efficient in Python programming.




