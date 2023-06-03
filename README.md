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
```
Developed By: Sivaramakrishnan B
Register Number: 212222110044
```

## 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## 2-Norm of a Matrix
```
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## 3-Infinity Norm of a Matrix
```
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:

### 1-Norm of a Matrix
![image](https://github.com/SivaramakrishnanBaskar/Norm-of-a-matrix/assets/119476322/3fb7bd81-47a2-41d8-b046-6bc8c520dc1f)

### 2-Norm of a Matrix
![image](https://github.com/SivaramakrishnanBaskar/Norm-of-a-matrix/assets/119476322/3a063c43-96b6-4f04-b3ee-6f6c1f35f5da)

### 3-Infinity Norm of a Matrix
![image](https://github.com/SivaramakrishnanBaskar/Norm-of-a-matrix/assets/119476322/1d3978d9-80d8-4405-a6c5-cd0aafea35b7)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
