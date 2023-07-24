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

i)	To find the maximum of marks using the list method sort.
```python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
def max_marks(marks):
    marks.sort()
    b = marks[-1]
    return b

```

ii)	To find the maximum marks using the list method max().
```python
''' 
Program to find the maximum marks using the list method max().
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
def max_marks(marks):
    b = max(marks)
    return b
```

iii) To find the maximum marks without using builtin functions.
```python
''' 
Program to the maximum marks without using builtin functions.
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
def max_marks(list1):
    d = list1[0]
    for i in list1:
        if i>d:
            d=i
    return d
        
```

## Output:
#### 1. The maximum of marks using the list method sort
![output1](out1.png)
#### 2. The maximum marks using the list method max()
![output2](out2.png)
#### 3. The maximum marks without using builtin functions
![output3](out3.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.