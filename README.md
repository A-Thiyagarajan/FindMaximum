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

i)To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)To find the maximum marks using the list method max().
```
def max_marks(marks):
    return max(marks)
```

iii)To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
```
## Sample Input:
![output](./img/max_marks1.jpg) 

## Output:
### List method sort:
![max-1](https://github.com/A-Thiyagarajan/FindMaximum/assets/118707693/a747970e-d90a-4af9-ad42-19a464f9204f)





### List method max():



![max-2](https://github.com/A-Thiyagarajan/FindMaximum/assets/118707693/dfe6ccca-5cb6-4641-9fd2-acf2cb71155e)


### Builtin functions:


![max-3](https://github.com/A-Thiyagarajan/FindMaximum/assets/118707693/9c1e2e4d-eee0-4293-b5b6-f388662643fd)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
