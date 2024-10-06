# DATE:
# EX:6- Find the maximum of a list of numbers
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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large




```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
    


```



## Output:
![Screenshot 2024-10-06 203445](https://github.com/user-attachments/assets/e8553dd1-3adf-4389-a968-3773914ba910)
![Screenshot 2024-10-06 203454](https://github.com/user-attachments/assets/9eab31ca-2819-44f3-bcc3-efc80e443ff6)
![Screenshot 2024-10-06 203504](https://github.com/user-attachments/assets/8b93d30a-e586-4609-b34a-bc5be8e2b68d)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
