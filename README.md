# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Start

### Step 2: Open the first file in read mode by an appropriate method.
 
### Step 3: Open the Second file in write mode by an appropriate method.

### Step 4:  Loop until a variable 'i' in the first file.so Variable i propagates all over the content

### Step 5: Loop until a variable 'i' in the first file.so Variable i propagates all over the content.

### Step 6: Stop

## PROGRAM:

```python
#Develpoed By:A.Ruchitha Reddy
#Reference No:21005032
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
    # read content from first file
    for line in firstfile:
        # append content to second file
        secondfile.write(line)
```
### OUTPUT:
![output](https://github.com/Shaik-sameer-AIML/copy-file/blob/main/copy%203.JPG?raw=true)
![output](https://github.com/Shaik-sameer-AIML/copy-file/blob/main/copy%201.JPG?raw=true)
![output](https://github.com/Shaik-sameer-AIML/copy-file/blob/main/copy2.JPG?raw=true)


## RESULT:
Thus the program is written to copy the contents from one file to another file.