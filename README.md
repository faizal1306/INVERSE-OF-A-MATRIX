# Ex:3-INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the NumPy module using import numpy as np so that we can use its built-in matrix functions.
### Step 2:
Create the matrix by placing the elements of each row inside a list and convert it into a NumPy array using np.array().
### Step 3: 
Use the function np.linalg.inv() to compute the inverse of the given matrix.
### Step 4: 
Display the inverse matrix and end the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Mohamed faizal M
#RegisterNumber:24000006
import numpy as np
a = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
c = np.linalg.inv(a)
print(c)
```
## Output:
![Screenshot 2024-10-08 094501](https://github.com/user-attachments/assets/35718900-5f22-40a1-aed1-cd3f3a9ca934)

## Result:
Thus the inverse of given matrix is successfully solved using python program

