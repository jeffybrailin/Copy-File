# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
Open the source file in read mode.
### Step 3: 
Read the contents of the source file.
### Step 4:  
Open (or create) the destination file in write mode.
### Step 5: 
Write the contents into the destination file.
### Step 6: 
Close both the files and stop the program.
## PROGRAM:
```
try:
    with open("source.txt", "r") as source_file:
        content = source_file.read()

    with open("destination.txt", "w") as destination_file:
        destination_file.write(content)

    print("File copied successfully!")

except FileNotFoundError:
    print("Error: source.txt file not found!")

```
### OUTPUT:
<img width="536" height="167" alt="image" src="https://github.com/user-attachments/assets/a9751e5a-356b-4b7b-b4dd-feef57c46f8a" />



## RESULT:
Thus the program is written to copy the contents from one file to another file.
