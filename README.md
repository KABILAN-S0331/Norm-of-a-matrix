# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Start
2. Input the matrix Convert the input into a NumPy array
3. Compute the 1-Norm Find the maximum column sum of the matrix
4. Compute the 2-Norm Find the largest singular value of the matrix
5. Compute the Infinity Norm Find the maximum row sum of the matrix
6. Print all three results (rounded to 2 decimal places)
7. Stop
## Program:
```Python
# Register No: 212225230119
# Developed By: Kabilan S
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
<img width="1829" height="890" alt="Screenshot 2026-03-24 212839" src="https://github.com/user-attachments/assets/f847afa9-4e39-4981-ba02-927847627115" />


### 2-Norm of a Matrix
<img width="1829" height="903" alt="Screenshot 2026-03-24 212852" src="https://github.com/user-attachments/assets/be2ba5a5-64d3-44bf-8d16-75fe45cb92f7" />


### Infinity Norm of a Matrix
<img width="1791" height="903" alt="Screenshot 2026-03-24 212904" src="https://github.com/user-attachments/assets/22e988bb-153b-44a3-b184-d945efadf551" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
