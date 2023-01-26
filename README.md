# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from which we need to copy the text.

### Step 2:
Using keyword "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'w' which is used to write only.

### Step 5:
The for function is used to take each line from the main file.

### Step 6:
write() is used to write the lines of main file to the empty file or to the directed file.

### PROGRAM:

```
'''
Developed by:KANISHKAR M
Register Number:22007816
'''
with open('text.txt','r') as firstfile:
    with open('text2.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:

#### First File

![5c data1](https://user-images.githubusercontent.com/118886772/214780092-3aa99abe-1728-4851-b91b-c6ee8f169ce6.png)

#### Code File

![5c kan](https://user-images.githubusercontent.com/118886772/214780159-b04090f2-d36a-49b0-9a1d-fce304a0e67c.png)

#### Output File

![5c output](https://user-images.githubusercontent.com/118886772/214780275-37ef9fa5-cfe3-400b-94e6-a2bac1d99457.png)

## RESULT:

Thus the program is written to copy the contents from one file to another file.
