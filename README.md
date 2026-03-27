# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Algorithm for 1-Norm of a Matrix

1. **Start the program**
2. **Read the input matrix** and convert it into a NumPy array `mat`
3. **Import NumPy library** for matrix operations
4. **Compute 1-norm** using `np.linalg.norm(mat, 1)`
5. **Format, display the result, and stop**

---

### Algorithm for 2-Norm of a Matrix

1. **Start the program**
2. **Read the input matrix** and convert it into a NumPy array `mat`
3. **Import NumPy library** for matrix operations
4. **Compute 2-norm** using `np.linalg.norm(mat, 2)`
5. **Format, display the result, and stop**

---

### Algorithm for Infinity Norm of a Matrix

1. **Start the program**
2. **Read the input matrix** and convert it into a NumPy array `mat`
3. **Import NumPy library** for matrix operations
4. **Compute infinity norm** using `np.linalg.norm(mat, np.inf)`
5. **Format, display the result, and stop**


## Program:
```Python
# Register No: 212225240090
# Developed By: Monisha D
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

# 3-Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
<br><img width="1854" height="541" alt="Screenshot 2026-03-20 141647" src="https://github.com/user-attachments/assets/86a2d616-ef99-44a8-af00-401fd75c5472" />


### 2-Norm of a Matrix
<br><img width="1826" height="871" alt="Screenshot 2026-03-20 141141" src="https://github.com/user-attachments/assets/39659071-85a0-4e87-9661-64c46afa6935" /> 


### Infinity Norm of a Matrix
<br><img width="1882" height="576" alt="Screenshot 2026-03-20 141535" src="https://github.com/user-attachments/assets/4d60f0e2-0e75-482b-8d54-377846dd2807" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
