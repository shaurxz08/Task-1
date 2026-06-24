# Task-1
# Task 1 - Maincrafts Python Internship

# 1. Sum of Two Numbers
print("1. Sum of Two Numbers")
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum =", a + b)

print("\n----------------------")

# 2. Odd or Even Checker
print("2. Odd or Even Checker")
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")

print("\n----------------------")

# 3. Factorial Calculation
print("3. Factorial Calculation")
n = int(input("Enter a number: "))
fact = 1
for i in range(1, n + 1):
    fact *= i
print("Factorial =", fact)

print("\n----------------------")

# 4. Fibonacci Sequence
print("4. Fibonacci Sequence")
n = int(input("Enter number of terms: "))
a, b = 0, 1
for i in range(n):
    print(a, end=" ")
    a, b = b, a + b

print("\n\n----------------------")

# 5. String Reverse
print("5. String Reverse")
text = input("Enter a string: ")
print("Reversed string:", text[::-1])

print("\n----------------------")

# 6. Palindrome Check
print("6. Palindrome Check")
word = input("Enter a word: ")
if word == word[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")

print("\n----------------------")

# 7. Leap Year Check
print("7. Leap Year Check")
year = int(input("Enter year: "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print("Leap Year")
else:
    print("Not Leap Year")

print("\n----------------------")

# 8. Armstrong Number
print("8. Armstrong Number")
num = int(input("Enter number: "))
order = len(str(num))
sum_val = 0
temp = num

while temp > 0:
    digit = temp % 10
    sum_val += digit ** order
    temp //= 10

if num == sum_val:
    print("Armstrong Number")
else:
    print("Not Armstrong Number")
