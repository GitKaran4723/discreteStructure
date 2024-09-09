# Relations

*Definition* :
For sets $A$ and $B$ any subset of $A \times B$ is called a (binary) relation from $A$ to $B$

## Domain and Range of relations
*Definition* :
Let $A$ and $B$ be any two non - empty sets and $R$ be a relation from $A$ to $B$ i.e. $R \subseteq A \times B$, if $(a, b) \in R$ 
 - **Domain of R** is defined as the collection of all the first elements of the ordered pair $(a, b) \in R$
$$
\text{Domain of R} = \\{a \in A | (a, b) \in R\\}
$$
 - **Range of R** is defined as the collection of all second elements of the ordered pair $(a, b) \in R$
$$
\text{Range of R} = \\{b \in B | (a, b) \in R\\}
$$

### Example
Let $A = \\{1, 2, 3, 4\\}$, Relation on A is defined as $(x ,y) \in R$ if $x \lt y$. Write the relation $R$ and the *Domain and Range of R*

**Solution**:
Given: $A = \\{1, 2, 3, 4\\}$ and relation $R$ where $(x, y) \in R$ if $x < y$.

**Relation $R$:**
$$
R = \\{ (1, 2), (1, 3), (1, 4), (2, 3), (2, 4), (3, 4) \\}
$$

**Domain:**
$$
\\{ 1, 2, 3 \\}
$$

**Range:**
$$
\\{ 2, 3, 4 \\}
$$

## Complement of a Relation

Consider a relation $R$ from set $A$ to set $B$. The complement of relation $R$, denoted as $\bar{R}$,  is defined as:

$$
\bar{R} = \{ (a, b) | (a, b) \notin R \}
$$
That is, $\bar{R}$ includes all ordered pairs from $A \times B$ that do not belong to $R$. Formally:

$$
\bar{R} = (A \times B) \setminus R
$$

### Example:

Let $A = \\{ 1, 2, 3 \\}$, $B = \\{ 8, 9 \\}$, and $R = \\{ (1, 8), (1, 9), (3, 9) \\}$.

Now, $A \times B$ is the set of all ordered pairs between $A$ and $B$:
$$
A \times B = \\{ (1, 8), (1, 9), (2, 8), (2, 9), (3, 8), (3, 9) \\}
$$

The complement $\bar{R}$ is the set of pairs in $A \times B$ that are **not** in $r$. Since $R = \\{ (1, 8), (1, 9), (3, 9) \\}$, we remove these pairs from $A \times B$.

Thus, $\bar{R}$ is:
$$
\bar{R} = \\{ (2, 8), (2, 9), (3, 8) \\}
$$




Here is the corrected version of your problem regarding the different ways to represent a relation:

### Representation of a Relation
There are mainly 6 ways of representing a relation:

1. **By Language (Description)**
2. **By Ordered Pairs**
3. **By Arrow Diagram**
4. **By Matrix Form**
5. **By Coordinate Form**
6. **By Graph Form**

### Example:
Consider a set $A = \\{1, 2, 3\\}$ and let $R$ be a relation on $A$ such that the first element is greater than the second element. Let’s represent this relation $R$ in different forms.

---

### 1. **By Language (Description)**:
The relation $R$ can be described as:
$$
R = \\{ (a, b) \mid a > b \text{ and } a, b \in A \\}
$$
This means that for each pair $(a, b)$, $a$ is greater than $b$.

---

### 2. **By Ordered Pairs**:
The relation $R$, based on the condition $a > b$, can be represented by the following ordered pairs:
$$
R = \\{ (2, 1), (3, 1), (3, 2) \\}
$$

---

### 3. **By Arrow Diagram**:
In this representation, we draw arrows from each element of set $A$ to another element if the relation holds (i.e., if $a > b$):

![Arrow Diagram](https://lh3.googleusercontent.com/d/1TtynjLc43tLc531_pLd41cCcaQvdzPzf)

- Arrows from 2 to 1.
- Arrows from 3 to 1 and 3 to 2.

---

### 4. **By Matrix Form**:
In matrix form, the relation is represented by a binary matrix $M$, where $M[i][j] = 1$ if $a_i > a_j$, and $M[i][j] = 0$ otherwise.

For the set $A = \\{1, 2, 3\\}$, the matrix is:

![Matrix Representation](https://lh3.googleusercontent.com/d/1ok0kAd0MR6cA1Okt2wCWJLg-9Z5tVvzx)

- Row represents the first element.
- Column represents the second element.

---

### 5. **By Coordinate Form**:
We plot the relation as points on the coordinate plane, where the x-axis represents the first element, and the y-axis represents the second element.

The ordered pairs $(2, 1), (3, 1), (3, 2)$ will be represented as points:

![In cartetian graph](https://lh3.googleusercontent.com/d/1mmpa2Vr0YL6P8Y2c8V-M20pSYFUq9c4z)

---

### 6. **By Graph Form**:
In the graph form, each element of $A$ is represented by a vertex. We draw directed edges between vertices based on the relation:

![by graph representation](https://lh3.googleusercontent.com/d/1j9G-n76RTJh_rdDeB7YlcRbvoOvxmkjk)

- A directed edge from 2 to 1.
- Directed edges from 3 to 1 and 3 to 2.

---