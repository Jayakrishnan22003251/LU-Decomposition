# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program.


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JAYAKRISHNAN L B L
RegisterNumber: 22003251
*/
```
   import numpy as np
   from scipy.linalg import lu 
   a=np.array(eval(input()))
   P,L,U=lu(a)
   print(L)
   print(U)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JAYAKRISHNAN L B L
RegisterNumber: 22003251
*/
```
  import numpy as np
  from scipy.linalg import lu_factor,lu_solve
  a=np.array(eval(input()))
  b=np.array(eval(input()))
  lu,piv=lu_factor(a)
  x=lu_solve((lu,piv),b)
  print(x)



## Output:
![lu decomposition]()
![image (5)](https://user-images.githubusercontent.com/120232371/212461889-11c3b1cf-cc97-4ff8-b681-32c30c29ed0e.png)
![image (6)](https://user-images.githubusercontent.com/120232371/212461901-6f63989c-9ca5-46c4-b6b5-ea60fb6bf8d8.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

