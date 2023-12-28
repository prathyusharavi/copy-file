# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file

### Step 2: 
write some lines in that file
 
### Step 3: 
create a python file

### Step 4: 
write a code to copy the  content of the  new file

### Step 5: 
run the program

### Step 6: 
display the output

## PROGRAM:
```
##Developed by:YENUGANTI PRATHYUSHA
##RegisterNumber: 23009045
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![image](https://github.com/prathyusharavi/copy-file/assets/147474424/7355252f-764f-433c-9270-f5a89fced834)
![image](https://github.com/prathyusharavi/copy-file/assets/147474424/46982cdb-9745-4a75-9ba5-ff85f50fa2ed)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
