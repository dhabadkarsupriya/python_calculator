    # python_calculator
    python calculator program!

     # This function adds two numbers
    def add(x, y):
    return x + y

    # This function subtracts two numbers
    def subtract(x, y):
    return x - y

    # This function multiplies two numbers
    def multiply(x, y):
    return x * y

    # This function divides two numbers
    def divide(x, y):
    return x / y
    
    print("select operation:")
    print("1.Add")
    print("2.Subtract")
    print("3.Multiply")
    print("4.Divide")

    while true:
    # Take input from the user
    choice = input("Enter choice(1/2/3/4): ")
    if choice in('1','2','3','4'):

    num1 = float(input("enter num1:"))
    num2 = float(input("enter num2:"))

        if choice == "1"
            print(num1, "+", num2, "=", add(num1, num2))

        elif choice == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))

        elif choice == '3':
            print(num1, "*", num2, "=", multiply(num1, num2))

        elif choice == '4':
            print(num1, "/", num2, "=", divide(num1, num2))
        break
    else:
        print("Invalid Input")

