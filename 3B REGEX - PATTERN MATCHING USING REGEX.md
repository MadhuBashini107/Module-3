# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r" ab{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```python
import re
pattern = r'ab{2,3}'
s = input()

if re.search(pattern, s):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT

<img width="1253" height="213" alt="image" src="https://github.com/user-attachments/assets/73570d9f-132e-4ea1-8de6-f6fe4fa2f180" />

### RESULT
Thus, the Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions has be written and executed
