# DATE:
# EX-05: LU Decomposition 

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
Developed by: HARSSHITHA LAKSHAMANAN
RegisterNumber: 212223230075
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by: HARSSHITHA LAKSHMANAN
RegisterNumber: 212223230075
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

![image](https://github.com/user-attachments/assets/fc233586-d7db-43d8-8385-b63f8f2165aa)
![image](https://github.com/user-attachments/assets/b58b7d3f-1b15-4019-bbea-d2e5cf47b632)
![image](https://github.com/user-attachments/assets/f246b383-d856-4226-bc0a-bd1acd76b9fa)
![image](https://github.com/user-attachments/assets/d5403a2e-268e-4194-8685-08efe6d6bb37)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

