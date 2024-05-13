# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.
### Step 6: 
End the program.
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: RATHEESH KUMAR B R
RegisterNumber: 212223110040

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![image](https://github.com/Ratheesh28/Copy-File/assets/138849186/f5925c00-0082-413a-8757-9ac1628250a1)
![image](https://github.com/Ratheesh28/Copy-File/assets/138849186/bb56beec-b89b-4f4a-9ec4-42c65df369a6)
![image](https://github.com/Ratheesh28/Copy-File/assets/138849186/fdc84e06-f837-4d7f-a368-d045de7db98a)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
