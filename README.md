## DATE:
# EX.NO:5 LU Decomposition 
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
'''Program to find L and U matrix using LU decomposition.
Developed by: POZHILAN V D
RegisterNumber: 212223240118
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: POZHILAN V D
RegisterNumber: 212223240118
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output 1:
![image](https://github.com/user-attachments/assets/4fdd220d-d095-48d9-b381-87509c36980c)

## Output 2:
![image](https://github.com/user-attachments/assets/c453217a-ae7d-491f-a871-a213d5d19aee)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

