# python_assignment_2


1. Create the below pattern using nested for loop in Python.
```
*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*
```



```
# for upper half
n=int(input("Enter the number: "))
for i in range(n):
    for j in range(i+1):
        print('*',end="")
    print()
# for lowwer half
for i in range(n):
    for j in range(n-i-1):
        print('*',end="")
    print()
    
```


2. Write a Python program to reverse a word after accepting the input from the user.
Input word: ineuron
Output: norueni  

```
word=input("Enter the word")

for char in range(len(word)-1,-1,-1):   # here we take stop argumet -1 so that we go upto first element
    print(word[char], end="")
print("\n")
```
    
    
    
    
