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
#REGISTER NUMBER: 212223100020
#DEVELOPED BY: KAVINAJAI.T

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
 2-Norm of a Matrix
 ```

#Program to find 2-norm of a matrix.
#Developed by: Kavinajai.T
#RegisterNumber: 212223100020

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
3. Infinity Norm of a Matrix
   ``
#Program to find 2-norm of a matrix.
#Developed by: Kavinajai.T
#RegisterNumber: 212223100020

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
``
# Output:
1.![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/802aed46-4cd3-426a-b32e-e674d342899b)
2.![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/ee6d8b99-680b-40c3-94dc-ac26fb882fb7)
3.![image](https://github.com/Kavin1311/Norm-of-a-matrix/assets/145695724/fcd3cc07-450f-4478-8398-b6bad3566e48)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
