# EXPERIMENT: 5
# LU Decomposition 
## NAME: AVINASH T
## DEPARTMENT: ARTIFICIAL INTELLIGENCE AND DATA SCIENECE
## REG NO: 212223230026
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: AVINASH T 
#RegisterNumber: 212223230026
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,l,U=lu(A)
print(l)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: AVINASH T
#RegisterNumber: 212223230026
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print (x)
```
## Input:
(i) To find the L and U matrix
![image](https://github.com/AVINASH05T/LU-Decomposition/assets/151514286/5623f1eb-0341-479b-b216-e3e831164e5b)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/AVINASH05T/LU-Decomposition/assets/151514286/c2888ae0-6b25-4d98-aabd-110cd7956cbe)

## Output:
(i) To find the L and U matrix
![image](https://github.com/AVINASH05T/LU-Decomposition/assets/151514286/40c64447-ddec-4f74-8988-eb1223cb4662)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/AVINASH05T/LU-Decomposition/assets/151514286/c6acc67c-6378-4bee-8569-4e015629c06b)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

