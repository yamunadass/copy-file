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
### Step 5: 
End the program
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Yamuna M
RegisterNumber: 212223230248

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/yamunadass/copy-file/assets/138971172/bb7fa25e-4f54-4b26-85de-b7fc7482a14c)
![image](https://github.com/yamunadass/copy-file/assets/138971172/cae360d5-4917-47ea-a1f0-021c33978b45)
![image](https://github.com/yamunadass/copy-file/assets/138971172/c3e31ce6-c1a6-475e-841f-513dbe37e601)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
