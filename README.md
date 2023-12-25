# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with.text extension

### Step 2: 
Add some extensions
 
### Step 3: 
Create a python file

### Step 4:  
Write a code to count the number of words in that file

### Step 5: 
Run the program

### Step 6: 
Display the out put

## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("total number of words:",count)
program() 

```

### OUTPUT:
![Alt text](<Screenshot 2023-12-25 125643.png>)
![Alt text](<Screenshot 2023-12-25 125706.png>)
![Alt text](<Screenshot 2023-12-25 125633.png>)


## RESULT:
Thus the program is written to find the word count from a text.
