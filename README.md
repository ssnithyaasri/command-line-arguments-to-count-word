# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
Open file using commandline arguments.

### Step 3:
Using for loop find the word count from the contents of a file.

### Step 4:
Use len to count number of words.

### Step 5:
Give print statement.

### Step 6:
End the program. 

## PROGRAM:
```
#program to find commaa=nd-line-arguments-to-count-word
#developed by:Nithyaa sri S S
#register number:22008434

import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```

### OUTPUT:
![](command%20line%2033.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
