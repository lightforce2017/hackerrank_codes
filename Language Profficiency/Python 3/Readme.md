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
- <img src="https://latex.codecogs.com/svg.latex?-1%20\le%20n%20\le%20100 " /> 

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

# Python: Division

**Task**  
The provided code stub reads two integers, ***a*** and ***b***, from STDIN.

Add logic to print two lines. The first line should contain the result of integer division, ***a//b***. The second line should contain the result of float division, ***a/b***.

No rounding or formatting is necessary.

**Example**   
***a=3***   
***b=5***   
- The result of the integer division ***3//5=0***.   
- The result of the float division is ***3/5=0.6***.   
Print:
```
0
0.6
```

**Input Format**

The first line contains the first integer, ***a***.   
The second line contains the second integer, ***b***.

**Output Format**

Print the two lines as described above.

**Sample Input 0**
```
4
3
```

**Sample Output 0**

```
1
1.33333333333
```

## My submission
```python
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a//b)
    print(a/b)
```

---

# Loops

**Task**   
The provided code stub reads and integer, ***n***, from STDIN. For all non-negative integers ***i<n***, print ***i<sup>2</sup>***.

**Example**

The list of non-negative integers that are less than ***n=3*** is ***[0,1,2]***. Print the square of each number on a separate line.
```
0
1
4
```

**Input Format**

The first and only line contains the integer, ***n***.

**Constraints**   
<img src="https://latex.codecogs.com/svg.latex?1%20\le%20n%20\le%2020 " />

**Output Format**

Print ***n*** lines, one corresponding to each ***i***.

**Sample Input 0**
```
5
```

**Sample Output 0**
```
0
1
4
9
16
```

## My submission
```python
if __name__ == '__main__':
    n = int(input())
    for i in range(0, n):
        print(i**2)
```

---

# Print Function

The included code stub will read an integer, ***n***, from STDIN.

Without using any string methods, try to print the following:    
***123...n***

Note that "..." represents the consecutive values in between.

**Example**   
***n=5***
Print the string ***12345***.

**Input Format**

The first line contains an integer ***n***.

**Constraints**   
<img src="https://latex.codecogs.com/svg.latex?1%20\le%20n%20\le%20150 " />

**Output Format**

Print the list of integers from ***1*** through ***n*** as a string, without spaces.

**Sample Input 0**
```
3
```

**Sample Output 0**
```
123
```

## My submission
```python
if __name__ == '__main__':
    n = int(input())
    for i in range(1, n+1):
        print(i, end='')
```

---

