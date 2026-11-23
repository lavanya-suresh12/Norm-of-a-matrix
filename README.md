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
```Python
# Register No:26012000
# Developed By:Lavanya S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norml=np.linalg.norm(A,1)
norm="{:.2f}".format(norml)
print(norm)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norml=np.linalg.norm(A,2)
norm="{:.2f}".format(norml)
print(norm)




# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norml=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(norml)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="996" height="800" alt="Screenshot 2026-11-23 104517" src="https://github.com/user-attachments/assets/4e829887-c2a5-4bba-a4f3-7acc303b069c" />

### 2-Norm of a Matrix
<img width="977" height="848" alt="Screenshot 2026-11-23 104532" src="https://github.com/user-attachments/assets/1d40af73-8701-430a-baec-a98adaec011d" />

### Infinity Norm of a Matrix
<img width="957" height="775" alt="Screenshot 2026-11-23 104543" src="https://github.com/user-attachments/assets/2fd74a2b-97fb-437e-beeb-5b2f50ed0432" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
