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
Developed by: Dharini PV
RegisterNumber: 212222240024
'''
def max_marks(marks):
    marks.sort()
    return (marks[-1])
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Dharini PV
RegisterNumber: 212222240024
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Dharini PV
RegisterNumber: 212222240024
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Output:

## To find the maximum of marks using the list method sort
![image](https://github.com/DHARINIPV/FindMaximum/assets/119400845/227a9bdc-8c92-4f53-a21c-739b2a65d95e)

## To find the maximum marks using the list method max()
![image](https://github.com/DHARINIPV/FindMaximum/assets/119400845/a9ecc932-3ec5-4b7f-8524-406b09da19d2)

## To find the maximum marks without using builtin functions
![image](https://github.com/DHARINIPV/FindMaximum/assets/119400845/5752c222-6501-46e9-b400-928bfb9a893e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
