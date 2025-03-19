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


def iterate():
    string=input("Enter a string:")
    for i in string:
        print(ord(i),end=" ")
iterate()


```






### Output:

![Screenshot 2025-03-13 033642](https://github.com/user-attachments/assets/b3b3c990-4011-4453-827f-172e50dd58f0)

![Screenshot 2025-03-13 033902](https://github.com/user-attachments/assets/daa1c5fd-3027-4320-b0e2-7ae59d7e2025)

![Screenshot 2025-03-13 034013](https://github.com/user-attachments/assets/d3403418-de9e-4a8a-a4e6-c2b8957fdf9c)

![Screenshot 2025-03-13 034551](https://github.com/user-attachments/assets/05ec3fd6-fac7-46c0-9ca6-df9d1baf67fe)

![Screenshot 2025-03-13 034736](https://github.com/user-attachments/assets/5af3291e-7199-4faf-bc41-e02149f13a17)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


