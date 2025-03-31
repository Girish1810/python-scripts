Task 1: Perform Basic Mathematical Operations
Problem Statement: Write a Python program that does the following:
1.  Takes two numbers as input from the user.  2).  Performs the basic mathematical operations on these two numbers:

o	Addition  o	Subtraction  o	Multiplication  o	Division

solution

a = int(input("Enter the First number: "))
b = int(input("Enter the secound number: "))

print(a+b)
print(a-b)
print(a*b)
print(a/b)

output:

Enter the First number: 5
Enter the secound number: 10
15
-5
50
0.5


Task 2: Create a Personalized Greeting
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.  2.  Concatenates the first name and last name into a full name. 3.  Prints a personalized greeting message using the full name.

solution:

first_name = str(input("Enter your first name: "))
last_name = str(input("Enter your secound name: "))

full_name = first_name +" "+ last_name

print(f"Hello, {full_name}! Welcome to the python program")

output:
Enter your first name: Viktor
Enter your secound name: Daniel
Hello, Viktor Daniel! Welcome to the python program

