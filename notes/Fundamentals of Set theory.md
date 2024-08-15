# Fundamentals of Set Theory

## 1. Definition of a Set

A **set** is a well-defined collection of distinct objects, considered as an object in its own right. The objects in a set are called the **elements** or **members** of the set. A set is usually denoted by a capital letter, and its elements are listed within curly braces `{}`.

### Notations for a Set

- **Curly Braces `{}`**: The elements of a set are enclosed within curly braces. For example, the set of natural numbers less than 5 is written as $\\{1, 2, 3, 4\\}$.
- **Element Symbol `∈`**: If an object is an element of a set, we use the symbol `∈`. For example, $2 ∈ \\{1, 2, 3\\}$ means 2 is an element of the set $\\{1, 2, 3\\}$.
- **Not an Element Symbol `∉`**: If an object is not an element of a set, we use the symbol `∉`. For example, $4 ∉ \\{1, 2, 3\\}$ means 4 is not an element of the set $\\{1, 2, 3\\}$.

### Examples of Sets:
- The set of natural numbers: $\mathbb{N} = \\{1, 2, 3, 4, \dots\\}$
- The set of vowels in the English alphabet: $V = \\{a, e, i, o, u \\}$
- The set of solutions to the equation $x^2 - 4 = 0$ : $S = \\{-2, 2 \\}$

## 2. Types of Representations of a Set

### 2.1 Roster or Tabular Form
In the **roster form** (also called the **tabular form**), all the elements of the set are listed, separated by commas, and enclosed within curly braces.

#### Examples:
- The set of even numbers less than 10: $E = \\{2, 4, 6, 8\\}$
- The set of prime numbers less than 10: $P = \\{2, 3, 5, 7\\}$

### 2.2 Set-Builder Form
In the **set-builder form**, a set is defined by a property that its members must satisfy, rather than by listing the elements.

#### Examples:
- The set of all $x$ such that $x$ is a positive even number less than 10: $E = \\{x \mid x $ is an even number and  0 < x < 10 $\\}$
- The set of all $x$ such that $x$ is a prime number less than 10: $P = \\{x \mid x $ is a prime number and $ x < 10\\}$

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

To solve the quadratic equation, we first attempt to factor it. We look for two numbers that multiply to give the constant term $\(6\)$ (the last term in the equation) and add up to give $\(-5\)$ (the coefficient of the middle term).

The factors of $\(6\)$ are $\(1 \times 6\)$ and $\(2 \times 3\)$. We need the factors to sum to $\(-5\)$, so we choose $\(-2\)$ and $\(-3\)$ since:
$$
(-2) + (-3) = -5
$$
$$
(-2) \times (-3) = 6
$$

Thus, we can write the equation as:
$$
x^2 - 5x + 6 = 0
$$

$$
\implies x^2 - 2x - 3x + 6 = 0
$$

$$
\implies x ( x - 2 ) - 3 ( x - 2 ) = 0
$$

$$
\implies  ( x - 2 ) ( x - 3 ) = 0
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

To verify the solutions, substitute $\(x = 2\)$ and $\(x = 3\)$ back into the original equation:

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

## 4. Types of Sets
### 4.1 Finite set
A set with a **limited** number of elements
**Example** : $D = \\{1, 2, 3, 4, 5 \\}$ is a finite set with 5 elements.

### 4.2 Infinite set
A set with **unlimited or infinite** elements
**Example** : $E = \\{1, 2, 3, 4, \dots \\}$ is a set of all natural numbers, which is infinte.

### 4.3 Singleton Set
A **singleton set** is a set that contains exactly one element.  
**Example**: $F = \\{ 7 \\}$ is a singleton set, as it contains only one element, 7.

### 4.4 Subsets and Proper Subsets
- **Subset**: A set $A$ is a subset of a set $B$ if every element of $A$ is also an element of $B$. This is denoted as $A \subseteq B$.  
- Definition is denoted as if $x \in B$ $\implies$ $x \in A$
  **Example**: If $A = \\{1, 2\\}$ and $B = \\{1, 2, 3\\}$, then $A \subseteq B$.
  
- **Proper Subset**: A set $A$ is a proper subset of a set $B$ if $A \subseteq B$ and $A \neq B$. This is denoted as $A \subset B$.  
  **Example**: If $A = \\{1, 2\\}$ and $B = \\{1, 2, 3\\}$, then $A \subset B$ is a proper subset of $B$.

### 4.5 Power Set
The **power set** of a set $S$ is the set of all possible subsets of $S$, including the empty set and $S$ itself. It is denoted by $P(S)$.  
**Example**: If $S =\\{a, b \\}$, then the power set $P(S) =\\{\emptyset,\\{a\\}, \\{b\\}, \\{a, b\\}\\}$.

### 4.6 Universal Set
A **universal set** is the set that contains all the objects or elements under consideration, typically denoted by $U$.  
**Example**: If we are considering the set of all natural numbers, then the universal set $U$ would be the set of all natural numbers.

### 4.7 Empty Set (Null Set)
The **empty set** (or null set) is a set that contains no elements. It is denoted by $\emptyset$ or $\\{\\}$.  
**Example**: The set $G = \\{x \mid x > 5$ and $ x < 4\\}$ is an empty set because there is no number that satisfies both conditions.

## 5. Equal Sets
Two sets are said to be **equal** if they contain exactly the same elements.  
**Example**: If $H = \\{1, 2, 3\\}$ and $I = \\{3, 2, 1\\}$, then $H$ and $I$ are equal sets, i.e., $H = I$.

## 6. Equivalent Sets
Two sets are **equivalent** if they have the same number of elements, but not necessarily the same elements.  
**Example**: If $J = \\{a, b, c\\}$ and $K = \\{1, 2, 3\\}$, then $J$ and $K$ are equivalent sets because they both contain three elements.

## 7. Basic Set Symbols
1. **{ }**: **Set Brackets**
   - Used to define a set. For example, `{1, 2, 3}` is a set containing the elements 1, 2, and 3.

2. **∈**: **Element of**
   - Indicates that an object is an element of a set. For example, `2 ∈ {1, 2, 3}` means 2 is an element of the set `{1, 2, 3}`.

3. **∉**: **Not an element of**
   - Indicates that an object is not an element of a set. For example, `4 ∉ {1, 2, 3}` means 4 is not an element of the set `{1, 2, 3}`.

4. **|**: **Such that**
   - Used in set builder notation. For example, `{x | x `>` 0}` means "the set of all x such that x is greater than 0."

5. **∅**: **Empty set**
   - Represents a set with no elements. For example, `∅` or `{}`.

6. **N, Z, Q, R, C**: **Standard sets of numbers**
   - **N**: Natural numbers (1, 2, 3, ...)
   - **Z**: Integers (..., -2, -1, 0, 1, 2, ...)
   - **Q**: Rational numbers (fractions of integers)
   - **R**: Real numbers (all numbers on the number line)
   - **C**: Complex numbers (numbers that have a real part and an imaginary part)

## 8. Operations on Sets
1. **∪**: **Union**
   - The union of two sets is a set containing all elements from both sets. For example, `{1, 2} ∪ {2, 3}` gives `{1, 2, 3}`.

2. **∩**: **Intersection**
   - The intersection of two sets is a set containing only the elements common to both sets. For example, `{1, 2} ∩ {2, 3}` gives `{2}`.

3. **−**: **Difference**
   - The difference of two sets is a set containing elements of the first set that are not in the second set. For example, `{1, 2} − {2, 3}` gives `{1}`.

4. **Δ**: **Symmetric Difference**
   - The symmetric difference of two sets is a set containing elements in either of the sets but not in their intersection. For example, `{1, 2} Δ {2, 3}` gives `{1, 3}`.

5. **×**: **Cartesian Product**
   - The Cartesian product of two sets is the set of all ordered pairs formed by taking an element from the first set and an element from the second set. For example, `{1, 2} × {3, 4}` gives `{(1, 3), (1, 4), (2, 3), (2, 4)}`.

## 9. Set Relations
1. **⊆**: **Subset**
   - A set \\( A \\) is a subset of \\( B \\) if all elements of \\( A \\) are also in \\( B \\). For example, `{1, 2} ⊆ {1, 2, 3}`.

2. **⊂**: **Proper Subset**
   - A set \\( A \\) is a proper subset of \\( B \\) if \\( A \\) is a subset of \\( B \\) and \\( A \\) is not equal to \\( B \\). For example, `{1, 2} ⊂ {1, 2, 3}`.

3. **⊇**: **Superset**
   - A set \\( A \\) is a superset of \\( B \\) if \\( B \\) is a subset of \\( A \\). For example, `{1, 2, 3} ⊇ {1, 2}`.

4. **⊃**: **Proper Superset**
   - A set \\( A \\) is a proper superset of \\( B \\) if \\( A \\) is a superset of \\( B \\) and \\( A \\) is not equal to \\( B \\). For example, `{1, 2, 3} ⊃ {1, 2}`.

## 10. Additional Symbols
1. **|A|**: **Cardinality**
   - Represents the number of elements in a set \\( A \\). For example, if \\( A = {1, 2, 3} \\), then \\( |A| = 3 \\).

2. **℘(A)**: **Power Set**
   - The power set of \\( A \\) is the set of all subsets of \\( A \\). For example, if \\( A = {1, 2} \\), then \\( ℘(A) = {∅, {1}, {2}, {1, 2}} \\).

3. **∀**: **For all**
   - Used to denote that something is true for all elements of a set. For example, \\( ∀x ∈ A \\), P(x) indicates that the property P(x) holds for all elements x in the set A.

4. **∃**: **There exists**
   - Indicates the existence of at least one element in a set for which a property holds. For example, \\( ∃x ∈ A \\), P(x) indicates that there is at least one element x in set A for which the property P(x) is true.

5. **∖**: **Set Minus**
   - Represents the relative complement of one set in another, i.e., the set of elements in one set but not in the other. For example, if \\( A = {1, 2, 3} \\) and \\( B = {2, 3} \\), then \\( A ∖ B = {1} \\).

## 11. Venn Diagram
- A visual representation of the relationships between sets, usually represented by overlapping circles.

These symbols form the foundation of set theory, and they are used extensively in mathematics to describe and analyze collections of objects.

--------------------------
