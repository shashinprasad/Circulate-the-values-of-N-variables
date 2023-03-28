# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values from the user
### Step 2:
Use functions and pass parameters.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print circulated values.
### Step 6: 
End the program.
## Program:
```
#Program to circulate N values.
#Developed by: Shashin prasad.s
#RegisterNumber:212222230144
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:

![Screenshot 2023-03-28 103313](https://user-images.githubusercontent.com/129143499/228134322-e65e94c3-30b4-422e-b798-7d4841359ae8.png)

## Result:
Thus the circulate-the-values-of-N-variables are successfully executed.
