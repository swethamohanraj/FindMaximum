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
```def max_marks(marks):
    marks.sort()
    largest_value=marks[-1]
    return largest_value
    
```

ii)	# To find the maximum marks using the list method max().
```def max_marks(marks):
    max=0
    for i in marks:
        if max<i:
            max=i
    return max
```

iii) # To find the maximum marks without using builtin functions.
```def max_marks(marks):
    marks.sort()
    largest_value=marks[-1]
    return largest_value

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://user-images.githubusercontent.com/94228215/149768337-f4267702-f165-4af4-9ce0-4336053aaae3.png)
![image](https://user-images.githubusercontent.com/94228215/149768560-3a47c380-fc5f-4c0a-9110-8cce4165cc6e.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
