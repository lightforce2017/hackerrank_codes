## Introduction
- [x] Say "Hello, World!" With Python
- [x] Python If-Else
- [x] Arithmetic Operators
- [x] Python: Division
- [x] Loops
- [x] Print Function

## Basic Data Types
- [x] List Comprehensions
- [ ] Find the Runner-Up Score!
- [ ] Nested Lists
- [ ] Finding the percentage
- [ ] Lists
- [ ] Tuples

## Strings
- [ ] sWAP cASE
- [ ] String Split and Join
- [ ] What's Your Name?
- [ ] Mutations
- [ ] Find a string
- [ ] String Validators
- [ ] Text Alignment
- [ ] Text Wrap
- [ ] Designer Door Mat
- [ ] String Formatting
- [ ] Capitalize!

## Sets
- [ ] Set .add()
- [ ] Set .discard(), .remove() & .pop()
- [ ] Set .union() Operation
- [ ] Set .intersection() Operation
- [ ] Set .difference() Operation
- [ ] Set .symmetric_difference() Operation
- [ ] Set Mutations
- [ ] The Captain's Room
- [ ] Check Subset
- [ ] Check Strict Superset
- [ ] Introduction to Sets




# Say "Hello, World!" With Python

Here is a sample line of code that can be executed in Python:
```
print("Hello, World!")
```
You can just as easily store a string as a variable and then print it to stdout:
```
my_string = "Hello, World!"
print(my_string)
```
The above code will print Hello, World! on your screen. Try it yourself in the editor below!

**Input Format**

You do not need to read any input in this challenge.

**Output Format**

Print `Hello, World!` to stdout.

**Sample Output 0**
```
Hello, World!
```

## My submission
```python
print("Hello, World!")
```

---

# Python If-Else

**Task**  
Given an integer, ***n***, perform the following conditional actions:

- If ***n*** is odd, print `Weird`
- If ***n*** is even and in the inclusive range of **2** to **5**, print `Not Weird`
- If ***n*** is even and in the inclusive range of **6** to **20**, print `Weird`
- If ***n*** is even and greater than **20**, print `Not Weird`

**Input Format**

A single line containing a positive integer, ***n***.

**Constraints**  
- 1 <= n <= 100

![\Large -1 \le n \le 100](https://latex.codecogs.com/svg.latex?-1%20\le%20n%20\le%20100)

**Output Format**

Print `Weird` if the number is weird. Otherwise, print `Not Weird`.

**Sample Input 0**
```
3
```

**Sample Output 0**
```
Weird
```

**Explanation 0**  
***n = 3***   
***n*** is odd and odd numbers are weird, so print `Weird`.

**Sample Input 1**
```
24
```

**Sample Output 1**
```
Not Weird
```

**Explanation 1**

***n = 24***   
***n > 20*** and ***n*** is even, so it is not weird

## My submission
```python
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
    if (n % 2 == 1) or (n % 2 == 0 and 6 <= n <= 20):
        print("Weird")
    elif (n % 2 == 0 and 2 <= n <= 5) or (n % 2 == 0 and n > 20):
        print("Not Weird")
```

---

