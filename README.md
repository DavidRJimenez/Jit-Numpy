# Jit-Numpy
Taller de Numpy y JIT
Introduction
This Jupyter Notebook demonstrates various techniques for matrix operations, image processing, and performance optimization using Numba's Just-In-Time (JIT) compilation. It includes examples of matrix multiplication, image normalization, histogram calculation, and convolution operations with and without JIT optimization.

Prerequisites
Ensure you have the following libraries installed:

numpy
numba
scikit-image
matplotlib
You can install these libraries using pip:

sh
Copiar código
pip install numpy numba scikit-image matplotlib
Content Overview
Matrix Operations

Matrix Multiplication: Implements and compares custom matrix multiplication with NumPy's dot product.
Timing Matrix Multiplications: Uses %timeit to compare the performance of custom and NumPy matrix multiplication functions.
Image Processing

Plotting Points: Creates and plots points on a 2D plane.
Reflection Transformation: Defines a function to reflect points across the origin and plots the result.
Image Normalization: Reads an image and normalizes its pixel values.
Histogram Calculation: Provides a skeleton for a histogram function.
Convolution Operations

Custom Convolution: Defines a custom convolution function.
JIT-Optimized Convolution: Uses Numba's jit decorator to optimize the convolution function.
Timing Convolution Functions: Uses %timeit to compare the performance of the custom and JIT-optimized convolution functions.
