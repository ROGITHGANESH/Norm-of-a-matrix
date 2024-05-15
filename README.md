# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
        2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

1-Norm of a Matrix
```
#REGISTER NUMBER: 212223100046
#DEVELOPED BY: ROGITH GANESH.R

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
 2-Norm of a Matrix
 ```

#Program to find 2-norm of a matrix.
#Developed by: ROGITH GANESH.R
#RegisterNumber: 212223100046

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
3. Infinity Norm of a Matrix
```
#Program to find 2-norm of a matrix.
#Developed by: ROGITH GANESH.R
#RegisterNumber: 212223100046

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Output:
# one norm of a matrix:
![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/f99e12d0-b28c-4cd4-8ddf-69d078b2869f)
# two norm of a matrix
![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/538a39b4-f9ea-4d90-a70d-59992a00402c)
# Infinity norm of a matrix
![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/54fbeee0-e0ea-4531-b9d2-aadb9ae09f77)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
