# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open terminal and activate conda, then open jupyter notebook.

### Step 2: 
Create a text file in jupyter notebook or upload a text file in the jupyter notebook.
 
### Step 3: 
Open a new cell in jupyter notebook.

### Step 4: 
Type the program in the cell.

### Step 5: 
Now in the output box,type the file name.

### Step 6: 
End the program.

## PROGRAM:
```
#Developed by: JAYAMANI R
#Reference No: 22008124
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:
Text File:
![Screenshot from 2023-01-26 14-55-56](https://user-images.githubusercontent.com/85949888/214801216-cc88be45-d7be-4192-b659-423f27fa32d7.png)

![Screenshot from 2023-01-26 14-52-41](https://user-images.githubusercontent.com/85949888/214801001-5548a44e-d847-4380-a00f-c635e9fa43c3.png)


## RESULT:
Thus the program is written to find the word count from a text.
