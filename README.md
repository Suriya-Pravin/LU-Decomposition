### Date: 25-09-2024
# Ex-5: LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1) Define the package as scipy.linalg import lu.</br>
2) Get input from user and print L and U matrix by 'print'.</br>
3) Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.</br>
4) print the variable 'X'</br>
## Program:
### (i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Suriya Pravin M
RegisterNumber: 212223230223'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
### (ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Suriya Pravin M
RegisterNumber: 212223230223'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
### (i) To find the L and U matrix
![1)_page-0001](https://github.com/user-attachments/assets/f8a0ffab-f548-4a94-995f-452c4fd961b4)

### (ii) To find the LU Decomposition of a matrix
![2)_page-0001](https://github.com/user-attachments/assets/ecbb2044-a4ea-4f9b-ba5d-71850206ca47)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

