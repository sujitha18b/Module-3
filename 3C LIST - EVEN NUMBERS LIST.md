# Exp.No:3c
## LIST - APPEND NUMBERS IN LIST


### AIM  
To write a Python function that takes a list 'L' as an argument, adds 5 in all the odd values and 10 in all the even values of the list L. Also display the list L.

### ALGORITHM

1.Start

2.Define a function modify_list(L)

3.For each element num in the list L:

4.If num is even (num % 2 == 0), add 10

5.Else (odd), add 5

6.Replace the original value in the list with the new value

7.Display the modified list

8.End

### PROGRAM

 def add(n):     <br />
    l=[]      <br />
    for i in n:    <br />
        if i%2!=0: <br />
            i+=5    <br />
            l.append(i)    <br />
        else:     <br />
            i+=10    <br />
            l.append(i)     <br />
    print(l)    

### OUTPUT

![Screenshot 2025-04-30 105658](https://github.com/user-attachments/assets/cb4fdfe6-c125-494a-8382-647460aa8286)


### RESULT
Thus,the given python program is implemented and executed sucessfully.
