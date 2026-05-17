# Norm of a matrix
## Name:Nivetha N
## Reg.no:212225040290
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
# Register No:212225040290
# Developed By:Nivetha N
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```





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
```
<br> <img width="807" height="787" alt="Screenshot 2026-05-17 191841" src="https://github.com/user-attachments/assets/9bd97c49-b93c-4f6d-9e36-8aab83fc0201" />



### 2-Norm of a Matrix
<br><img width="783" height="831" alt="Screenshot 2026-05-17 191934" src="https://github.com/user-attachments/assets/4dad6ab3-8108-43cf-b4af-63d64895095f" />

### Infinity Norm of a Matrix
<br><img width="822" height="797" alt="Screenshot 2026-05-17 191948" src="https://github.com/user-attachments/assets/1b3e1b31-d5ec-4e45-8afb-b2bca97a6f78" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
