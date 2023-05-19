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
# Register No: 212222110010
# Developed By: DINESH KUMAR R
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)


# 2-Norm of a Matrix

#name: DINESH KUMAR R
#Reg no: 212222110010
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)



# Infinity Norm of a Matrix

#name: DINESH KUMAR R
#Reg no: 212222110010
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)


```
## Output:

### 1-Norm of a Matrix

<br>
<br>![maths 1](https://user-images.githubusercontent.com/119477784/235362196-7eca6d06-eabf-43c7-8202-daf73cb4c1a2.png)
<br>

### 2-Norm of a Matrix

<br>![maths 2](https://user-images.githubusercontent.com/119477784/235362210-c3dbd31f-15bb-469e-8047-6e804f3602f4.png)
<br>
<br>

### Infinity Norm of a Matrix

<br>
<br>![maths 3](https://user-images.githubusercontent.com/119477784/235362219-56c39a99-b215-4b38-9489-328c3a339a22.png)
<br>

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
