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
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
DEVELOPED BY: THARUN DP
REGISTER NUMBER:25018717
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
a='{:.2f}'.format(ans)
print(a)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yournameTHARUN DP
RegisterNumber: 25018717
'''
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n=f'{a:.2f}'
print(n)




# Infinity Norm of a Matrix


'''DEVELOPED BY: THARUN DP
REG NUMBER: 25018717
'''
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n=f'{a:.2f}'
print(n)


```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1182" height="209" alt="Screenshot 2025-10-21 102300" src="https://github.com/user-attachments/assets/72abaf38-b49e-4ce0-8211-db055ce41531" />
<br>

### 2-Norm of a Matrix
<br>
<img width="1180" height="253" alt="Screenshot 2025-10-21 102358" src="https://github.com/user-attachments/assets/90bf277e-aac9-48ff-abc9-3d579eb0fbdf" />
<br>

### Infinity Norm of a Matrix
<br>
<img width="1071" height="205" alt="Screenshot 2025-10-21 102429" src="https://github.com/user-attachments/assets/3d0db3e6-7b70-484d-b418-84815cd0246c" />
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
