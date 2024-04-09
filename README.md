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
Name:Santhosh G
Reference no:212223240152
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
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```



## Output:
![Screenshot 2024-04-09 165614](https://github.com/GSanthosh007/FindMaximum/assets/147527586/59eef0a0-211b-4470-b4a6-fcedd4a6d709)
![Screenshot 2024-04-09 165653](https://github.com/GSanthosh007/FindMaximum/assets/147527586/9a2b3aad-1a58-4ebe-ae4e-630233c57a68)
![Screenshot 2024-04-09 165715](https://github.com/GSanthosh007/FindMaximum/assets/147527586/f74d793c-7dd5-440d-a127-9bf13c9f12a4)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
