# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
 1. Get the input matrix using np.array()   
 2. Find the 2-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places.

```
## Program:
```
```
Python
# Register No:23004426
# Developed By: Tirupathi Jayadeep
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/23004426/Norm-of-a-matrix/assets/144979327/0fd70f3b-a661-4c85-a369-f6ce1580387b)

### 2-Norm of a Matrix
![Screenshot 2023-12-25 105739](https://github.com/23004426/Norm-of-a-matrix/assets/144979327/75ad9c5b-3ce3-4092-8195-6b32fa5dce7d)

### Infinity Norm of a Matrix
![Screenshot 2023-12-25 105739](https://github.com/23004426/Norm-of-a-matrix/assets/144979327/0c3625cb-2b4d-491d-ae12-2c97a6af2e79)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
