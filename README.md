#Mathematical Operators of Numbers

n1 = int(input("Enter first number: "))

n2 = int(input("Enter second number: "))

operation = input("Enter mathematical operator('+', '-', '*', '/', '%', '**', '//'): ")

if operation == '+':

    print(n1, '+', n2, '=', n1 + n2)

elif operation == '-':

    print(n1, '-', n2, '=', n1 - n2)

elif operation == '*':

    print(n1, '*', n2, '=', n1 * n2)

elif operation == '/':

    print(n1, '/', n2, '=', n1 / n2)

elif operation == '%':

    print(n1, '%', n2, '=', n1 % n2)

elif operation == '**':

    print(n1, '**', n2, '=', n1 ** n2)

elif operation == '//':

    print(n1, '//', n2, '=', n1 // n2)
