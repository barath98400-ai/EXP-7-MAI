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
# Register No: 212225220016
# Developed By: Barath M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/5f76e943-9c22-4c1a-b727-73fb5cff3ef9" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/09392b61-3ed8-45a4-84ad-81be647737f2" />



### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/f8131864-c9c4-4364-acbd-dc4c1096c93c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
