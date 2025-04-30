# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX


### AIM  
To write a Python program  to check that a string contains only a certain set of characters (in this case a-z, A-Z and 0-9).

### ALGORITHM

1.Start

2.Input the string

3.For each character in the string:

4.Check if the character is not alphanumeric (i.e., not a letter or digit)

5.If any such character is found:

6.Return False (string is invalid)

7.If all characters are alphanumeric:

8.Return True (string is valid)

9.End

### PROGRAM

import re      <br />
n=input()      <br />
a=re.search('^[a-z]+$',n) <br />
if a: <br />
    print("True")    <br />
else:     <br />
    print("False")
    
### OUTPUT

![Screenshot 2025-04-30 105012](https://github.com/user-attachments/assets/061aac71-29ce-457d-81de-1e3fe75640b9)


### RESULT
Thus, the given python program is implemented and executed sucessfully.
