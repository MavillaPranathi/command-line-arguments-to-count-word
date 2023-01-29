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
 Open file using open().
### Step 3: 
Use for loop.
### Step 4:  
Use len to count number of words.
### Step 5: 
Give print.
### Step 6: 
output will come
## PROGRAM:
```
developed by:m.pranathi
refrence number:22005710

import sys 
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("word count in file =",count)
```

### OUTPUT:
![command line arguments](https://user-images.githubusercontent.com/118343610/215310562-3233f0e1-ceb3-49a1-a97f-190b61a5531e.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
