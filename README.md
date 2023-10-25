# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:  
Get the value from the user for the number of rotation
### Step 2:
Using the slicing concept rotate the list

## Program:
```
# Program to circulate N values.
# Developed by:Amruthavarshi Gopal 
# RegisterNumber:23000851
def circulate():
    l=eval(input())
    n=int(input())
    a=l[n:]+l[:n]
    print("After circulating the values are:",a)
```

## Output:
![Alt text](circulating.png)

## Result:
Thus the circulation of n variables are successfully executed
