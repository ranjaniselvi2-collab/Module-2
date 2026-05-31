### Ex-2:Built-in Functions -Binary Conversion Using Built-in Functions in Python

### Aim:
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

### Algorithm:
1.Assign the value 16 to a variable a.

2.Use the built-in bin() function to convert the number to binary.

3.Print the result.

### Program:
```
num = int(input("Enter a number: "))
print("Binary value is:", bin(num))
```
### Output:

<img width="400" height="118" alt="Screenshot 2026-05-31 103243" src="https://github.com/user-attachments/assets/ca375989-3d27-4fd9-8591-8300d4777c49" />


### Result:
Thus, the Python program for binary conversion using the built-in bin() function was executed successfully, and the binary equivalent of the given number was displayed correctly.

### Ex-2:Functions in Python: Modulo Calculator

### Aim:

To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

### Algorithm:

1.Define a function called result that takes two arguments a and b.

2.Inside the function, compute the modulo using a % b.

3.Print the result of the modulo operation.

4.Get two integer inputs from the user.

5.Call the result function with the user-provided values.

### Program:
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
result = a % b
print("Modulo =", result)
```
### Output:

<img width="445" height="159" alt="image" src="https://github.com/user-attachments/assets/46c39c32-0f47-4c65-a8c4-5b91f35ccc5f" />

### Result:

Thus, the Python program for calculating the modulo (remainder) of two numbers was executed successfully.

### Ex-2:Lambda Function in Python: Addition of Two Numbers

###  Aim:

To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

### Algorithm:

1.Get two integer inputs from the user.

2.Use a lambda function to define a function f that returns a + b.

3.Call the function with the user inputs and print the result.


### Program:
```
add = lambda a, b: a + b
x = int(input("Enter first number: "))
y = int(input("Enter second number: "))
print("Sum =", add(x, y))
```

### Output:

<img width="403" height="140" alt="image" src="https://github.com/user-attachments/assets/8524bf54-c53a-45f8-9d78-6bfe239eeeee" />

### Result:

Thus, the Python program for addition of two numbers using a lambda function was executed successfully.

### Ex-2:Looping(Patterns)-Pascal's Triangle Generator in Python

### Aim:

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

### Algorithm:

1.Start the program.

2.Input the number of rows from the user.

3.Loop from 0 to the number of rows.

4.For each row:
  Print appropriate spaces to shape the triangle.
  Compute values using the formula:
  [ C(n, k) = \frac{n!}{k!(n-k)!} ]
  
5.Print all rows of Pascal’s Triangle.

6.End the program.

### Program:
```
n = int(input("Enter the number of rows: "))

for i in range(n):
    num = 1
    for j in range(n - i - 1):
        print(" ", end="")
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()

```

### output:

<img width="523" height="307" alt="image" src="https://github.com/user-attachments/assets/02524a1b-8280-46ab-b2fd-af1e59704b10" />

### Result:

Thus, the Python program for generating Pascal's Triangle was executed successfully.

### Ex-2:Loops in Python: Palindrome Number Checker

### Aim:

Thus, the Python program for generating Pascal's Triangle was executed successfully.

### Algorithm:
1.Get input from the user and assign it to a variable num.

2.Assign the value of num to a temporary variable temp.

3.Initialize a variable rev to 0 (used to store the reversed number).

4.Use a while loop to reverse the digits:
    While temp > 0:
     rev = (10 * rev) + temp % 10
      temp = temp // 10
5.After the loop, compare rev with num:
      If equal, print that the number is a palindrome.
          Else, print that it is not a palindrome.

### Program:
```



