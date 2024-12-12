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
```python
# Register No: 24900032
# Developed By: V. RAKSHITA

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix) 


# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![1 NORM](https://github.com/user-attachments/assets/d837851e-8af5-490d-a6c7-663e2f9503c5)


### 2-Norm of a Matrix

![L2 NORM](https://github.com/user-attachments/assets/d4e459be-dbc8-425a-a8b1-cf8d4a6e52e7)

### Infinity Norm of a Matrix

![INFINITY NORM](https://github.com/user-attachments/assets/66149eb1-32f3-4cd2-a9a7-f43db9862ba5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
