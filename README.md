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
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/155506447/0268149c-9d74-4c70-8cac-5602dd00647f)


### 2-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/155506447/76856fb2-c661-471a-a2ca-2def1d969004)


### Infinity Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/155506447/f3c9ac04-2727-4b02-9e33-1c1b01fbf84c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
