# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
```
## Step 1:
Create two txt file.A file which has content [lines.txt] to be copied to the empty [text.txt]file.

## Step 2:
Using write() function to copy the content from line.txt to empty file,text.txt.

## Step 3:
Save and run the python program in terminal.

## Step 4:
The text from the lines.txt file is copied to the empty file text.txt.

## Step 5:
Then the text is shown in empty file text.txt.

## Step 6:
Result is obtained.
```
## PROGRAM:
'''
Reference no: 21005572
Developed by: Rakshitha devi.J
'''
```
with open('lines.txt','r') as file1:
    with open('text.txt','w') as file2:
        for line in file1:
            file2.write(line)
```
### OUTPUT:
### copy.py:
![image](https://user-images.githubusercontent.com/94165326/153892248-d0e339b6-b30b-4a82-8c2a-a580e01f4198.png)



### line.txt:
![image](https://user-images.githubusercontent.com/94165326/153892370-95d3cf9d-7623-4087-b23e-eecc7b177dea.png)


### Terminal and text.txt:
![image](https://user-images.githubusercontent.com/94165326/153892573-87d3e100-0f4b-4d0a-b01d-3cd759ac5c59.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
