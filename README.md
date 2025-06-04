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
# Register No:212224240189
# Developed By:Yasvanth RD
# 1-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.abs(m)
s=np.sum(a,axis=0)
ma=np.max(s)
print(ma)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
l2=np.linalg.norm(mat,2)
print(f"{l2:.2f}")





# Infinity Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
infinity=np.linalg.norm(mat,np.inf)
print(f"{infinity:.2f}")





```
## Output:
### 1-Norm of a Matrix
![450615057-0f1d7534-2e53-4bad-a356-742af7cf8ebf](https://github.com/user-attachments/assets/74737248-1426-4bf0-8b51-50f4fcf3c818)


### 2-Norm of a Matrix
![450615409-9c7dc7f6-07e1-4182-95ca-00078f3c49d6](https://github.com/user-attachments/assets/45c87538-b991-4312-afe0-f43aaa2f3ece)


### Infinity Norm of a Matrix
![450615668-59530cec-a15a-4c24-9bea-379ffa0a0252](https://github.com/user-attachments/assets/e2d7d739-c6c8-41a7-a582-3adb600ac96c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
