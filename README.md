Introduction
This project contains a collection of five simple yet educational Python programs that cover core programming concepts such as arithmetic operations, algebraic equations, mathematical graphing, function definition, and GUI application development. These examples are ideal for students and beginners learning Python for academic purposes, practical problem-solving, or project submissions.

Each program is explained briefly with code and expected behavior.

1. Arithmetic and Quadratic Operations
Arithmetic Operations
This program performs basic arithmetic operations like addition and multiplication:

Code
a, b = 10, 5
print("Add:", a + b)
print("Multiply:", a * b)
Explanation:
It simply adds and multiplies two predefined values a and b.

Quadratic Equation Solver
This part solves a quadratic equation using the standard quadratic formula:

Code
import math
a, b, c = 1, -3, 2
d = b**2 - 4*a*c
x1 = (-b + math.sqrt(d)) / (2*a)
x2 = (-b - math.sqrt(d)) / (2*a)
print("Roots:", x1, x2)
Explanation:
The program computes the discriminant and uses it to find the roots of the equation x² - 3x + 2 = 0.

2. Linear Equation Solver
This program solves a simple linear equation of the form ax + b = 0.

Code
a, b = 2, -4
x = -b / a
print("Solution of 2x - 4 = 0 is:", x)
Explanation:
It isolates x to find its value using simple algebra. In this example, the result is x = 2.

3. Graphical Representation of a Mathematical Function
This script uses the matplotlib and numpy libraries to plot a graph of the equation y = x²:

Code
import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(-10, 10, 100)
y = x ** 2

plt.plot(x, y, label='y = x²', color='blue')
plt.title("Graph of y = x²")
plt.xlabel("x")
plt.ylabel("y")
plt.grid(True)
plt.legend()
plt.show()
Explanation:
The graph visualizes a parabola. This helps understand how functions behave visually, which is useful in science and engineering.

4. Function Implementation
This program defines a simple function that greets a user by name.

Code
def greet(name):
    return "Hello " + name

print(greet("Alice"))
Explanation:
This shows how to define and call functions in Python to make reusable and modular code.

5. GUI Application using Tkinter
This is a basic GUI application with a button:

Code
import tkinter as tk

def say_hello():
    print("Hello from Tkinter")

win = tk.Tk()
btn = tk.Button(win, text="Click Me", command=say_hello)
btn.pack()
win.mainloop()
Explanation:
When the user clicks the button, a message is printed to the console. It introduces the concept of event-driven programming and user interfaces.

Conclusion
These five programs showcase:

Mathematical calculations (arithmetic, quadratic, linear equations),

Visualization with graphs using matplotlib,

Function creation for clean code, and

GUI design with Tkinter.

They are beginner-friendly and suitable for classroom assignments or self-study projects. You can build on them to create more complex applications.

