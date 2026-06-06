# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

x = complex(a, b)

print("Complex Number:", x)
print("Real Part:", x.real)
print("Imaginary Part:", x.imag)
```

## Output
<img width="243" height="137" alt="image" src="https://github.com/user-attachments/assets/f479d943-4e55-4e40-9c63-8258fc291eba" />

## Result
Thus, the Python program to create a complex number and display its real and imaginary parts was executed successfully and the output was verified.
