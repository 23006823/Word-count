# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file using notepad with extension txt
### Step 2: 
open goole colab and mount the drive for using the created file 
### Step 3: 
now open the text file in read mode
### Step 4:  
Then read and split file using the read() and split() which is assigned to the variable
### Step 5: 
print the assinged variables length using len() function
### Step 6: 
end of the program
## PROGRAM:
 ```
#count the number of words in a text file
#developed by: M GAYATHIRI ROSHINI
#register number:23006823
with open('/content/drive/Mydrive/record/content.txt','r') as f:
  a=f.read().split()
  print(len(a))
 ```
### OUTPUT:
1.TEXT FILE:
![image](https://github.com/23006823/Word-count/assets/138971409/d98e891f-019b-457d-b3e3-9e96f9124fe5)
2.MOUNT DRIVE:
![image](https://github.com/23006823/Word-count/assets/138971409/062d65cc-80e4-4d29-90a1-ab7b4621a19f)
3.OUTPUT:
![image](https://github.com/23006823/Word-count/assets/138971409/6974ee58-f732-4b61-8bbb-c49b4e5f8b7b)
## RESULT:
Thus the program is written to find the word count from a text.
