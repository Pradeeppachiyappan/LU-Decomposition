# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### step 1:
import the numpy module to use the bulit in functions for calculation
### step 2:
prepare the list from each linear equation and assign in np.array()
### step 3:
Using the np.linalg.solve(),we can find the solution
### step4 :
End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: pradeep raj 
RegisterNumber: 212222240073
*/import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: pradeep raj
RegisterNumber:212222240073 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

![Screenshot (63)](https://user-images.githubusercontent.com/118707347/235442414-bba6d0ec-f048-4f3a-b85b-c7324a1c8ff6.png)


![Screenshot (64)](https://user-images.githubusercontent.com/118707347/235442454-7db9d921-2c8d-41ba-86c0-e40f4c37d8fc.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

