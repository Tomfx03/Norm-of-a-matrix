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

# 1-Norm of a Matrix
```
'''
program to find 1-norm of a matrix.
Developed by: Tom Francies Xaviour L
RegisterNumber: 21222311060
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Tom Francies Xaviour L
RegisterNumber: 21222311060
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```


# Infinity Norm of a Matrix
```
'''
Program to find Infinity-norm of a matrix.
Developed by: Tom Francies Xaviour L
RegisterNumber: 21222311060
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```


## output:

### 1-Norm of a Matrix
![Screenshot 2024-05-01 134709](https://github.com/Tomfx03/Norm-of-a-matrix/assets/101335832/80c02c14-2e68-449d-90e9-b7c20be22965)


### 2-Norm of a Matrix
![Screenshot 2024-05-01 134725](https://github.com/Tomfx03/Norm-of-a-matrix/assets/101335832/232f544b-902c-44dd-bf2f-4e3dcb027e21)

### Infinity Norm of a Matrix
![Screenshot 2024-05-01 134836](https://github.com/Tomfx03/Norm-of-a-matrix/assets/101335832/e5caec6e-66d3-4872-af90-a360b501d560)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified

