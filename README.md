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
# Register No:212223240180
# Developed By:Vikaash P
# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by:Vikaash P
Reg no:212223240180
'''

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Vikaash P
RegisterNumber: 212223240180
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix and display the result in two decimal places.
Developed by: Vikaash P
RegisterNumber: 212223240180
'''
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Vikaash16/Norm-of-a-matrix/assets/139218414/3c085009-4df7-4872-8e24-c4afdee4b317)

### 2-Norm of a Matrix
![image](https://github.com/Vikaash16/Norm-of-a-matrix/assets/139218414/dcd65ea7-e1db-44b2-94bc-19e92d150072)

### Infinity Norm of a Matrix
![image](https://github.com/Vikaash16/Norm-of-a-matrix/assets/139218414/c271322f-d72b-4a3d-8a3e-24bf4c50bacd)












<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
