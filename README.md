# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the NumPy library.
### Step 2: Read the square matrix elements and store them in a NumPy array.
### Step 3: Find the inverse of the matrix using np.linalg.inv().
### Step 4: Display the inverse matrix and stop the program.

## Program:
```python
import numpy as np

A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])

A_inv = np.linalg.inv(A)

print(A_inv)
```
## Output:
<img width="1150" height="776" alt="image" src="https://github.com/user-attachments/assets/989b16c2-1641-4fbf-8d41-69ebed8c3027" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

