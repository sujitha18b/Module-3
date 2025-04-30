# Exp.No:3d  
## TUPLES - REMOVE THE ELEMENTS OF THE TUPLE


### AIM  

To write a python function that  a string, convert it into a tuple and remove the 3rd element of the tuple.


### ALGORITHM

1.Start

2.Input a string from the user

3.Convert the string to a tuple (each character becomes an element)

4.Check if the tuple has at least 3 elements

5.If yes, remove the element at index 2

6.Else, skip removal

7.Return/Display the modified tuple

8.End

### PROGRAM

def strtotuple(a):    <br />
    t=tuple(a)      <br />
    print(t)     <br />
    l=list(t)       <br />
    b=l[2]    <br />
    l.pop(2)   <br />
    t1=tuple(l) <br />
    print(t1) <br />
    print(f"Character Removed: {b}")

### OUTPUT
![Screenshot 2025-04-30 110601](https://github.com/user-attachments/assets/7f9b9a06-e927-44c0-b69d-eb7388becf72)


### RESULT
Thus,the given python program is implemented and executed sucessfully.
