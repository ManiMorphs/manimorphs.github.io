---
title: "Absolute Value Equations"
math: true
weight: 4
---

# Absolute Value Equations

## Chapter 11: Solving Absolute Value Equations

### 1. What is Absolute Value?

-   The **absolute value** of a number tells us its distance from zero on the number line.
-   It is always **non-negative**.
-   Example:

    -   \\( |7| = 7 \\)
    -   \\( |-7| = 7 \\)

**Key property:**

\\[
\begin{cases}
|x| = x, & x \geq 0 \\\\
-x, & x < 0
\end{cases}
\\]

---

### 2. General Strategy for Equations with Absolute Value

To solve equations of the form:

\\[
|ax + b| = c
\\]

1. **Isolate** the absolute value expression.
2. Write two cases:
    - \\( ax + b = c \\)
    - \\( ax + b = -c \\)
3. Solve both equations.
4. **Check solutions**, since absolute value equations sometimes create _extraneous_ ones.

---

### 3. Examples

#### Example 1

Solve:
\\[
|x - 3| = 9
\\]

**Step 1:** Already isolated.

**Step 2:** Cases:
\\[
\begin{cases}
x - 3 = 9 \\\\
x - 3 = -9
\end{cases}
\\]

**Step 3:** Solve:

-   \\( x = 12 \\)
-   \\( x = -6 \\)

**Answer:** \\( x = -6, 12 \\)

---

#### Example 2

Solve:
\\[
2|3x + 1| - 5 = 9
\\]

**Step 1:** Isolate absolute value:
\\[
\begin{align*}
2|3x + 1| = 14 \\\\
\Rightarrow |3x + 1| = 7
\end{align*}
\\]

**Step 2:** Cases:
\\[
\begin{cases}
3x + 1 = 7 \\\\
3x + 1 = -7
\end{cases}
\\]

**Step 3:** Solve:

-   \\( x = 2 \\)
-   \\( x = -\tfrac{8}{3} \\)

**Answer:** \\( x = 2, -\tfrac{8}{3} \\)

---

#### Example 3: Equation with Two Absolute Values

Solve:
\\[
|2x - 5| = |x + 4|
\\]

**Step 1:** Break into two cases:

1. \\( 2x - 5 = x + 4 \quad \Rightarrow \quad x = 9 \\)
2. \\( 2x - 5 = -(x + 4) \quad \Rightarrow \quad 3x = 1 \\)

\\( \quad \Rightarrow \quad x = \tfrac{1}{3} \\)

**Answer:** \\( x = \tfrac{1}{3}, 9 \\)

---

### 4. Special Cases

1. **No Solution**
   If \\( |x| = k \\) where \\( k < 0 \\), no real solutions exist.
    - Example: \\( |x + 2| = -3 \\) → No solution.

---

2. **Exactly One Solution**
   If \\( |x| = 0 \\), then \\( x = 0 \\).
    - Example: \\( |2x - 6| = 0 \quad \Rightarrow \quad x = 3 \\)

---

### 5. Quick Reference Table

| Equation Form                             | Solution Type                      |
| ----------------------------------------- | ---------------------------------- |
| \\( \mid ax+b = c \mid, c > 0 \\)         | Two possible solutions             |
| \\( \mid ax+b \mid = 0 \\)                | Exactly one solution               |
| \\( \mid ax+b \mid = c, c < 0 \\)         | No solution                        |
| \\( \mid expr1 \mid = \mid expr2 \mid \\) | Solve two cases (equal / opposite) |

---

## Chapter 12: Solving Absolute Value Inequalities

### Objectives

-   Solve absolute value inequalities using two main structures:

    -   **“Greater than”** → treated as a **union (“or”)** of solutions.
    -   **“Less than”** → treated as a **conjunction (“and”)**, resembling a three-part inequality.

-   Identify cases with **all real numbers** or **no solutions**.
-   Express solutions in both **interval notation** and **graphical form** using number-line diagrams.

---

### 1. Two Fundamental Forms of Inequalities

#### A) **“Greater Than” Cases: “or” Situation**

For inequalities like:

\\[
|ax + b| > k \quad \text{or} \quad |ax + b| \ge k
\\]

**Approach:**

1. **Isolate** the absolute value term.
2. Set up a compound condition using **“or”**:

    \\[
    ax + b > k \quad \text{or} \quad ax + b < -k
    \\]

3. Solve both parts separately.
4. Express result as a **union** of intervals.

**Example 1:**

Solve \\( |x - 2| > 5 \\).

-   Isolated already.
-   Cases:

    \\[
    \begin{cases}
    x - 2 > 5 \Rightarrow x > 7 \\\\
    x - 2 < -5 \Rightarrow x < -3
    \end{cases}
    \\]

-   **Solution:** \\( x < -3 \quad or \quad x > 7 \\)
-   **Interval notation:** \\( (-\infty, -3) \cup (7, \infty) \\)

---

#### B) **“Less Than” Cases: “and” Situation**

For inequalities like:

\\[
|ax + b| < k \quad \text{or} \quad |ax + b| \le k
\\]

**Approach:**

1. **Isolate** the absolute value.
2. Convert to a **three-part “and” inequality**:

    \\[
    -k < ax + b < k
    \\]

3. Solve jointly to find the overlapping interval.

**Example 2:**

Solve \\( |2x + 3| \le 7 \\).

-   Isolated already.
-   Convert:

    \\[
    -7 \le 2x + 3 \le 7
    \\]

-   Subtract 3:

    \\[
    -10 \le 2x \le 4
    \\]

-   Divide by 2:

    \\[
    -5 \le x \le 2
    \\]

-   **Solution:** \\( x \in [-5, 2] \\)

---

### 2. Special Situations

#### A) **All Real Numbers**

If, after isolating, you end up with something always true for all \(x\), then **every real number** is a solution.

**Example 3:**

Solve \\( |x + 4| \ge -2 \\).

Since \\( |...| ≥ 0 \\) and 0 ≥ –2 is **always true**, every real \(x\) satisfies.

---

#### B) **No Solutions**

If the inequality requires an absolute value to be strictly below a **negative** number, that's impossible—so **no solution**.

**Example 4:**

Solve \\( |3x - 1| < -1 \\).

Impossible, as absolute values are never negative → **No real solution**.

---

### 3. Summary Table

| Inequality Type                                      | Method                                   | Outcome                    |
| ---------------------------------------------------- | ---------------------------------------- | -------------------------- |
| \\( \mid ax + b \mid > k, k ≥ 0 \\)                  | Split into two “or” conditions           | Union of two intervals     |
| \\( \mid ax + b \mid < k, k ≥ 0 \\)                  | Express as \\( -k < ax+b < k \\) ("and") | Single continuous interval |
| \\( \mid ... \mid ≥ \text{negative}\\) → always true | All real numbers                         |
| \\( \mid ... \mid < \text{negative}\\) → impossible  | No solution                              |

---

### 4. Additional Example Pair

#### Example 5

Solve:

\\[
5|x - 1| + 4 > 14
\\]

-   Isolate:  
    \\[
    5|x - 1| > 10 \quad\Rightarrow\quad |x - 1| > 2
    \\]

-   Cases:

    \\[
    \begin{cases}
    x - 1 > 2 \Rightarrow x > 3 \\\\
    x - 1 < -2 \Rightarrow x < -1
    \end{cases}
    \\]

-   **Solution:** \\( x < -1 \quad or \quad x > 3 \\)
-   **Interval:** \\( (-\infty, -1) \cup (3, \infty) \\)

#### Example 6

Solve:

\\[
|4x + 2| < 6
\\]

-   Three-part form:

    \\[
    -6 < 4x + 2 < 6
    \\]

-   Subtract 2:

    \\[
    -8 < 4x < 4
    \\]

-   Divide:

    \\[
    -2 < x < 1
    \\]

-   **Solution:** \\( x \in (-2, 1) \\)
