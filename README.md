# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Obtain the input of the file.

### Step 2: Initiate word count is 0.
 
### Step 3: Split the line using line.split().

### Step 4:  Get the len of words and increment it.

### Step 5: Print the number of words got.

## PROGRAM:
fname=input("Enter file name: ")

num_words=0

with open(fname,'r') as f:

    for line in f:
    
        words=line.split()
        
        num_words+=len(words)
        
print("Number of words: ",num_words)

### OUTPUT:
![image](https://github.com/Meetha22003992/Word-count/assets/119401038/1ca83139-46b3-42a3-8ff1-5c52f4cb2723)

## RESULT:
Thus the program is written to find the word count from a text.
