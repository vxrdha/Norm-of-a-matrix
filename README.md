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
# Register No:25011322

# Developed By:AMSAVARADHAN M

# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")



# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm3=np.linalg.norm(A,np.inf)
print(f"{norm3:.2f}")




```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1020" alt="Screenshot 2025-12-18 100824" src="https://github.com/user-attachments/assets/9d0ddf1e-e29d-4807-9449-4c3be9357690" />


### 2-Norm of a Matrix
<img width="1920" height="1020" alt="Screenshot 2025-12-18 100840" src="https://github.com/user-attachments/assets/ada22a5b-9ce3-44be-acdc-bdd6cad808f6" />


### Infinity Norm of a Matrix
<img width="1920" height="1020" alt="Screenshot 2025-12-18 100857" src="https://github.com/user-attachments/assets/3bedb40c-93d1-4373-a0ad-cf19781d5183" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
