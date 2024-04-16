# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Using library scipy.linalg,import lu to find l and u matrices and lu_factor,lu_solve to find result
3. Prepare the lists from given matrix
4. Using lu(),l and u matrices can be printed and using lu_factor() and lu_solve() to find resultant matrix

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![Screenshot 2024-04-16 202141](https://github.com/rdxkeerthi/LU-Decomposition/assets/147473120/71aaecc8-b3f4-4c8a-bec6-60c741807b95)

![Screenshot 2024-04-16 202224](https://github.com/rdxkeerthi/LU-Decomposition/assets/147473120/ea5dc6df-582a-4b3d-ab32-f552d6a25156)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

