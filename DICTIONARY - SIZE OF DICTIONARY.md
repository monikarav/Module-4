# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.No 212223060059

#Name-Dineshkumar K

import sys


dic1 = {}

dic2 = {'a': 1, 'b': 2}

dic3 = {'name': 'Alice', 'age': 25, 'city': 'New York'}

print("Size of dic1:", sys.getsizeof(dic1), "bytes")

print("Size of dic2:", sys.getsizeof(dic2), "bytes")

print("Size of dic3:", sys.getsizeof(dic3), "bytes")
```




### OUTPUT

![image](https://github.com/user-attachments/assets/a220e56b-588f-4cc9-9447-8231e25640bd)

### RESULT
Thus, the python program to print the size of a dictionary using getsizeof() from the sys module has been executed and verified successfully.
