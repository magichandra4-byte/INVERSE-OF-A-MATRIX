# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : **Import NumPy** using `import numpy as np`.
### Step 2: **Create the matrix** using `np.array()` with the given matrix elements.
### Step 3: **Find the inverse** of the matrix using `np.linalg.inv(matrix)`.
### Step 4: **Store the inverse matrix** in the variable `result`.
### Step 5: **Display the inverse matrix** using `print(result)`.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: VEDHA M
#RegisterNumber:212225230292

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result = np.linalg.inv(matrix)
print(result)


```



## Output:
![alt text](<Screenshot (68).png>)
![alt text](<Screenshot (69).png>)

[text](EXP3.REV.pdf)

## Result:
Thus the inverse of given matrix is successfully solved using python program

