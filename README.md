# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
First, crate a file in txt mode.

## Step 2:
next Decleare number of words is 0

## Step 3:
Give range for i

## Step 4:
Then nxt split the words

## Step 5:
count the number of words

## Step 6:
putting print statement for getting output

## PROGRAM:
```
'''Program to count the words in a file
Developed by: K R HASHISH VIDYA SAGAR
Register Number: 212222230047
'''
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:

![py xp 5b](https://github.com/hashish9275/Word-count/assets/118707521/7e2a3799-943a-452b-8d78-ff882fd7e73b)


## RESULT:
Thus the program is written to find the word count from a text.
