# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix
### Step 4: 
End the program
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: A.Karthik 
#RegisterNumber: 25016949
import numpy as np
a = np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])  
inverse = np.linalg.inv(a)
print(inverse)
~~~
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b04f2d99-b135-4428-8d72-fd13321f9ef3" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

