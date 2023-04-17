# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy package as np
2. From scipy package import lu
3. Get input from the user
4. Print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: M.PRAKASH
RegisterNumber: 212222100035
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
arr=np.array(A)
p,l,u=lu(arr)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: M.PRAKASH
RegisterNumber: 212222100035
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:
<img width="721" alt="image" src="https://user-images.githubusercontent.com/118350045/232545225-a359a7ff-fc45-4d8f-8d4e-0ad6afb3af64.png">
<img width="642" alt="image" src="https://user-images.githubusercontent.com/118350045/232545442-68865112-e0ab-4b7a-9bf0-8a556508cae7.png">


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

