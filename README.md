# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

   1.PC
   2.Anaconda - Python 3.7
   
## ALGORITHM: 

### Step 1:

import numpy as np

### Step 2: 
 
 Enter the correct input values
 
### Step 3: 

write a python program for getting the word count from the contents of a file using command line
arguments.

### Step 4: 

Use command line srguments

### Step 5: 

End of the program

## PROGRAM:
```
'''
developed by : Tejusve Kabeer.F
reference.no : 22002543
'''
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: Tejusve Kabeer.F")
print("word count in file = ",count)
```
### OUTPUT:
![cmdlin](https://user-images.githubusercontent.com/118364993/214821918-638c593c-b454-4d5d-814b-b2b1f149a184.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
