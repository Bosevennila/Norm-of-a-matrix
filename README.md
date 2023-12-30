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
```
Python
# Register No: 23013526
# Developed By: CHANDRAPRIYADHARSHINI C

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![7a maths](https://github.com/Bosevennila/Norm-of-a-matrix/assets/144870486/294047d6-4a05-4b22-90a9-9a85b3a411a5)


### 2-Norm of a Matrix
![7b maths](https://github.com/Bosevennila/Norm-of-a-matrix/assets/144870486/32870e27-479b-4f24-99b5-6244edfc1836)


### Infinity Norm of a Matrix
![7c maths](https://github.com/Bosevennila/Norm-of-a-matrix/assets/144870486/db8d3154-79c5-4162-87a2-856687befcf6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
