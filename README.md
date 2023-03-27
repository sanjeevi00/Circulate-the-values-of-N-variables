# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define the calcualte value 
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list

### Step 4: 
print the values
### Step 5: 
end the program
## Program:
```
#Program to circulate N values.
#Developed by:SANJEEVI J 
#RegisterNumber:212222110040
def circulate():
    l=eval(input())
    n=int(input())
    result=l[n:]+l[:n]
    print("After circulating the values are:",result)

```
## Output:
![image](https://user-images.githubusercontent.com/121484976/227839234-48260868-104d-4722-a509-9ec1d7d84e3c.png)

## Result:
The program is executed sucessfully!
