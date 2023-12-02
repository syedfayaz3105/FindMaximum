![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/1ea5c3dc-3bb0-4f1d-981e-93df13fe4686)# Find the maximum of a list of numbers
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
Developed by: Farhana H
RegisterNumber: 23012987
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Farhana H 
RegisterNumber: 23012987
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Farhana H
RegisterNumber: 23012987
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/8bb6aaa4-2c3f-4390-af4a-d6fa429b3df1)
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/c1061f3e-ec12-4c3d-a9f2-8ded99990307)
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/b8bbea69-c11b-4787-8494-23a7a0e0fd98)


## Output:
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/362f4cee-b57c-4880-b882-f7819c5dd5a7)
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/b8ab2a1e-1cfb-43fc-9baf-a7537c52896c)
![image](https://github.com/syedfayaz3105/FindMaximum/assets/147144126/1537ef27-5998-4ead-ad5f-6acc8ebd488d)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
