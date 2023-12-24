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
1.
```
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}" .format(sol)
print(norm)
```
2.
```
'''
Program to find 2-norm of a matrix.
Developed by: VIJAY R
RegisterNumber: 23013759
'''
import numpy as np
a=([[1,2],[3,4],[1,7]])
b=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)
```
3.
```
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 203315](https://github.com/vijayr21/Norm-of-a-matrix/assets/149347607/fa7afb7a-27ba-43f2-b1b5-99a64b116144)


### 2-Norm of a Matrix
![Screenshot 2023-12-24 203330](https://github.com/vijayr21/Norm-of-a-matrix/assets/149347607/c446f1cd-ead0-40c7-aac1-379ddd8f40f7)

### Infinity Norm of a Matrix
![Screenshot 2023-12-24 203343](https://github.com/vijayr21/Norm-of-a-matrix/assets/149347607/ad9cf2ef-89b9-4fff-9a43-5987bac274c1)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
