# Counting and Venn Diagrams

## Venn Diagrams

### Following are some examples of venn diagrams
1. $A$ and $\overline{A}$

![Counting Complement](https://lh3.googleusercontent.com/d/1646pXVnaYSExfAV1cSANrnvgOhiwBiI_)

2. $\overline{B}$

![Counting Complement](https://lh3.googleusercontent.com/d/14q6vhd2urtUURf6yni661Fvlia2sDjyW)

3. $A - B$

![Counting Complement](https://lh3.googleusercontent.com/d/1sGgguiKlAlDZHtaGGqvaVRr2UrL1oFQ1)

4. $A \cap \overline{B}$

![Counting Complement](https://lh3.googleusercontent.com/d/1ASzGu2nuPeieWq4dn9v7ZeL4jkNoaiaW)

Following are the Videos for understanding venn diagram
1. [Venn Diagram Basics](https://youtu.be/rgppiKOM_ko?si=x5joVJkFySHhgNn5)
2. [Using venn Diagrams - De Morgan's Laws](https://youtu.be/Ix4H7PWscXY?si=LcKWR9T-KzpMXGRW)

## Counting

For sets $A, B$ from a finite universe $U$ the following venn diagrams will help us in obtaining counting formula for $| \overline{A} |$ and $| A \cap B |$ in temrs of $|U|, |A|, |B|, |A \cap B|$

for example,
$| A | + | \overline{A} |$ = $| U |$

As shown in the following venn diagram

![Counting Complement](https://lh3.googleusercontent.com/d/1-1tMg802c8qXefm_a440zkcGeBjoC9vI)

$\implies | \overline{A} | = | U | - | A |$

to find the number of elements in $ \overline{A} $ we need to subtract $A$ from $U$.

### When A and B are disjoint sets

Consider the following venn diagram for set $A, B$ and $U$

![Disjoint sets](https://lh3.googleusercontent.com/d/1xaBWJCmnQE7x52-W7YTyI4MdKszsXQwl)

In this venn diagram $A$ and $B$ are disjoint thus do not have nay common elements

for example,
$U = \\{1, 2, 3, 4, 5, 6\\}$ , $A = \\{1, 2, 3\\}$ and $B = \\{4, 5, 6\\}$
in this example we have $A \cap B$ = $\emptyset$ or $\\{\\}$

thus we have $|A \cap B| = |A| + |B|$

### When A and B are not Disjoint

Consider the following venn diagram for set $A, B$ and $U$

![Non disjoint sets](https://lh3.googleusercontent.com/d/1b50YR6FWtgRSpGX9VWvGf69YuYPaxvWM)

In the above given case we have $A \cap B \neq \emptyset$
$\implies$  $|A \cap B| \neq 0$

for example,
$U = \\{1, 2, 3, 4, 5, 6\\}$ , $A = \\{1, 2, 3, 4, 5\\}$ and $B = \\{4, 5, 6\\}$
in this example we have $A \cap B$ = $\\{4, 5\\} \not = \emptyset$

Thus we have $| A \cup B |$ = $|A| + |B| - |A \cap B|$

### When there is involvement of 3 sets 

Consider the sets $A$, $B$, $C$ $\subseteq$ $U$ as given in the following venn diagram

![Union of three sets](https://lh3.googleusercontent.com/d/1PJfo6vVKXXpfDv6CsUbHX58Z3MpiaLug)

in such case counting formula of union of 3 sets i.e. $|A \cup B \cup C|$ = $|A|$ + $|B|$ + $|C|$ - $|A \cap B|$ - $|B \cap C|$ - $|A \cap C|$ + $|A \cap B \cap C|$

following are the two sample examples for the given problem

1. In a BCA sem 1 Class, there are 60 students, 30 students like C++, 25 students like Java and 10 students like both, then answer the following questions
   - How many students like atleast one programming language
   - How many likes atmost one programming language
   - How many students like no programming language

2. There are 100 machines 23 of the machines have D1 defect, 26 of them have D2 defect 30 of them have D3 defect, 7 have D1 and D2 defect, 8 having D1 and D3 defects, 10 having D2 and D3 defects and 3 having all the three defects
   - How many machines have atleast one of the defect
   - How many machines have exactly two defects
   - How many machines have exactly one defect  




