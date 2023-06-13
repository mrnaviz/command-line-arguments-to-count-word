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
 initially make count = 0
### Step 3: 
open the content file using command line arguments.
### Step 4:  
by using for loop name the function as "line"
### Step 5: 
split the line using .split
### Step 6: 
split the line using .spli
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: NAVEEN KUMAR.B
Register Number: 212222230091

import sys
fp=open(sys.argv[-1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:

![image](https://github.com/mrnaviz/command-line-arguments-to-count-word/assets/123350791/dbe1fa9a-7e92-41bd-a13e-bd0603e6f3ef)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
