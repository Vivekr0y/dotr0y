# dotr0y
# Basic calculator program in Python Programming Language.
# Functions for our calculator.
def add(num1, num2):
    # Return the result to the user.
    return num1 + num2

def sub(num1, num2):
    # Return the result to the user.
    return num1 - num2

def mul(num1, num2):
    # Return the result to the user.
    return num1 * num2

def div(num1, num2):
    # Return the result to the user.
    return num1 / num2

# Take integer input from user.
num1 = int(input("Enter first number: ")) #input 1
num2 = int(input("Enter second number: ")) #input 2
# Take choice(string) from user
choice = input("Enter your choice: ") #input 3

# Logic for addition, multiplication, division and subtraction.
if(choice == "add"):
    # Print the result.
    print(add(num1, num2))

elif(choice == "sub"):
    # Print the result.
    print(sub(num1, num2))

elif(choice == "mul"):
    # Print the result.
    print(mul(num1, num2))

elif(choice == "div"):
    # Print the result.
    print(div(num1, num2))

