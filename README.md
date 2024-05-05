# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix\
'''\
Program to find L and U matrix using LU decomposition.\
Developed by:INFANTINA MARIA L \
RegisterNumber:212223100013\
'''\
import numpy as np\
from scipy.linalg import lu\
matrix=np.array(eval(input()))\
pivot,l_matrix,u_matrix=lu(matrix)\
print(l_matrix)\
print(u_matrix)

(ii) To find the LU Decomposition of a matrix\
'''\
Program to solve a matrix using LU decomposition.\
Developed by:INFANTINA MARIA L \
RegisterNumber:212223100013\
'''\
import numpy as np\
from scipy.linalg import lu_factor,lu_solve\
A=np.array(eval(input()))\
b=np.array(eval(input()))\
lu,piv=lu_factor(A)\
X=lu_solve((lu,piv),b)\
print(X)
## Output:
![Screenshot 2024-05-05 230723](https://github.com/INFANTINA1401/LU-Decomposition/assets/147313821/78c2735a-bdfe-4d1e-8f36-ba6cedeec033)

![Screenshot 2024-05-05 230731](https://github.com/INFANTINA1401/LU-Decomposition/assets/147313821/50b3884f-990f-4ca0-8b08-ba01b72a651c)

![Screenshot 2024-05-05 230746](https://github.com/INFANTINA1401/LU-Decomposition/assets/147313821/3edb6ff5-5ce0-4de5-bc12-434372477ec0)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

