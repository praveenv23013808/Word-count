# 5a.Word-count

## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:Open then required file by using the function"with"
### Step 2:Using split function to split the words.
### Step 3:Finding the length of the words by using len() function.
### Step 4:Calling the function and printing the number of words.
## PROGRAM:
```
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)
```
### OUTPUT:
![Screenshot 2023-11-18 120157](https://github.com/praveenv23013808/Word-count/assets/145824728/81d4fe1e-1abb-4a21-a281-64c531f53750)

![Screenshot 2023-11-18 120314](https://github.com/praveenv23013808/Word-count/assets/145824728/0b732bd4-89c6-4dd9-b827-8139fc84a96d)



## RESULT:
Thus the program is written to find the word count from a text.
