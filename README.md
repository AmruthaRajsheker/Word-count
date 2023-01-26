# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Assign a variable for value zero.
### Step 2: 
Open the required file using the function "with".
### Step 3: 
Then use the for loop for assigning the "i" value in the file 
### Step 4:  
Use split function to split the words 
### Step 5: 
Find the length of the words by using len() function
### Step 6: 
Call the function and print the number of words.

## PROGRAM:
```
'''Program to count the words from a text.
Developed by: Amrutha Rajsheker
RegisterNumber: 22004501
'''
fname = input('Enter filr name: ')
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```

## OUTPUT:
### Text file
![output](/text.png)
### Output
![output](/output.png)

## RESULT:
Thus the program is written to find the word count from a text.
