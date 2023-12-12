# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: PRITHIVIRAJAN V
RegisterNumber: 23003859
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: PRITHIVIRAJAN V
RegisterNumber: 23003859
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:PRITHIVIRAJAN V
RegisterNumber: 23003859
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
OUTPUT 1
![image](https://github.com/Prithivirajan2911/FindMaximum/assets/147020085/1211dab4-8556-4622-9b75-75b034d29532)
OUTPUT 2
![image](https://github.com/Prithivirajan2911/FindMaximum/assets/147020085/6c8dd7db-e6cf-451f-92ce-bc949aa1fe42)
OUTPUT 3
![image](https://github.com/Prithivirajan2911/FindMaximum/assets/147020085/dbd59147-a868-4e38-8a8b-afad5c3917e5)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
