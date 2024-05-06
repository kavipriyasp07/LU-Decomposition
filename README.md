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
Developed by:kavipriya sp 
RegisterNumber: 2305002011
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:kavipriya sp
RegisterNumber:2305002011
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![lu decomposition]()
![Screenshot 2024-05-06 091710](https://github.com/kavipriyasp07/LU-Decomposition/assets/155508590/45461e70-8e22-42f7-8dc1-35c7a19bca31)
![Screenshot 2024-05-06 091728](https://github.com/kavipriyasp07/LU-Decomposition/assets/155508590/acfcb9c3-65f4-4ee7-b77e-387d3b09bdfa)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

