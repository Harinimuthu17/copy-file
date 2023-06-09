# copy-file


## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Create a text1.txt with some content in it

### Step 2:
Open the text1.txt file in read mode

### Step 3:
Create a copy.txt file using write mode

### Step 4:
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```

Program for copying the contents from one file to another file
Developed by:M.Harini
RegisterNumber: 212222240035

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)


```
### OUTPUT:

![image](https://github.com/Harinimuthu17/copy-file/assets/130278614/3b3085fc-8c1f-4325-9c5d-00a36c6d8cca)


![image](https://github.com/Harinimuthu17/copy-file/assets/130278614/ffadcef6-9c6d-43ff-acaf-8a92981b9006)


![image](https://github.com/Harinimuthu17/copy-file/assets/130278614/fa88dad3-bb19-404d-be9e-dc6d9c87f502)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
