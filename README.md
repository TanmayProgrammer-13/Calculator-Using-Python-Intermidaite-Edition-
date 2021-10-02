num1 = input("Enter First Number: ")
num1 = int(num1)

op = input("Enter Your Operator: ")

num2 = input("Enter Second Number: ")
num2 = int(num2)

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "*":
    print(num1 * num2)
elif op == "/":
    print(num1 / num2)
else:
    print("Invalid Operator!")




