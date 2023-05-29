# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2.from scipy.linalg import lu,lu_factor,lu_piv
3.Get input from the user as eval(input())
4.Use lu_factor and lu_solve to find LU decomposition
5.print L,U
6.print x

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Gowrisankar.p
RegisterNumber: 212222230041
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Gowrisankar.p
RegisterNumber: 212222230041 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot (16)](https://github.com/gowrisankarponnusamy/LU-Decomposition/assets/119393123/333f7922-9b8b-48b8-8dab-29ed099c012f)
![Screenshot (17)](https://github.com/gowrisankarponnusamy/LU-Decomposition/assets/119393123/ae4c2b72-138d-47f3-9cc5-df51bc7f5723)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

