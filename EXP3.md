# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:                                                                            
### REGISTER NUMBER : 
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:

```
num = input("Enter a positive number: ")
if num.isnumeric():  
    z = int(num)
    if z < 2:
        print("Not a Prime Number")  
    elif z == 2:
        print("Prime Number")  
    else:
        flag = 1  
        for i in range(2, z // 2 + 1):
            if z % i == 0:
                flag = 0  
                break
        
        if flag == 1:
            print("Prime Number")
        else:
            print("Not a Prime Number")
else:
    print("Enter a valid positive number")


```








### Output:

![Screenshot 2025-03-27 092624](https://github.com/user-attachments/assets/0d868290-81f4-4034-b87e-77dcf00e0440)




### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
