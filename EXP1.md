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









### Output:


Enter a positive value for START: 3
Enter a positive value for END: 10
3
4
5
6
7
8
9
Enter a value for N: b
Enter a valid number.

Enter a positive value for START: 6
Enter a positive value for END: -6
Enter a valid positive number.

Enter a value for N: r
Enter a valid number.

Enter a value for A:7
Enter a value for B:9
B is greater than

Enter a string:software
115 111 102 116 119 97 114 101




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


