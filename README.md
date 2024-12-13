# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/'''Program to find L and U matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
 Output:
![image](https://github.com/user-attachments/assets/99ed2879-1131-4701-ab7e-22855f68a41e)
![image](https://github.com/user-attachments/assets/35b73655-a9db-41b9-ab2b-59a81da03096)
![image](https://github.com/user-attachments/assets/a8fd9940-ff88-48d4-9034-08e1937bdad0)
![image](https://github.com/user-attachments/assets/891b92a2-232d-47f1-bdc5-96978f38534c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

