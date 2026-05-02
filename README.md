# PYTHON-CHALLENGE-100-DAYS-
HOW TO IMPLEMENT A SIMPLE CALCULATOR 
# implementing a simple calculator
while True:
    print("Choose the operation you want to perform: ")
    print("Enter 1:Addition")
    print("Enter 2:Subtraction")
    print("Enter 3:Multiplication")
    print("Enter 4:Division")
    print("Enter 5:Square Root")
    print("Enter 6: exit")
    i = int(input("Please enter your choice:"))
    if i == 1:
        a = int(input("Enter a value: "))
        b = int(input("Enter a value: "))
        print(a,'+',b, '=',a+b)
    elif i == 2:
        a = int(input("Enter a value: "))
        b = int(input("Enter a value: "))
        print(a, '-', b, '=', a-b)
    elif i == 3:
        a = int(input("Enter a value: "))
        b = int(input("Enter a value: "))
        print(a, '*', b, '=', a*b)
    elif i == 4:
        a = int(input("Enter a value: "))
        b = int(input("Enter a value: "))
        print(a, '/', b, '=', a/b)
    elif i == 5:
        a = int(input("Enter a value: "))
        print("squareroot of",a,  '=', a**0.5)
    else:
        break
