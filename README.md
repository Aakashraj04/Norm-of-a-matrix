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
# Register No: 22008579
# Developed By: Aakashraj M


# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)


# 2-Norm of a Matrix

import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121117266/214569607-7c930c46-148a-46b0-90bc-60edda6c8ab1.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121117266/214569689-5a0cefaa-5099-4542-b853-faf665cded63.png)


### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/121117266/214569778-cba7c63e-c691-4a57-810b-fd2e4f742d34.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
