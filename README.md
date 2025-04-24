# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. You need NumPy for arrays and SciPy for LU decomposition tools.
2. You enter the coefficient matrix A and the right-hand side vector b.
3. Perform LU Decomposition and Solve
4. Prints the solution vector x

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Pragatheeshraaj D
RegisterNumber: 212224230199
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Pragatheeshraaj D
RegisterNumber: 212224230199
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu, piv),b)
print(X) 
*/
```

## Output:
![Screenshot 2025-04-24 190200](https://github.com/user-attachments/assets/cc0dcc8d-672b-4953-9d93-a863e8f45ef0)
![Screenshot 2025-04-24 190212](https://github.com/user-attachments/assets/b1a82829-eb68-4fb3-9d75-3d0a730b2bd7)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

