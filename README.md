# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.



### Step 2: 
Read the text using read() function.

 
### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character. 

### Step 4:  

The length of the split list should equal the numbers of words in the test file.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.


### Step 6: 

End the program.

## PROGRAM:

DEVELOPED BY:  naresh.r
REFERENCE NUMBER: 23005559
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))


### OUTPUT:
![Screenshot 2023-12-25 111019](https://github.com/feryjfgkuyfgewjfgew/Word-count/assets/150319377/9f95c64b-28f2-4cd8-aa7d-5527f883dfaf)

![Screenshot 2023-12-25 111028](https://github.com/feryjfgkuyfgewjfgew/Word-count/assets/150319377/28c87a05-d10e-4720-84f7-051f7d7db50f)

## RESULT:
Thus the program is written to find the word count from a text.
