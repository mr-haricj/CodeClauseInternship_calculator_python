print("Select a operation to be perform")
print("1.ADD")
print("2.SUBTRACT")
print("3.DIVIDE")
print("4.MULTIPLY")
while True:
    operation=input("Enter the operation to be performed:")
    if operation=="1":
        n1=input("Enter the first number:")
        n2=input("Enter the second number:")
        print("The sum of two numbers:"+ str(int(n1)+int(n2)))
    elif operation=="2":
        n1 = input("Enter the first number:") 
        n2 = input("Enter the second number:")
        print("The difference of two numbers:" + str(int(n1) - int(n2)))
    elif operation=="3":
        n1 = input("Enter the first number:")
        n2 = input("Enter the second number:")
        print("The division of two numbers:" + str(int(n1) / int(n2)))
    elif operation=="4":
        n1 = input("Enter the first number:")
        n2 = input("Enter the second number:")
        print("The multiplication of two numbers:" + str(int(n1) * int(n2)))
    else:
        print("Invalid")
