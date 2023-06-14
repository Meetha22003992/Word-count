# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC, Anaconda - Python 3.7
## ALGORITHM: 
1. Obtain the input of the file.
2. Initiate word count is 0.
3. Split the line using line.split().
4.  Get the len of words and increment it.
5. Print the number of words got.
## PROGRAM:
```
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
Text File:

![image](https://github.com/Meetha22003992/Word-count/assets/119401038/74bdc6e8-ca76-41d8-89aa-dd3e7be60f38)

![image](https://github.com/Meetha22003992/Word-count/assets/119401038/909e6a0b-c9f0-4dd7-8015-1f57ad413934)

## RESULT:
Thus the program is written to find the word count from a text.
