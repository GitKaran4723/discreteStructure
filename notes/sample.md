# Fundamentals of Set Theory

## 1. Definition of a Set

A **set** is a well-defined collection of distinct objects, considered as an object in its own right. The objects in a set are called the **elements** or **members** of the set. A set is usually denoted by a capital letter, and its elements are listed within curly braces `{}`.

### Notations for a Set

- **Curly Braces `{}`**: The elements of a set are enclosed within curly braces. For example, the set of natural numbers less than 5 is written as $\\{1, 2, 3, 4\\}$.
- **Element Symbol `∈`**: If an object is an element of a set, we use the symbol `∈`. For example, $2 ∈ \\{1, 2, 3\\}$ means 2 is an element of the set $\\{1, 2, 3\\}$.
- **Not an Element Symbol `∉`**: If an object is not an element of a set, we use the symbol `∉`. For example, $4 ∉ \\{1, 2, 3\\}$ means 4 is not an element of the set $\\{1, 2, 3\\}$.

### Examples of Sets:
- The set of natural numbers: $\mathbb{N} = \\{1, 2, 3, 4, \dots\\}$
- The set of vowels in the English alphabet: $V = \\{a, e, i, o, u\\}$
- The set of solutions to the equation $x^2 - 4 = 0$: $S = \\{-2, 2\\}$

## 2. Types of Representations of a Set

### 2.1 Roster or Tabular Form
In the **roster form** (also called the **tabular form**), all the elements of the set are listed, separated by commas, and enclosed within curly braces.

#### Examples:
- The set of even numbers less than 10: $E = \\{2, 4, 6, 8\\}$
- The set of prime numbers less than 10: $P = \\{2, 3, 5, 7\\}$

### 2.2 Set-Builder Form
In the **set-builder form**, a set is defined by a property that its members must satisfy, rather than by listing the elements.

#### Examples:
- The set of all $x$ such that $x$ is a positive even number less than 10: $E = \\{x \mid x \text{ is an even number and } 0 < x < 10\\}$
- The set of all $x$ such that $x$ is a prime number less than 10: $P = \\{x \mid x \text{ is a prime number and } x < 10\\}$

## 3. Solving Examples with Set-Builder Form

### Example 1: Set of Solutions to a Quadratic Equation
Consider the quadratic equation $x^2 - 5x + 6 = 0$. We can solve this equation to find its roots.

**Step 1: Solve the Quadratic Equation**
$$
x^2 - 5x + 6 = 0
$$

This can be factored as:
$$
(x - 2)(x - 3) = 0
$$

So, the solutions are $x = 2$ and $x = 3$.

### Explanation:

To solve the quadratic equation, we first attempt to factor it. We look for two numbers that multiply to give the constant term $\(6\)$ (the last term in the equation) and add up to give \(-5\) (the coefficient of the middle term).

The factors of $\(6\)$ are $\(1 \times 6\)$ and $\(2 \times 3\)$. We need the factors to sum to $\(-5\)$, so we choose $\(-2\)$ and $\(-3\)$ since:
- $(-2) + (-3) = -5$
- $(-2) \times (-3) = 6$

Thus, we can write the equation as:
$$
x^2 - 5x + 6 = x^2 - 2x - 3x + 6
$$

$$
x ( x - 2 ) - 3 ( x - 2 ) = (x - 2)(x - 3) = 0
$$


Now, we solve for $\(x\)$ by setting each factor equal to zero:
$$
x - 2 = 0 \quad \text{or} \quad x - 3 = 0
$$

This gives us the solutions:
$$
x = 2 \quad \text{and} \quad x = 3
$$

### Verification (Optional):

To verify the solutions, substitute $\(x = 2\)$ and \(x = 3\) back into the original equation:

For $\(x = 2\)$:
$$
2^2 - 5(2) + 6 = 4 - 10 + 6 = 0
$$

For $\(x = 3\)$:
$$
3^2 - 5(3) + 6 = 9 - 15 + 6 = 0
$$

Both values satisfy the original equation, confirming that the solutions are correct.


**Step 2: Represent the Solution Set in Roster and Set-Builder Forms**

- **Roster Form:** $S = \\{2, 3\\}$
- **Set-Builder Form:** $S = \\{x \mid x^2 - 5x + 6 = 0\\}$

### Example 2: Set of Real Numbers Satisfying a Quadratic Inequality
Consider the inequality $x^2 - 4x - 5 \leq 0$.

**Step 1: Solve the Quadratic Inequality**
$$
x^2 - 4x - 5 = (x - 5)(x + 1)
$$
This inequality can be solved by finding the intervals where the product is non-positive.

The solutions are $x \in [-1, 5]$.

**Step 2: Represent the Solution Set in Roster and Set-Builder Forms**

- **Roster Form:** Since it's a continuous interval, we do not use roster form here.
- **Set-Builder Form:** $S = \\{x \mid -1 \leq x \leq 5\\}$


### Summary
This covers the basics of set definitions, notations, different representations of sets, and examples involving quadratic equations using set-builder notation. Set theory is fundamental in various areas of mathematics and understanding these basics will help in solving more complex problems.
