# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N** and calculates their sum.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.
6. To find the sum, print `sum(l)`.
7. Terminate the program.

---

### PROGRAM

```python
def createlist(n):
    even_list = [i for i in range(2, n) if i % 2 == 0]
    print("List =", even_list)
    print("Sum of the list = ", sum(even_list))
```

### OUTPUT

<img width="937" height="253" alt="image" src="https://github.com/user-attachments/assets/3e4f711c-2c28-49fa-b3a9-e8bf70737077" />


### RESULT
Thus, a Python function that accepts a number **N** and creates a list containing all even numbers up to **N** and calculates their sum has been written and executed
