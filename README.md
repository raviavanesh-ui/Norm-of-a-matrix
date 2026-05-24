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
# Register No: 212225240018
# Developed By: Avanesh.R
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Avanesh.R 
RegisterNumber: 212225240018
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Avanesh.R
RegisterNumber: 212225240018
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/8b5782a9-d603-4510-8301-ee7dc6cc7194" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/802a1092-1b03-4093-81da-c6b9bef5569b" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a4ef530d-b277-4c0e-b670-7c9d659add73" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
