# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

import collections

n1=input()
n2=input()
n3=input()

de=collections.deque([n1,n2,n3])

de.popleft()

print("The deque after deletion is : ")
print(de)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/2b6c5e63-656f-47d4-975b-aeb9b8ab2054)

### RESULT

Thus, the python program to delete elements at FRONT END of deque using a collection built-in function has been executed and verified successfully.
