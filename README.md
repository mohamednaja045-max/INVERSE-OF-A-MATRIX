# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the required library (⁠numpy⁠ and ⁠os⁠)
### Step 2: Define the input matrix a using the ⁠numpy.array()⁠ function with the specified elements ⁠[[6,2,3],[3,1,1],[10,3,4]]
### Step 3: Compute the inverse of the matrix a using the built-in linear algebra function ⁠numpy.linalg.inv(a)⁠ and store the result in variable b
### Step 4: Print the resulting inverse matrix b and terminate the program

## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]= "1" 

import numpy

a=numpy.array([[6,2,3],[3,1,1],[10,3,4]])

b=numpy.linalg.inv(a)

print(b)

## Output:<img width="668" height="804" alt="{E60A1890-89E2-4696-841E-01703FA18B2D}" src="https://github.com/user-attachments/assets/d0818503-aba6-406b-912a-b226c2960c29" />
## Result:
Thus the inverse of given matrix is successfully solved using python program

