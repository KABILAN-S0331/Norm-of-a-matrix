# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Start
2.Input the matrix Convert the input into a NumPy array
3.Compute the 1-Norm Find the maximum column sum of the matrix
4.Compute the 2-Norm Find the largest singular value of the matrix
5.Compute the Infinity Norm
6.Find the maximum row sum of the matrix
7.Print all three results (rounded to 2 decimal places)
8.Display the output as result
## Program:
```Python
# Register No:212225230119
# Developed By:
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
<img width="1829" height="890" alt="Screenshot 2026-03-24 212839" src="https://github.com/user-attachments/assets/ad41f2d2-99ca-4c3b-a689-519f20fed1a2" />


### 2-Norm of a Matrix
<img width="1829" height="903" alt="Screenshot 2026-03-24 212852" src="https://github.com/user-attachments/assets/fd5ae44c-aa91-46ca-8be6-434cded7f925" />


### Infinity Norm of a Matrix
<img width="1791" height="903" alt="Screenshot 2026-03-24 212904" src="https://github.com/user-attachments/assets/2f29445e-b28b-4a8b-8334-f07402c5472f" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
