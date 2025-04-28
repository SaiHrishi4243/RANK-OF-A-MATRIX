# RANK-OF-A-MATRIX

## Aim:

To write a python program to find the rank of a matrix

## Equipment’s required:

1. 	Hardware – PCs

2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1: 

Import the numpy module to use the built-in functions for calculation

### Step 2: 

Prepare the lists from each linear equations and assign in np.array()

### Step 3:

Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: 

End the program

## Program:

```python

#Program to find the rank of a matrix.
#Developed by: Sai Hrishi M
#RegisterNumber: 212224240140

import numpy as ma
a=ma.array([[3,2,5],[1,1,2],[3,3,6]])
solution=ma.linalg.matrix_rank(a)
print(solution)

```

## Output:

![Screenshot 2025-04-28 235024](https://github.com/user-attachments/assets/681d3f37-61be-4085-ad76-497d5c8b3ca2)

## Result:

Thus the rank for the given matrix is successfully solved by  using a python program.

