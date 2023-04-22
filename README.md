# python_calulator
#code to build a calculator in python language
while True:
    print("Enter 'quit' to exit")
    print("Enter an operation: +, -, *, /")

    # take input from the user
    choice = input("Enter choice( + / - / * / / ): ")

    # exit the program if the user enters 'quit'
    if choice == 'quit':
        break

    # take input values
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    # perform the operation based on the user's choice
    if choice == '+':
        result = num1 + num2
    elif choice == '-':
        result = num1 - num2
    elif choice == '*':
        result = num1 * num2
    elif choice == '/':
        result = num1 / num2
    else:
        print("Invalid input")
        continue

    # display the result
    print("Result: ", result)
