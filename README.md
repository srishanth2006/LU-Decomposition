# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import libraries
2. Get the matrix from the user
3. Find the L and U 
4. Print the solution.
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:SRISHANTH J 
RegisterNumber: 21223240160
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U =lu(a)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu, piv),b)
print(x)

## Output:
<img width="629" alt="Screenshot 2023-12-24 194431" src="https://github.com/srishanth2006/LU-Decomposition/assets/150319470/cecc334f-c34b-467c-9aa8-9519a35853ec">

<img width="654" alt="Screenshot 2023-12-24 194448" src="https://github.com/srishanth2006/LU-Decomposition/assets/150319470/e99ba487-3292-4dce-a361-f757adac8182">


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

