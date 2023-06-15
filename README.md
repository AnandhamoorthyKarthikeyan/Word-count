# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Open visual studio code.

## Step 2:
Create file with .py extension.

## Step 3:
Start the program.

## Step 4:
write the code

## Step 5:
Run terminal for output of the given program.

## Step 6:
End the program.
## PROGRAM:
```
#Developed by: ANANDHAMOORTHY.K
#Register No: 212222100004
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
for line in f:
words=line.split()
wordslen+=len(words)
print("Number of wordds:",wordslen)

```

### OUTPUT:
![Screenshot 2023-06-15 222338](https://github.com/AnandhamoorthyKarthikeyan/Word-count/assets/119475998/09f6c40f-9250-4a22-9d00-366bafa8578e)

## RESULT:
Thus the program is written to find the word count from a text.
