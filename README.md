# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1. import numpy as np

Step 2: from scipy package import lu

Step 3: get input from the user

Step 4: print result  

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: HARI PRASATH P
RegisterNumber: 212224230084

import numpy as np
from scipy .linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: HARI PRASATH P
RegisterNumber: 212224230084
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy .linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
<img width="1703" height="985" alt="Screenshot 2025-08-28 094402" src="https://github.com/user-attachments/assets/97ef5992-1d27-4f01-a42e-890c0026cdf4" />
<img width="1692" height="904" alt="Screenshot 2025-08-28 094419" src="https://github.com/user-attachments/assets/3afe2dfd-ef18-4893-a022-4e3e6ab90ad7" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

