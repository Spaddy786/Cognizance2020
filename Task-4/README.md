<<<<<<< HEAD
# __*Binary Search*__
>### __What is Binary Search?__
![Binary search](https://i.ytimg.com/vi/HlEz93t628E/maxresdefault.jpg)
<p>   
Binary search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one.</p>

>### __Difference between Linear and Binary Search__

| Linear Search   |    Binary Search  |
| -------------   |    --------------  |
| Linear search is an algorithm to find an element in a list by sequentially checking the elements of the list until finding the matching element| Binary search is an algorithm that finds the position of a target value within a sorted array.|
| A linear search scans one item at a time without skipping to any item.| A binary search cuts down the search to half as soon as the middle of a sorted list is found.|
|Linear search is easy to use because there is no need for any ordered elements.|The binary search is a bit complicated with elements being necessarily arranged in a given order.|
>>>>### __Program__
```python
  def bsearch(L,n):
       start=0
       end=len(L)-1
       while start<=end:
          mid=(start+end)//2
          if L[mid]==n:
            return True
          elif L[mid]<=n:
            start=mid+1
          else:
          end=mid-1
        else:
           return 
           False 
   L=eval(input("Enter the list of numbers"))               
   n=int(input("Enter the list of numbers"))
   L.sort()
   if bsearch(L,n):
        print("Letter found")
   else:
        print("Letter not found")    
```
>### *__Purpose of binary search__*  
* Binary search is an efficient algorithm for finding an item from a sorted list of items.  
* It works by repeatedly dividing in half the portion of the list that could contain the item.

>## *__Example of Binary Search__*
![Games](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0yb5t6H_LXLd1In4NjY_aVMNKU9Rzg1A--w&usqp=CAU)

>### __Usage__

* [x] Eases the tasks in Python
* [x] Used In #C programming language
* [x] better than linear search in every aspect

>##### Logon to the following website to know more-
__[Cognizance2020](https://cognizance2020.github.io/post/markdown/)__

---
# __*Thank You*__
=======
# Task-4
>>>>>>> b1
