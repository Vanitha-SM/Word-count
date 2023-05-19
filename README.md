# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file object and get file name from the user
### Step 2: 
Open the file given by the user
### Step 3: 
Using for loop acess the file
### Step 4:  
Use split funtion to separate the words
### Step 5: 
The words is then counted by len function
### Step 6: 
Print the number of words
## PROGRAM:
```
'''
Program to count the number of words in a file
Developed by: Vanitha S
Register Number: 212222100057
'''
fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
  for line in f:
    word=line.split()
    words+=len(word)
print("Number of words:",words)
```
### OUTPUT:
![WhatsApp Image 2023-05-19 at 11 35 15](https://github.com/Vanitha-SM/Word-count/assets/119557985/12237406-aeb6-4a0a-93d3-1c67c62a66ed)
![2](https://github.com/Vanitha-SM/Word-count/assets/119557985/dd008a97-fdd6-40c1-88c6-2205b63498a6)



## RESULT:
Thus the program is written to find the word count from a text.
