# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Get the file name and location from the user.

### Step 2: Give a new file name to create a copy of a file content.
 
### Step 3: Read the file and close the file.

### Step 4:  Now write the content in the new file.

### Step 5: When done print "File copied successfully".

### Step 6: End of the program.

## PROGRAM:
```Program For Copying The Contents:
Developed by: SILAMBARASAN.K
RegisterNumber: 21500586 

with open ('copy1.txt') as c1:
    with open ('copy2.txt','w') as c2:
        for line in c1:
            c2.write(line)
```

### OUTPUT:
![git log](Screenshot1.png)
![git log](Screenshot2.png)
![git log](Screenshot3.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.