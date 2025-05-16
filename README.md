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
# Register No:21222410034
# Developed By:Madhu Shrie J
# 1-Norm of a Matrix
```
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
```




# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix

![Screenshot 2025-05-12 083724](https://github.com/user-attachments/assets/c9578c27-2ac3-4055-9dd4-dcb8d7e79985)



### 2-Norm of a Matrix

![Screenshot 2025-05-12 083839](https://github.com/user-attachments/assets/f2d33b76-109d-4157-b041-18580a085356)


### Infinity Norm of a Matrix
![Screenshot 2025-05-12 083905](https://github.com/user-attachments/assets/1df8243a-2368-492a-baba-239583e6b7c6)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
