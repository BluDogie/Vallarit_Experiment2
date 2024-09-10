# Vallarit, Marick Andrei T. 2ECE-C
# ECE2112 Experiment 2 - Numerical Python
I. Intended Learning Outcomes:
1. To identify the codes and functions incorporated in the Numpy library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Numpy library

II. Instructions:
Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter
notebook in the dedicated submission bin.

# NORMALIZATION PROBLEM: 
Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation. Mathematically, normalization can be
expressed as:

![image](https://github.com/user-attachments/assets/8b0a9d0f-ddc0-4cd0-b336-2f984734da63)


In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls.

In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized
ndarray as X_normalized.npy

# DIVISIBLE BY 3 PROBLEM: 
Create the following 10 x 10 ndarray.

![image](https://github.com/user-attachments/assets/dca38630-3ded-467e-b33f-8189f1d27ff2)

which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

# Personal Challenges from this Experiment
For the first problem, I was skeptical about the input since it generates random integers for a 5x5 array. To normalize the elements of the array, as the instructions say to use the z-table formula in order to normalize the array, "Centering means subtracting the data from the mean and scaling means dividing with its standard deviation". Using the .std() and .mean() functions to automate the means and standard. Using the numpy library, we can save the file as .npy since the problem needs the output of the array to be saved as .npy. In the end of problem, I printed the output of the normalized array so I can verify if the output is up to par with the intended output of the Normalization Problem. *Note: Before I printed the normalized array, I printed the array beforehand and used manual calculations on one of the elements to verify if the output is correct or not.*

For the second problem, I faced no personal challenges since the essence of problem #1 is the same as #2, but I used a modulo function in order to determine the elements or integers that are divisible by 3. I printed the array in order to verify if my output is correct or not, which it is.
