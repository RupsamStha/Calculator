num1 = float(input('Enter first number:'))
num2 = float(input('Enter second number:'))


print('Select operation:')
print('1. Addition')
print('2. Substraction')
print('3. multiplication')
print('4. Division')

Operation = int(input('Select operation(1, 2, 3, 4):'))

if Operation == 1:
    sum = num1 + num2
    print(num1, '+', num2, '=', sum)
elif Operation == 2:
    Substraction = num1 - num2
    print(num1, '-', num2, '=', Substraction)
elif Operation == 3:
    Multiplication = num1 * num2
    print(num1, '*', num2, '=', Multiplication)
elif Operation == 4:
    if num2 == 0:
        print('Divisor cannot be zero(0)!')
    else:
        Division = num1 / num2
        print(num1, '/', num2, '=', Division)
else:
    print('Invalid Operation! Try Again.')
