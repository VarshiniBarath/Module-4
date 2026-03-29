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

```python
from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3} 
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print("Size of dic1: ",getsizeof(dic1),"bytes",sep="")
print("Size of dic2: ",getsizeof(dic2),"bytes",sep="")
print("Size of dic3: ",getsizeof(dic3),"bytes",sep="")
```

### OUTPUT
<img width="1183" height="238" alt="image" src="https://github.com/user-attachments/assets/3f9afc33-8041-4843-874b-305cb29a3143" />

### RESULT
Therefore, the output is the example to write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.
