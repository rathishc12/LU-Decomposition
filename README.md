# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.	import the numpy as np
2.	import the lu from scipy.linalg
3.	give the array values
4.	print the output
5.	end the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Rathish kuamr C
RegisterNumber: 22009283
'''
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
/*

Program to find the L and U matrix.
Developed by: Rathish kumar C
RegisterNumber: 22009283
*/
```
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U))
(ii) To find the LU Decomposition of a matrix
```
Developed by: Rathish kumar C
RegisterNumber: 22009283
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
/*
Program to find the LU Decomposition of a matrix.
Developed by: Rathish kuamr C
RegisterNumber: 22009283
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

*/
```

## Output:

![lu](https://user-images.githubusercontent.com/120539398/215090757-28dc49e6-d931-46ab-8500-e5adfaf34e4d.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

