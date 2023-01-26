# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import the scipy from the library,for lu decomposition.

2. Get the eval input from the user.

3. Assign the value for a,b.

4. printf the program

## Program:
```
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: Jivan Karthec.B.S
RegisterNumber: 22004763
*/
```
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)

```
```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by:Dinesh Karthec.B.S
RegisterNumber: 22005847
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![m](https://user-images.githubusercontent.com/120552008/214861814-9d3ef214-bed1-4a41-ab65-90785c831734.png)
![m2](https://user-images.githubusercontent.com/120552008/214861867-d9a1bdef-46a4-4ad0-80cd-e9169aa0e48d.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

