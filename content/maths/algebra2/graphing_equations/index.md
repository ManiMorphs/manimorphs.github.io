---
title: "Graphing Equations"
math: true
draft: true
---

# Graphing Equations

## Chapter 13: Linear Equations in Two Variables

### 1. Overview & Objectives

By the end of this lesson, you should be able to:

-   Understand what makes an equation **linear in two variables**.
-   Generate **ordered-pair solutions**—i.e., $(x, y)$—by picking values for one variable and solving for the other.
-   **Plot** these ordered pairs on the Cartesian (rectangular) coordinate plane.
-   Draw a **straight line** that represents all possible solutions to the equation.

---

### 2. What is a Linear Equation in Two Variables?

A linear equation involving $x$ and $y$ is typically written as:

$$
ax + by = c
$$

-   Here, $a$, $b$, and $c$ are constants, and at least one of $a$ or $b$ must be non-zero.
-   Unlike one-variable equations, this form represents **infinitely many solutions**—each can be expressed as an ordered pair $(x, y)$.

---

### 3. Generating Ordered-Pair Solutions

**Method:**

1. Choose a value for $x$, and solve for $y$.
2. Alternatively, choose $y$ and compute $x$.
3. Recording several such pairs provides enough points to graph the equation.

**Example:** For the equation

$$
2x - 5y = 20
$$

-   Let $x = 0$:

    $$
    2(0) - 5y = 20 \implies -5y = 20 \implies y = -4 \quad \Rightarrow \quad (0, -4)
    $$

-   Let $x = 5$:

    $$
    2(5) - 5y = 20 \implies 10 - 5y = 20 \implies -5y = 10 \implies y = -2 \quad \Rightarrow \quad (5, -2)
    $$

-   Let $x = 10$:

    $$
    2(10) - 5y = 20 \implies 20 - 5y = 20 \implies -5y = 0 \implies y = 0 \quad \Rightarrow \quad (10, 0)
    $$

**Table of Solutions:**

| $x$ | $y$ |
| :-: | :-: |
|  0  | –4  |
|  5  | –2  |
| 10  |  0  |

---

### 4. Plotting on the Cartesian Plane

-   Mark each $(x, y)$ as a point on the coordinate grid.
-   Draw a line through the points and extend infinitely in both directions (use arrows).
-   This line visualizes **all solutions** to the linear equation.

_(The image above gives a visual example of this process.)_

---

### 5. Example in Action

Let's graph:

$$
3x + 2y = 12
$$

Generate three points:

1. Let $x = 0$:

    $$
    2y = 12 \implies y = 6 \quad \Rightarrow \quad (0, 6)
    $$

2. Let $x = 4$:

    $$
    12 + 2y = 12 \implies 2y = 0 \implies y = 0 \quad \Rightarrow \quad (4, 0)
    $$

3. Let $y = 3$:

    $$
    3x + 6 = 12 \implies 3x = 6 \implies x = 2 \quad \Rightarrow \quad (2, 3)
    $$

Plotting these three points and drawing a straight line gives a clear representation of all possible solutions.

---

### 6. Jupyter (Python) Script to Plot

Here’s a Python snippet you can run in a Jupyter notebook to plot the equation—**perfect for generating an image for your notes**.

```python
import numpy as np
import matplotlib.pyplot as plt

## Define coefficients for the equation: ax + by = c
a, b, c = 3, 2, 12

## Generate x-values
x = np.linspace(-2, 6, 100)
## Compute y-values based on the linear equation
y = (c - a * x) / b

## Plot the line
plt.figure(figsize=(6, 6))
plt.plot(x, y, label=f'{a}x + {b}y = {c}')
plt.scatter([0, 4, 2], [6, 0, 3], color='red')  ## example points
plt.text(0, 6, '(0,6)', ha='right', va='bottom')
plt.text(4, 0, '(4,0)', ha='left', va='top')
plt.text(2, 3, '(2,3)', ha='right', va='bottom')

## Add axes and grid
plt.axhline(0, color='black')
plt.axvline(0, color='black')
plt.grid(True, which='both')
plt.xlim(-2, 6)
plt.ylim(-2, 6)

plt.xlabel('x')
plt.ylabel('y')
plt.title('Graph of 3x + 2y = 12')
plt.legend()
plt.show()
```

**How to use it:**

1. Paste into a Jupyter Notebook cell and run.
2. The plot will appear with the line and the three points.
3. Take a screenshot and embed it into your notes—as a visual aid for students.

---

### 7. Quick Reference Table

| Step | Action                                                          |
| ---- | --------------------------------------------------------------- |
| 1    | Write the equation in the form $ax + by = c$                    |
| 2    | Generate at least two (preferably three) ordered pairs          |
| 3    | Plot each $(x, y)$ on the Cartesian plane                       |
| 4    | Draw a straight line through plotted points, extend with arrows |
| 5    | Customize with Jupyter for clean visual output                  |

---

Let me know if you'd like more advanced variations—like plotting using intercept-intercept form, slope-intercept form, or even overlaying multiple lines for systems of equations!
