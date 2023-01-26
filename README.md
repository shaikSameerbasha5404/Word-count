# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the variable to count the number of words in the file and defined with 0.
### Step 2: 
 Open the text file using the with open keyword.
### Step 3: 
Using r command i.e:read mode.
### Step 4:  
Using for loop iterate the file to split the space in the words.
### Step 5: 
The splited and stored in the variable, use len() function of the splited word variable.
### Step 6: 
End the program.
## PROGRAM:
```python
# Developed By: Shaik sameer basha
# Reference number: 22004926
num_words=0
with open('text.txt','r') as f1:         
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in a file = {}".format(num_words))
```
### OUTPUT:
![5a](https://user-images.githubusercontent.com/118707756/214848323-e469481b-976b-4e45-a94b-8b2a77d15e43.jpg)
## RESULT:
Thus the program is written to find the word count from a text.
