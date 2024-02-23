# Swapping-two-values
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:
```
#Developer Name : Prasanth E
#Reference Number : 212221233002
def swap_variables(x, y):
  temp = x
  x = y
  y = temp
  return x, y
a = int(input())
b = int(input())
a, b = swap_variables(a, b)
print("Swapped values are:", a, b)
```
## output
![Screenshot (8)](https://github.com/PrasanthE2001/Swapping-two-values/assets/114572171/5694653b-911f-4b6d-8460-531ced7858cc)



## RESULT:
Thus the swapping of two values are successfully executed



