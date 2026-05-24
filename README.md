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
# Register No:212225220001
# Developed By:Aarthi A
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="783" height="763" alt="Screenshot 2026-05-24 151407" src="https://github.com/user-attachments/assets/1acc577f-3c7d-4169-8c2d-eaf08bffcec8" />


### 2-Norm of a Matrix
<img width="800" height="760" alt="Screenshot 2026-05-24 151426" src="https://github.com/user-attachments/assets/06c243fb-8fec-4404-9b28-88fc0bbedef7" />


### Infinity Norm of a Matrix
<img width="1038" height="744" alt="Screenshot 2026-05-24 151442" src="https://github.com/user-attachments/assets/7bd4ad72-0a3d-493a-b902-c74494b05bdc" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
