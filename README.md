# Assignment1
## Task 1: Perform Basic Mathematical Operations
<ins>Problem Statement</ins>: Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
   - Addition
   - Subtraction
   - Multiplication
   - Division
3.  Displays the results of each operation on the screen.

### Python Code:
```
# Input the Numbers
a= input('Enter the first number: ')
b= input('Enter the second number: ')
a= float(a)
b= float(b)

# Addition
print('Addition : ', a+b)
# Subtraction
print('Subtraction : ', a-b)
# Multiplication
print('Multiplication: ', a*b)
# Division
print('Division: ', a/b)
```
### Output:
```
Enter the first number: 25
Enter the second number: 5
Addition :  30.0
Subtraction :  20.0
Multiplication:  125.0
Division:  5.0
```


## Task 2: Create a Personalized Greeting
<ins>Problem Statement</ins>: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

### Python Code:
```
# Personalise greeting
name= input('Enter your first name: ')
surname= input('Enter your last name: ')
print('Hello, ' + name + ' '+ surname +'!' + ' Welcome to the python program.')
```

### Output:
```
Enter your first name: James
Enter your last name: Bond
Hello, James Bond! Welcome to the python program.
```


