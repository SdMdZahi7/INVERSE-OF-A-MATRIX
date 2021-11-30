# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np in the program
### Step 2: 
Give the elements of the matrix as np.array([[values]]) and assign a variable as A
### Step 3:
Use the syntax s=np.linalg.inv(A) to find the inverse of the matrix and assign a variable as S
### Step 4: 
Give print command as print(S)

## Program:
~~~
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]]) 
s=np.linalg.inv(A)
print(s)
~~~

## Output:
![GitHub Logo](inv.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

