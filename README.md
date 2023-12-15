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
```
Program to mark the maximum of marks using the list method sort
Developed by: RAJARAMAN V
RegisterNumber: 23014299
def max_marks(marks):
    marks.sort()
    highest=marks[-1]
    return highest



```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: RAJARAMAN V
RegisterNumber: 23014299
def max_marks(marks):
    marks1=max(marks)
    return marks1


```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: RAJARAMAN V 
RegisterNumber: 23014299
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```

## Output:

  ![image](https://github.com/Rajaraman77/FindMaximum/assets/150319383/d1ee5d3d-d651-4141-bec3-aff9c34bc8d1)

  ![image](https://github.com/Rajaraman77/FindMaximum/assets/150319383/ee973ca7-73ae-456e-970a-c5155a542bd4)

  ![image](https://github.com/Rajaraman77/FindMaximum/assets/150319383/3acddbd3-f2f1-4530-b359-3192b834c41b)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
