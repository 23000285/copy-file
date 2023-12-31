# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a function named copy that takes two file names as input.

### Step 2: 
Prompt the user to enter the name of the existing file to copy and the name for the new file.
 
### Step 3: 
Open the existing file in read mode ('r') and create the new file in write mode ('w').

### Step 4:  
Read the entire contents of the existing file into a variable.

### Step 5: 
Write the contents of the variable to the new file.

### Step 6: 
Ensure both files are properly closed.

## PROGRAM:
```
#Python program for copying the contents from one file to another file.
#Developed by: VENKATANATHAN P R
#Register Number: 23000285

def copy(fname, newfile):
    with open(fname, 'r')as fp:
        with open(newfile, 'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname, newfile)
```
### OUTPUT:
![image](https://github.com/23000285/copy-file/assets/138970859/c733a7ca-a55e-418a-af0d-f77eb4759701)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
