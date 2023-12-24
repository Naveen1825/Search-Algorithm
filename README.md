# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Naveenkanthan L
RegisterNumber: 23007705
'''
def max_marks(marks):
    marks.sort()
    return marks[len(marks)-1]

```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
def max_marks(marks):
    return max(marks)
```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
def max_marks(list1):
    list1.sort()
    return list1[len(list1)-1]
```
## Sample Input and Output



![max_marks1](https://github.com/Naveen1825/Search-Algorithm/assets/138969868/83bf11aa-d576-45d6-8ba2-75b5eeb0121b)

## OUTPUT 
### 1st program
<img width="612" alt="290136933-10c17172-af89-4ffc-8e6f-b5042959a3c9" src="https://github.com/Naveen1825/Search-Algorithm/assets/138969868/7fb486d0-9cf3-4b15-99a7-cba58a051afd"><br>
### 2nd program
<img width="609" alt="290137018-66d8c195-42de-496e-849f-ee088637940c" src="https://github.com/Naveen1825/Search-Algorithm/assets/138969868/b4d00dbb-3712-4174-9008-e5a18617b449"><br>
### 3rd program
<img width="604" alt="290137111-5579400a-f9a9-4223-bc52-eca7562aec20" src="https://github.com/Naveen1825/Search-Algorithm/assets/138969868/4f610d45-2f96-4fa6-a36e-a9fee2ae3d62"><br>
## Result
Thus the linear search and binary search algorithm is implemented using python programming.
