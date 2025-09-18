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
# Register No: 212224230059
# Developed By: C Dharshan
```
# 1-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm="{:.2f}".format(ans)
print(Norm)

```

# 2-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("%.2f"%(ans))

```

# Infinity Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("%.2f"%(ans))
```
## Output:
### 1-Norm of a Matrix

<img width="1230" height="344" alt="Screenshot 2025-09-18 084943" src="https://github.com/user-attachments/assets/f08ca39e-59a6-480d-919c-ccf15de19414" />

### 2-Norm of a Matrix

<img width="1217" height="384" alt="Screenshot 2025-09-18 084952" src="https://github.com/user-attachments/assets/2bece3a3-e8b2-4041-b995-4fa57164103d" />

### Infinity Norm of a Matrix

<img width="1229" height="342" alt="Screenshot 2025-09-18 085002" src="https://github.com/user-attachments/assets/6d051b04-d383-4553-b936-eec4ff63dbcf" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
