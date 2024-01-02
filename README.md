# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```
# program for copying the contents from one file to another file.
# Developed by: Kishore A
# Reference number:23008675
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### File:
![sample1](https://github.com/Ashwathm12/copy-file/assets/138849225/9e9250af-64ef-42cf-8b27-ab5238ec481c)

### OUTPUT:

![Screenshot 2024-01-01 132933](https://github.com/Ashwathm12/copy-file/assets/138849225/0b5f2663-4cc8-4ec4-ae30-bbf00599b870)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
