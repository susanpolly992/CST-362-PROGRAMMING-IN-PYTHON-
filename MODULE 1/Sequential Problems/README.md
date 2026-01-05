1.Read a number and print it

n = int(input("Enter a number: "))
print("Number:", n)

output:
Enter a number: 5
Number: 5

2.Add any 2 numbers and print the sum

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum =", a + b)

output:
Enter first number: 10
Enter second number: 30
Sum = 40

3. Read any 2 numbers and find sum, difference, product, quotient, remainder
   
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum =", a + b)
print("Difference =", a - b)
print("Product =", a * b)
print("Quotient =", a / b)
print("Remainder =", a % b)

output:
Enter first number: 5
Enter second number: 2
Sum = 7
Difference = 3
Product = 10
Quotient = 2.5
Remainder = 1

5. Read any three numbers and find sum and average

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

s = a + b + c
avg = s / 3

print("Sum =", s)
print("Average =", avg)

output:
Enter first number: 5
Enter second number: 10
Enter third number: 15
Sum: 30
Average: 10.0

5. Find the area of a circle

r = float(input("Enter radius: "))
area = 3.14 * r * r
print("Area of circle =", area)

output:
Enter radius: 7
Area of circle: 153.86

6. Area and perimeter of a triangle
import math

a = float(input())
b = float(input())
c = float(input())

p = a + b + c
s = p / 2
area = math.sqrt(s*(s-a)*(s-b)*(s-c))

print("Perimeter =", p)
print("Area =", area)

output:
Enter side a: 3
Enter side b: 4
Enter side c: 5
Perimeter: 12.0
Area: 6.0

7. Convert seconds into hours, minutes and seconds

sec = int(input("Enter seconds: "))

h = sec // 3600
m = (sec % 3600) // 60
s = sec % 60

print(h, ":", m, ":", s)

output:
Enter seconds: 3665
Hours: 1
Minutes: 1
Seconds: 5

8. Swap two numbers using a temporary variable

a = int(input())
b = int(input())

temp = a
a = b
b = temp

print("a =", a)
print("b =", b)

output:
Enter first number: 5
Enter second number: 10
After swapping
a: 10
b: 5

9. Swap two numbers without using a temporary variable
   
a = int(input())
b = int(input())

a, b = b, a

print("a =", a)
print("b =", b)

output:
Enter first number: 3
Enter second number: 8
After swapping
a: 8
b: 3

10. Convert temperature from Celsius to Fahrenheit
    
c = float(input("Enter Celsius: "))
f = (9/5)*c + 32
print("Fahrenheit =", f)

output:
Enter temperature in Celsius: 0
Temperature in Fahrenheit: 32.0

12. Calculate Simple Interest

p = float(input("Enter principal: "))
r = float(input("Enter rate: "))
t = float(input("Enter time: "))

si = (p * r * t) / 100
print("Simple Interest =", si)

output:
Enter principal: 1000
Enter rate of interest: 5
Enter time: 2
Simple Interest: 100.0

