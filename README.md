# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Assign the values of second variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6:
End the program
## Program:
```
#Program to circulate N values.
#Developed by:Prem Kumar G
#RegisterNumber:23003614
def circulate():
     l=eval(input())
     n=int(input())
     l=l[n:]+l[:n]
     print("After circulating the values are:",l)

```
## Output:
![output](https://github.com/PremkumarG3/Circulate-the-values-of-N-variables/assets/138955646/c8be6381-84c2-484b-860e-b339f0d2ec78)

## Result:
Thus the circulate n variables are successfully executed
