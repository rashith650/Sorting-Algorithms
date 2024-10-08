### Date :
# Ex-8 : Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
Program to find the square root for the given number(newton's method) using function.</br>
Developed by: Mohamed Rashith</br>
RegisterNumber : 24001082</br></br>
i)	#Selection Sort
```
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)
```
ii)	#Insertion Sort
```
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)
```

## Output:
![8 1](https://github.com/user-attachments/assets/9a220c3b-61dc-4af1-b0cb-c43bc9f10069)
![8 2](https://github.com/user-attachments/assets/fa8e25a8-5511-44bb-93bd-c25850c6fc50)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
