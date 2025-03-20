# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```

def display():
    start=input("Enter a positive value for START:")
    end = input("Enter a positive value for END:")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end='')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ") 
if start.isnumeric()and end.isnumeric():
    start = int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")

def switch():
    switcher={
        0:"even",
        1:"odd" 
} 
n=input('Enter a value for N: ')
try:
    n=int(n)
    print(switcher[n%2]) 
except ValueError:
    print("Enter a valid number.")
    switch()

def compare():
    a=input("Enter a value for A:")
    b=input("Enter a value for B:")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")
compare()

def iterate():
    string=input("Enter a string:")
    for i in string:
        print(ord(i),end=" ")
iterate()


```






### Output:

![Screenshot 2025-03-20 084204](https://github.com/user-attachments/assets/829f9bc0-6019-4897-9932-63a61915d984)
![Screenshot 2025-03-20 084458](https://github.com/user-attachments/assets/7c032dfe-994b-488f-a3c2-cff540c424bf)
![Screenshot 2025-03-20 084641](https://github.com/user-attachments/assets/aac34abe-79ca-4835-88e0-6453b3f16b09)
![Screenshot 2025-03-20 084846](https://github.com/user-attachments/assets/8bb2a2d8-0d42-46bb-9409-b9dfbef8751d)
![Screenshot 2025-03-20 084959](https://github.com/user-attachments/assets/4bae6579-db51-48ef-bce9-db1d2a8854b6)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


