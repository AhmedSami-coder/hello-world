# hello-world
first training project 
"""first training project will be for for To Addition Subtraction, Multiplication, Division"""

first_number = int(input('Enter the first number: '))

operator = input("Enter any of these operator for operation +, -, *, /")

second_number = int(input('Enter the second number: '))

result = 0

if operator == '+':
    result = first_number + second_number
elif operator == '-':
    result = first_number - second_number
elif operator == '*':
    result = first_number * second_number
elif operator == '/':
    result = first_number / second_number
    
elset:
    print('operator is not supported')
    
 print(first_number, operator, second_number,"=" ,result)
