# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from one file to another file.

### Step 2:
Using key word "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using "w" which is used to write only.

### Step 5:
The for fuction is used to take the each line from the main file.

### Step 6:
Write() is used to write the lines of main file to the empty file or do the directed file.

### Step 7:
print the output.

## PROGRAM:
```python
with open("file.txt","r")as fp:
    x=fp.read()
with open("file1.txt","w") as fp1:
    fp1.write(x)
```
### OUTPUT:
![output (2)](https://github.com/S-ARVIND01/copy-file/assets/118707337/3e451b69-ba27-4556-98c5-34c6b7de6e29)
![output2](https://github.com/S-ARVIND01/copy-file/assets/118707337/6030841d-1307-48b4-91c7-5120bb68bae0)
![output1](https://github.com/S-ARVIND01/copy-file/assets/118707337/d667e257-d542-465a-8b26-dda31456c1dc)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
