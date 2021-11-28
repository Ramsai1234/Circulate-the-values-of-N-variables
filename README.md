# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create the program
### Step 2: 
Assign the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Display the output of the program.
### Step 6: 
End the program.
## Program:
```
#Program to circulate N values.
#Developed by:P.RAMSAI 
#RegisterNumber:21000888
def circulate():
    l=[10,20,30,40,50,60]
    n=int(input())
    p=l[n:]+l[:n]
    print("After circulating the values are:",p)
```
## Output:
![OUTPUT](/IMAGES/img5.png)

## Result:
Thus the program to circulate the variables is completed sucessfully.