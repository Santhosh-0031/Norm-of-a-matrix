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
# Register No:23013562
# Developed By:SANTHOSH KUMAR R
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 23013562
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

# 2-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 23003250
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 23013562
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix
![](<Screenshot 2023-12-24 192253.png>)


### 2-Norm of a Matrix
![Alt text](<Screenshot 2023-12-24 192311.png>)


### Infinity Norm of a Matrix
![Alt text](<Screenshot 2023-12-24 192341.png>)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
