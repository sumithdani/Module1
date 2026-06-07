
##  Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

##  Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

##  Program
```
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))
c = complex(a, b)
print("Complex Number =", c)
print("Real Part =", c.real)
print("Imaginary Part =", c.imag)
```

## Output
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/82ff8d72-51b7-410d-b749-b98056996f2e" />

## Result
Thus, the Python program to create a complex number from two integers and display its real and imaginary parts was executed successfully.
