# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension.

### Step 2: 
Add some texts in that file.

### Step 3: 
Create a python file.

### Step 4:  
Write a code to count the number of words in that file.

### Step 5: 
Run the program.

### Step 6: 
Display the output.

## PROGRAM:
```
#Developed by: SRIVATSAN V
#Register Number: 23000970
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```

### OUTPUT:
![Screenshot 2023-12-26 091421](https://github.com/Srivatsan0405/Word-count/assets/139841630/e3911f9d-833f-45f2-8f11-fc9232c79094)
![Screenshot 2023-12-26 091435](https://github.com/Srivatsan0405/Word-count/assets/139841630/763e0476-47a2-4d46-b8ab-f6b55b76cacf)
![Screenshot 2023-12-26 091459](https://github.com/Srivatsan0405/Word-count/assets/139841630/2e5207da-2466-4960-9848-61d8d03a0c45)




## RESULT:
Thus the program is written to find the word count from a text.
