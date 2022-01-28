# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
 Open a file which has to be filled.
### Step 2: 
  open a file which has to be copied.
### Step 3: 
  Using write function copy the file contents.
### Step 4:  
  Use with keyword to open the files.
### Step 5: 
  Run the code using terminal.
### Step 6: 
  Now the contents are copied.
## PROGRAM:
```
Name:J.Archana priya 
Reg.no:21500533

with open('text1.txt','w') as file1:
    with open("text2.txt",'r') as file2:
        for words in file2:
            file1.write(words)
```

### OUTPUT:
![Program](./Program.png)
![File2](./File2.png)
![File1](./File1.png)





## RESULT:
Thus the program is written to copy the contents from one file to another file.