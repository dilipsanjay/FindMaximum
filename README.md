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
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```

## Output:
![image](https://github.com/dilipsanjay/FindMaximum/assets/155506948/a65fa9bf-8309-47a3-8c23-d2cf87ec265e)
![image](https://github.com/dilipsanjay/FindMaximum/assets/155506948/4c478128-c36e-4751-910c-b981b44e057e)
![image](https://github.com/dilipsanjay/FindMaximum/assets/155506948/e95bd38a-90fd-40fb-95d3-bf82f44e263f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
