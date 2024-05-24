# Norm of a matrix
# Date : 
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. import the NumPy library using the statement import numpy as np.
        2. Define the given matrix A
        3. Compute the Norm of a matrix using np.linalg.inv()
        4. print and end the program
## Program:
```
'''
program to find 1-norm of a matrix.
Developed by: A.Divya
Register Number: 2305002007
'''
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/divyaanbu-143/Norm-of-a-matrix/assets/155506447/5695c711-26ca-4ae9-881f-2ca847f033d7)


### 2-Norm of a Matrix
![Screenshot 2024-05-24 135847](https://github.com/divyaanbu-143/Norm-of-a-matrix/assets/155506447/a263efd7-ca77-47da-87ee-0382608186e7)


### Infinity Norm of a Matrix
![Screenshot 2024-05-24 135813](https://github.com/divyaanbu-143/Norm-of-a-matrix/assets/155506447/97324f39-8511-4151-8083-7fc5966547a4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
