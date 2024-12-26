# LU Decomposition 

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
/*
Program to find the L and U matrix.
Developed by:Swetha C 
RegisterNumber: 24901183*/
```
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Swetha C
RegisterNumber: 24901183
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![Screenshot 2024-12-26 054033](https://github.com/user-attachments/assets/6c1f235a-c446-4723-8be0-a4755e2c5dcd)
![Screenshot 2024-12-26 054100](https://github.com/user-attachments/assets/0d302a11-8833-4d81-ba79-e0735fef79db)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

