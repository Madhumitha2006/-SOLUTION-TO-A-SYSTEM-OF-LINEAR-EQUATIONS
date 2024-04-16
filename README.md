# EX:1.SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

# Date:

## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program

## Program:
```
Developed by:Madhu mitha V
RegisterNumber:2305002013  

`````
```python
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
solu=np.linalg.solve(A,B)
print(solu)
```
## Output:
![Screenshot 2024-04-16 103530](https://github.com/Madhumitha2006/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155508589/94ca9985-d562-40b0-835c-12bbfb6ff26f)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

