---
title: "Linear Inequalities"
math: true
weight: 3
---

# Linear Inequalities

## Chapter 8: Interval Notation

Interval notation is a concise way to write a set of numbers that represents the solution to an inequality. Unlike equations, inequalities often have a range of solutions instead of a single value.

### Key Concepts

-   **Parentheses ( )**: Used for a **strict inequality** (\\( < or > \\)). This means the boundary number is **not included** in the solution set. It corresponds to an open circle on a number line.
-   **Brackets [ ]**: Used for a **non-strict inequality** (\\( \le or \ge \\)). This means the boundary number **is included** in the solution set. It corresponds to a closed (or filled) circle on a number line.
-   **Infinity (\\( \infty \\)) and Negative Infinity (\\( -\infty \\))**: Always use a **parenthesis** with infinity, as it is a concept of a value without a bound, not a number you can "include."

---

### Examples

Here's how to convert inequality notation to interval notation and a number line graph.

#### Example 1: \\( x > 3 \\)

Interval Notation: \\( (3, \infty) \\)

```text
    <------------------------------------------------
    -5 -4 -3 -2 -1  0  1  2  3  4  5  6  7  8  9 10
                             (---------------------
```

#### Example 2: \\( x \le -2 \\)

Interval Notation: \\( (-\infty, -2] \\)

```text
------------------------------------------------>
    -5 -4 -3 -2 -1  0  1  2  3  4  5  6  7  8  9 10
    ----------]
```

#### Example 3: \\( -1 < x \le 4 \\)

Interval Notation: \\( (-1, 4] \\)

```text
<------------------------------------------------>
    -5 -4 -3 -2 -1  0  1  2  3  4  5  6  7  8  9 10
                 (--------------]
```

## Chapter 9: Linear Inequalities in One Variable

Solving a **linear inequality** in one variable is very similar to solving a linear equation, with one crucial difference: you may need to reverse the inequality sign.

### Key Properties

-   **Addition Property of Inequality:** Adding or subtracting the same number from both sides of an inequality **does not change** the solution.

    -   Example: If \\( x - 2 > 5 \\), then \\( x - 2 + 2 > 5 + 2 \\) which simplifies to \\( x > 7 \\).

-   **Multiplication Property of Inequality:**

    -   Multiplying or dividing both sides by a **positive number** **does not change** the solution.
        -   Example: If \\( 2x < 6 \\), then \\( \frac{2x}{2} < \frac{6}{2} \\) which simplifies to \\( x < 3 \\).
    -   Multiplying or dividing both sides by a **negative number** **reverses** the direction of the inequality symbol.
        -   Example: If \\( -3x \ge 9 \\), then \\( \frac{-3x}{-3} \le \frac{9}{-3} \\) which simplifies to \\( x \le -3 \\).

### How to Solve Linear Inequalities

Here is a simple, step-by-step process for solving linear inequalities.

1.  **Simplify** each side of the inequality separately (distribute, combine like terms).
2.  **Isolate the variable term** by using the Addition Property of Inequality.
3.  **Isolate the variable** by using the Multiplication Property of Inequality. Remember to **reverse the inequality symbol** if you multiply or divide by a negative number.

#### Example

Let's solve the inequality \\( 3(x - 4) + 1 \ge 10 \\).

1.  **Simplify:**

    \\[
    \begin{align*}
    3x - 12 + 1 \\ge 10 \\\\
    3x - 11 \\ge 10
    \end{align*}
    \\]

2.  **Isolate the variable term:**

    \\[
    \begin{gather*}
    3x - 11 + 11 \\ge 10 + 11 \\\\
    3x \\ge 21
    \end{gather*}
    \\]

3.  **Isolate the variable:**

    \\[
    \begin{gather*}
    \frac{3x}{3} \ge \frac{21}{3} \\\\
    x \ge 7
    \end{gather*}
    \\]

**The solution is \\( x \ge 7 \\).**

---

### Three-Part Linear Inequalities

Some inequalities have two inequality signs, like \\( -4 < 2x - 6 < 8 \\). To solve these, you need to apply the same operations to **all three parts** of the inequality.

#### Example

Let's solve the inequality \\( -4 < 2x - 6 < 8 \\).

1.  **Isolate the variable term** in the middle by adding 6 to all three parts.

    \\[
    \begin{gather*}
    -4 + 6 \< 2x - 6 + 6 \< 8 + 6 \\\\
    2 \< 2x \< 14
    \end{gather*}
    \\]

2.  **Isolate the variable** by dividing all three parts by 2.

    \\[
    \begin{gather*}
    \frac{2}{2} \< \frac{2x}{2} \< \frac{14}{2} \\\\
    1 \< x \< 7
    \end{gather*}
    \\]

**The solution is \\( 1 < x < 7 \\).**

---

### Representing the Solution

The solution to a linear inequality can be represented in three ways:

-   **Inequality Notation:** \\( x \ge 7 \\)
-   **Interval Notation:** \\( [7, \infty) \\)
-   **Number Line Graph:**

<!-- end list -->

```text
    <------------------------------------------------>
    -1  0  1  2  3  4  5  6  7  8  9 10 11
                             [-------------------------
```

## Chapter 10: Compound Inequalities

A **compound inequality** is a statement that joins two inequalities with the word **"and"** or **"or"**. Solving them involves finding a solution that satisfies one or both of the connected conditions.

### "And" Compound Inequalities

A compound inequality with **"and"** is true only if **both** inequalities are true. The solution set is the **intersection** of the individual solution sets. This means you look for the values that are common to both solutions.

#### Example 1

Solve for \\(x\\): \\(x > 5\\) and \\(x \le 9\\).

**Solution:**
The first inequality, \\(x > 5\\), has a solution set of all numbers greater than 5, represented as \\((5, \infty)\\). The second inequality, \\(x \le 9\\), has a solution set of all numbers less than or equal to 9, represented as \\((-\infty, 9]\\).

The intersection of these two sets, \\((5, \infty) \cap (-\infty, 9]\\), is the set of all numbers between 5 and 9, including 9.

-   **Inequality Notation:** \\(5 < x \le 9\\)
-   **Interval Notation:** \\((5, 9]\\)
-   **Number Line Graph:**

<!-- end list -->

```text
    <------------------------------------------->
    -2 -1  0  1  2  3  4  5  6  7  8  9 10 11 12
                          (-----------]
```

#### Example 2 (No Solution)

Solve for \\(x\\): \\(x > 2\\) and \\(x < -1\\).

**Solution:**
There is no number that is both greater than 2 and less than -1. The two individual solution sets, \\((2, \infty)\\) and \\((-\infty, -1)\\), have no numbers in common. Therefore, there is **no solution**.

---

### "Or" Compound Inequalities

A compound inequality with **"or"** is true if at least **one** of the inequalities is true. The solution set is the **union** of the individual solution sets. This means you combine all the values from both solutions.

#### Example

Solve for \\(x\\): \\(x \le -3\\) or \\(x > 2\\).

**Solution:**
The first inequality, \\(x \le -3\\), includes all numbers less than or equal to -3, represented as \\((-\infty, -3]\\). The second inequality, \\(x > 2\\), includes all numbers greater than 2, represented as \\((2, \infty)\\).

The union of these two sets, \\((-\infty, -3] \cup (2, \infty))\\), includes all numbers from both ranges.

-   **Inequality Notation:** \\(x \le -3\\) or \\(x > 2\\)
-   **Interval Notation:** \\( (-\infty, -3] \cup (2, \infty) \\)
-   **Number Line Graph:**

<!-- end list -->

```text
    <------------------------------->
    -5 -4 -3 -2 -1  0  1  2  3  4  5
    -------]              (----------
```
