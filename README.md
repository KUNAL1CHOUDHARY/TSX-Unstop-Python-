# TSX-Unstop-Python-
# Variables
length = 10
width = 5

# Calculations
area = length * width
perimeter = 2 * (length + width)

# Output
print("Area:", area)
print("Perimeter:", perimeter)

# Input
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Comparison
if num1 > num2:
    print("First number is greater.")
elif num1 < num2:
    print("First number is smaller.")
else:
    print("Both numbers are equal.")

# Input
year = int(input("Enter a year: "))

# Leap year logic
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")

a = 10
b = 3

# Arithmetic
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Floor Division:", a // b)
print("Modulus:", a % b)
print("Exponent:", a ** b)

# Logical
print("Logical AND:", a > 5 and b < 5)
print("Logical OR:", a < 5 or b < 5)
print("Logical NOT:", not (a < 5))

# Input
str1 = input("Enter first string: ")
str2 = input("Enter second string: ")

# Concatenation
result = str1 + " " + str2
print("Concatenated String:", result)
