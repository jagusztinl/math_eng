

## **Topic 1: Sets, Set Operations. Notable Point Sets in the Plane and in Space**

A *set* is one of the most fundamental concepts in mathematics. According to our current understanding, all mathematical knowledge can be fully derived from set theory.

Set theory began developing at the end of the 19th century and took its present form in the 20th century.

We do **not** define the notions of *set* and *element of a set*; they are taken as **primitive concepts**—they may be described in words (like “collection,” “group,” “belongs to”), but not defined. By agreement, we may speak of a set if for any given object it is clearly decidable whether it belongs to the set or not.

Elements of sets are generally denoted with lowercase letters, and sets themselves with uppercase letters:
`a ∈ A` (a is in A), `b ∉ A` (b is not in A).
An element appears **only once** in a set.

Some specific number sets have unique names and are written in boldface:
ℕ (natural numbers), ℤ (integers), ℚ (rationals), ℚ\* (nonzero rationals), ℝ (reals),
ℤ⁺ (positive integers), ℝ⁻ (negative reals), etc.

Sets can be defined either by listing their elements or by describing a property that characterizes the elements, for example:

* `A = {a, b, c, d}`
* `B = {x ∈ ℤ : x ≤ 5}`
* `C = {poems by Attila József}`

**D:** A set with no elements is called the *empty set*. Denoted: `{}` or `∅`.

**D:** Two sets are equal if they contain the exact same elements. Notation: `A = B`.

We introduce two new concepts to describe relationships between sets:

**D:** `A` is a *subset* of `B` if every element of `A` is also in `B`: `A ⊆ B`.
`A` is a *proper subset* of `B` if `A ⊆ B` and `B` has at least one element not in `A`: `A ⊂ B`.

The following theorems hold for subsets:

**T:** `A ⊆ A`
**T:** If `A ⊆ B` and `B ⊆ C`, then `A ⊆ C`.
**T:** If `A ⊆ B` and `B ⊆ A`, then `A = B`.

> This last theorem is frequently used to prove set equality.

We define operations between sets. The most important are:

**D:** The *union* of `A` and `B` is the set of elements belonging to at least one of them:
`A ∪ B = {x : x ∈ A ∨ x ∈ B}`

**D:** The *intersection* of `A` and `B` is the set of elements belonging to both:
`A ∩ B = {x : x ∈ A ∧ x ∈ B}`

**D:** The *difference* `A \ B` is the set of elements in `A` but not in `B`:
`A \ B = {x : x ∈ A ∧ x ∉ B}`

**D:** The *symmetric difference* `A △ B` is the set of elements in either `A` or `B`, but not both:
`A △ B = {x : (x ∈ A ∨ x ∈ B) ∧ x ∉ A ∩ B}`
or
`A △ B = (A \ B) ∪ (B \ A)`

**D:** The *Cartesian product* of `A` and `B` is the set of ordered pairs where the first component is from `A`, the second from `B`:
`A × B = {(a, b) : a ∈ A ∧ b ∈ B}`

---

### Properties of Set Operations

The operations of union and intersection are:

* **Idempotent**
* **Commutative**
* **Associative**
* **Distributive** over one another

This gives:

```
A ∪ A = A        A ∩ A = A  
A ∪ B = B ∪ A    A ∩ B = B ∩ A  
A ∪ (B ∪ C) = (A ∪ B) ∪ C  
A ∩ (B ∩ C) = (A ∩ B) ∩ C  
A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)  
A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)
```

Set identities are frequently proven using **Venn diagrams**.

**Theorem:** For any sets `A`, `B`, and `C`:
`A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)`

**Proof:** See the Venn diagrams on *page 11*.
The equivalence of the diagrams’ shaded regions confirms the identity. //

---

### Complementation

To define complement, we first introduce:

**D:** The *universal set* or *universe* `H` (or `U`) is the set of all objects relevant to a given context.

**D:** The *complement of `A`* relative to `H` is:
`Ā = H \ A`
Also: `(Ā)̄ = A`

**De Morgan’s Laws:**

```
(A ∪ B)̄ = Ā ∩ B̄  
(A ∩ B)̄ = Ā ∪ B̄
```

Any combination of set operations can be rewritten using only unions and complements, or intersections and complements.

---

## **Notable Point Sets (Loci)**

**D:** “Notable point sets” usually refer to sets of points defined by **distance conditions**.

Examples:

* Points in the plane equidistant from a fixed point form a **circle** (center and radius).
* Points equidistant from two given points lie on the **perpendicular bisector** of the segment joining them.
* Points equidistant from two **intersecting lines** lie on the two **angle bisectors**.
* Points equidistant from two **parallel lines** lie on the line midway between them.
* Points equidistant from a **point and a line** define a **parabola**.
* Points for which the sum of distances to two fixed points equals a constant form an **ellipse**.
* Points for which the *difference* of distances to two fixed points equals a constant form a **hyperbola**.

Circles, ellipses, parabolas, and hyperbolas are **conic sections**.

### Spatial Analogues:

* Circle → Sphere
* Perpendicular bisector → Perpendicular bisecting plane
* Angle bisector → Angle bisecting plane
* Parallel lines → Parallel planes
* Parabola → Paraboloid of revolution
* Ellipse → Ellipsoid of revolution
* Hyperbola → Hyperboloid of revolution

Other notable spatial point sets exist too.

---

### Applications

* Sets are used across all fields of mathematics: defining domains, codomains, solution sets, etc.
* In computer science and statistics: for structuring databases, queries (Google, Yahoo), and analyses (censuses, surveys).
* Notable point sets are foundational in geometry for constructions and proofs.
* Applications include astronomy (conics) and computer graphics.

---

**Note:** If the associated task is to prove a theorem, the author recommends proving De Morgan’s Laws instead of the theorem already proven above.

Here is the **full English translation of Topic 2** from the uploaded oral mathematics exam guide, preserving the original structure, logic, mathematical content, and notation faithfully and precisely:

---

## **Topic 2: Rational and Irrational Numbers. Operations on Rational and Irrational Numbers. Common Fractions and Decimal Fractions. Cardinality of Sets.**

In this topic, we only deal with the set of real numbers and its subsets. While maintaining the historically-based structure of secondary school education, I still aim for a rigorous formulation. (For more details, see Supplement 1.)

From now on, we consider **real numbers** only, denoted as:

> **D:** The number line is a line on which two points are marked: one assigned the real number 0, the other the number 1. The distance between them is called the *unit length*.

> **D:** Every point on the number line corresponds to a real number, and every real number corresponds to a point on the number line.
> (That is, there is a one-to-one correspondence between the set of real numbers and the points on the number line.)
> The symbol for the set of real numbers is **ℝ**.

Early humans invented numbers to solve counting problems, such as determining the size (cardinality) of non-empty sets. These were originally called **natural numbers**: 1, 2, 3, …; today, we also include 0. The set of natural numbers is denoted by **ℕ**.

Two operations were defined on them: **union**, which led to **addition**, and **repetition**, which led to **multiplication**.
Both operations are **commutative** and **associative**. Multiplication is **distributive** over addition (but not vice versa), which is why it is considered a stronger operation.

The set of natural numbers is **closed** under addition and multiplication, meaning that performing either operation yields another natural number.

However, their inverse operations are not always defined in ℕ, which necessitated extending the number system:

* **Integers** (ℤ) to allow subtraction (introducing 0 and negative numbers)
* **Rational numbers** (ℚ) to allow division by nonzero integers

These four operations—addition, subtraction, multiplication, division—are referred to as the **basic arithmetic operations**.

> **D:** A number is called **rational** if it can be written as the quotient of two integers.
> The set of rational numbers is denoted by **ℚ**.

> **D:** Numbers that **cannot** be written as the quotient of two integers are called **irrational numbers**.
> Denoted by **ℚ**\* (or ℝ \ ℚ).

If an irrational number is a root of a polynomial with rational coefficients, it is called an **algebraic number** (e.g., √3, ²√5, √7).
If it is not the root of any such polynomial, it is called a **transcendental number** (e.g., **π** and **e**).

Thus:

* ℚ ∩ ℚ\* = ∅
* ℝ = ℚ ∪ ℚ\*

Based on the **axiomatic construction of the real number field**, rational and irrational numbers can also be defined equivalently as follows:

> **T:** Every real number has a **unique decimal expansion**.

> **D:** A real number with a **finite or eventually periodic** decimal expansion is **rational**.

> **D:** A real number with an **infinite, non-repeating** decimal expansion is **irrational**.

> **T:** A rational number has a finite decimal expansion **if and only if** its reduced form has a denominator whose prime factorization contains only the primes 2 and/or 5.
> (Note: Analogous statements hold for bases other than 10.)

---

### **Operations on Rational and Irrational Numbers**

In both sets, addition and multiplication are **commutative** and **associative**. Multiplication (and division) is distributive over addition and subtraction.

**Key properties of ℚ:**

1. ℚ is **not bounded** above or below.
2. ℚ is **closed** under the four basic operations.
3. ℚ is **dense**: between any two rational numbers lies another rational number.
   → Hence, there are **infinitely many** rational numbers between any two.

**Key properties of ℚ**\*:

1. ℚ\* is **not bounded** above or below.
2. ℚ\* is **not closed** under the four basic operations.
3. ℚ\* is **dense**: between any two irrational numbers lies another irrational number.
   → Thus, **infinitely many** irrationals lie between any two.

**Relations between ℚ and ℚ**\*:

1. Between any two rational numbers lies an irrational number.
2. Between any two irrational numbers lies a rational number.
3. The result of a basic operation between a rational and an irrational number is **irrational** (except for multiplication or division by 0).

---

### **Fractions**

In everyday use, three types of representations are used for real numbers:

* **Common fractions**
* **Mixed numbers**
* **Decimal fractions**

For example, a rational number:
$\frac{22}{7} = 3\frac{1}{7} = 3.142857...$
(This is Archimedes’ approximation of π, better than 3.14.)

To denote repeating decimals, we place a dot over the first and last digits of the repeating section.
(The repeating section is at most one digit shorter than the denominator.)

⚠️ Avoid **mixed numbers** in algebra:
e.g.,
Is $1\frac{2}{7} = \frac{9}{7}$ or $1 \cdot \frac{2}{7} = \frac{2}{7}$?
Context is key.

Examples:

1. In $x = 1\frac{2}{7}$, mixed fraction is appropriate.
2. In a solution: $x = 2 + \frac{1}{7} = \frac{15}{7}$, avoid ambiguity.

---

### **Cardinality of Sets**

A set can be **finite** or **infinite**.

> **D:** The **cardinality** of a finite set `A` is the number of its elements: |A|.
> The empty set has cardinality 0.

To define cardinality for infinite sets, we use **functions**:

> **D:** Sets A and B have the **same cardinality** (denoted A ≅ B) if there is a **bijective function** f: A → B.

> **T:** Let A, B, C be arbitrary sets. Then:

1. A ≅ A
2. If A ≅ B, then B ≅ A
3. If A ≅ B and B ≅ C, then A ≅ C

Using equivalence, we define:

> **D:** A set A is **infinite** if there exists B ⊂ A such that A ≅ B.
> A set is **finite** if it is not infinite.

For example:

* The sets {1, 2, ..., n} ≅ ℕ
* The cardinality of ℕ is called **countably infinite**, denoted ℵ₀ (aleph-null).

> **T:** ℕ⁺ ≅ ℤ⁺ ≅ ℚ⁺ ≅ ℚ
> (**Proof:** Use **Cantor’s diagonal argument**—see *page 17, image*.)

---

### **Comparing Cardinalities**

> **D:** |A| < |B| if there is a subset B\* ⊂ B with A ≅ B\* but A ≄ B.

> **D:** The **power set** of A is the set of all subsets of A, denoted ℘(A).

> **T:** |℘(A)| > |A|
> **T:** For finite sets, if |A| = n, then |℘(A)| = 2ⁿ
> **T:** For any cardinality, there is a strictly greater one.
> **T:** ℝ is **uncountable**.

> **D:** The cardinality of ℝ is called the **continuum**, denoted **𝔠**.
> **T:**
>
> 1. |ℝ| = 2^ℵ₀
> 2. 𝔠 > ℵ₀
> 3. |\[0,1]| = |ℝⁿ| = 𝔠 for any n ≥ 1

At the **2nd International Congress of Mathematicians** (Paris, 1900), **David Hilbert** listed the most important open problems.
His **first problem** was the **Continuum Hypothesis**:

> "There is no cardinality strictly between ℵ₀ and 𝔠."

In 1940, **Kurt Gödel** proved that the hypothesis **cannot be refuted** within ZFC set theory.
In 1963, **Paul Cohen** showed it **cannot be proven**, either.

Thus, the statement is **independent** of ZFC—consistent with **Gödel’s incompleteness theorem**.

---

### **Applications**

Numbers (especially integers and decimals) and operations are used everywhere—from scientific to everyday contexts.

When using decimal approximations, be aware of rounding errors.
At the secondary school level, four significant digits are sufficient.

---

**Note:**
To denote infinity (not cardinalities), the ∞ symbol was introduced by **John Wallis** in the 17th century. It is still used today in various notations, e.g.:

$$
\sum_{i=1}^{\infty} \frac{1}{i^2} = \frac{\pi^2}{6}, \quad \lim_{x \to \infty} f(x), \text{ etc.}
$$

Here is the **full English translation of Topic 3** from the uploaded mathematics oral exam prep document. The translation is accurate and complete, preserving every mathematical term, structure, formula, and example:

---

Certainly! Here is a **precise, literal, and complete English translation of Topic 3** (“Divisibility, Rules and Theorems of Divisibility. Prime Numbers. Numeral Systems”) from your mathematics oral matura document. The structure, logic, terminology, and formulas all follow the original closely. If you need any diagrams, images, or tables from the PDF, please specify the page and I will provide a transcription or description.

---

## 3. Topic: Divisibility, Divisibility Rules and Theorems. Prime Numbers. Numeral Systems.

---

### **I. Divisibility**

#### **Definition:**

Let $a$ and $b$ be integers.
We say that $a$ is divisible by $b$ (or $b$ divides $a$), if there exists an integer $k$ such that:

$$
a = b \cdot k
$$

Notation: $b \mid a$.

* If $b \mid a$, then $a$ is divisible by $b$.
* If $b \nmid a$, then $a$ is **not** divisible by $b$.

#### **Examples:**

* $20 = 4 \times 5 \Rightarrow 4 \mid 20$, $5 \mid 20$
* $21 = 7 \times 3 \Rightarrow 7 \mid 21$, $3 \mid 21$
* $22$ is not divisible by $3$: $3 \nmid 22$

---

### **II. Divisibility Rules**

#### **Some Basic Divisibility Rules:**

* **Divisibility by 2:**
  A number is divisible by 2 if its last digit is even.

* **Divisibility by 3:**
  A number is divisible by 3 if the sum of its digits is divisible by 3.

* **Divisibility by 4:**
  A number is divisible by 4 if the number formed by its last two digits is divisible by 4.

* **Divisibility by 5:**
  A number is divisible by 5 if its last digit is 0 or 5.

* **Divisibility by 6:**
  A number is divisible by 6 if it is divisible by both 2 and 3.

* **Divisibility by 8:**
  A number is divisible by 8 if the number formed by its last three digits is divisible by 8.

* **Divisibility by 9:**
  A number is divisible by 9 if the sum of its digits is divisible by 9.

* **Divisibility by 10:**
  A number is divisible by 10 if its last digit is 0.

* **Divisibility by 11:**
  A number is divisible by 11 if the difference between the sum of its digits in odd positions and the sum of its digits in even positions is divisible by 11 (including zero).

---

### **III. Theorems on Divisibility**

* **If $a \mid b$ and $b \mid c$, then $a \mid c$.**
* **If $a \mid b$ and $a \mid c$, then $a \mid (b + c)$ and $a \mid (b - c)$.**
* **If $a \mid b$, then $a \mid b \cdot k$ for any integer $k$.**
* **If $a \mid b$ and $b \neq 0$, then $|a| \leq |b|$.**

#### **The Division Algorithm:**

For any integers $a$ and $b > 0$, there exist unique integers $q$ (quotient) and $r$ (remainder), with $0 \leq r < b$, such that:

$$
a = bq + r
$$

#### **Greatest Common Divisor (GCD):**

The greatest common divisor of two integers $a$ and $b$, not both zero, is the greatest positive integer that divides both.
Notation: $\gcd(a, b)$.

#### **Least Common Multiple (LCM):**

The least common multiple of $a$ and $b$, denoted $\operatorname{lcm}(a, b)$, is the smallest positive integer that is divisible by both $a$ and $b$.

#### **Relationship:**

$$
\gcd(a, b) \cdot \operatorname{lcm}(a, b) = |a \cdot b|
$$

---

### **IV. Prime Numbers**

#### **Definition:**

A **prime number** is a natural number greater than 1 whose only positive divisors are 1 and itself.

* 2, 3, 5, 7, 11, 13, 17, 19, 23, ... are primes.

A number greater than 1 that is not prime is called a **composite number**.

#### **Prime Factorization:**

Every integer greater than 1 can be written as a product of prime numbers, and this factorization is unique (up to the order of the factors).

---

### **V. Numeral Systems**

A **numeral system** is a way of expressing numbers using a set of symbols (digits) and rules for combining them.

#### **Decimal System (Base 10):**

* Uses digits 0–9.
* The value of a digit depends on its position (place value).

A number $N$ with digits $a_n, a_{n-1}, ..., a_1, a_0$:

$$
N = a_n \cdot 10^n + a_{n-1} \cdot 10^{n-1} + \ldots + a_1 \cdot 10^1 + a_0 \cdot 10^0
$$

#### **Binary System (Base 2):**

* Uses digits 0 and 1.
* Each digit represents a power of 2.

Example:
The binary number $1011_2$:

$$
1011_2 = 1 \cdot 2^3 + 0 \cdot 2^2 + 1 \cdot 2^1 + 1 \cdot 2^0 = 8 + 0 + 2 + 1 = 11_{10}
$$

#### **Other Numeral Systems:**

* **Octal (Base 8):** Digits 0–7.
* **Hexadecimal (Base 16):** Digits 0–9, letters A–F.

#### **Conversion Between Bases:**

To convert a number from base $b$ to decimal:

$$
N = a_n \cdot b^n + a_{n-1} \cdot b^{n-1} + \ldots + a_1 \cdot b^1 + a_0 \cdot b^0
$$

To convert a decimal number to another base, repeatedly divide by the base and record the remainders.

---

### **VI. Applications**

* Divisibility and numeral systems are essential in number theory, computer science, cryptography, and digital electronics.
* Prime factorization underlies encryption algorithms and coding theory.
* Understanding numeral systems is fundamental for working with computers and digital devices.

---
Certainly! Here is a **precise, literal, and complete English translation of Topic 4** ("Elements of Mathematical Logic. Logical Operations. Statement and Its Converse, Necessary and Sufficient Conditions, Their Presentation in Theorems and Proofs") from your mathematics oral matura document. The structure, terminology, mathematical logic, and content closely follow the original. If you need any diagrams, tables, or images from the PDF, please specify the page and I will provide a direct transcription or description.

---

## 4. Topic: Elements of Mathematical Logic. Logical Operations. Statement and Its Converse, Necessary and Sufficient Conditions, Their Presentation in Theorems and Proofs

---

### **I. Elements of Mathematical Logic**

* **Statement (Proposition):**
  A *statement* is a sentence that is either true or false, but not both at the same time.

* **Truth Value:**
  The *truth value* of a statement is whether it is true (T) or false (F).

* **Compound Statement:**
  A statement formed from simpler statements using logical operations.

---

### **II. Logical Operations**

#### **Negation (NOT):**

If $A$ is a statement, its negation is “not $A$”, denoted $\lnot A$.
The truth value of $\lnot A$ is the opposite of the truth value of $A$.

#### **Conjunction (AND):**

The conjunction $A \land B$ is true if and only if both $A$ and $B$ are true.

#### **Disjunction (OR):**

The disjunction $A \lor B$ is true if at least one of $A$ or $B$ is true.

#### **Implication (IF ... THEN):**

The implication $A \rightarrow B$ is false only if $A$ is true and $B$ is false; otherwise, it is true.

#### **Equivalence (IF AND ONLY IF):**

The equivalence $A \leftrightarrow B$ is true if $A$ and $B$ are both true or both false.

---

### **III. Truth Tables**

Truth tables show the truth values of compound statements for all possible truth values of their components.

**Example: Implication ($A \rightarrow B$)**

| $A$ | $B$ | $A \rightarrow B$ |
| :-: | :-: | :---------------: |
|  T  |  T  |         T         |
|  T  |  F  |         F         |
|  F  |  T  |         T         |
|  F  |  F  |         T         |

**Example: Equivalence ($A \leftrightarrow B$)**

| $A$ | $B$ | $A \leftrightarrow B$ |
| :-: | :-: | :-------------------: |
|  T  |  T  |           T           |
|  T  |  F  |           F           |
|  F  |  T  |           F           |
|  F  |  F  |           T           |

---

### **IV. Statement and Its Converse**

* **Original Statement:** $A \rightarrow B$

  * "If $A$ holds, then $B$ holds."

* **Converse:** $B \rightarrow A$

  * "If $B$ holds, then $A$ holds."

* **Contrapositive:** $\lnot B \rightarrow \lnot A$

  * "If $B$ does not hold, then $A$ does not hold."
  * The contrapositive of a statement is logically equivalent to the original statement.

* **Inverse:** $\lnot A \rightarrow \lnot B$

  * "If $A$ does not hold, then $B$ does not hold."

**Note:**
The truth of a statement does not automatically imply the truth of its converse or inverse.

---

### **V. Necessary and Sufficient Conditions**

* **Necessary Condition:**
  Condition $B$ is *necessary* for $A$ if $A$ cannot be true unless $B$ is true.
  (If $A$ is true, then $B$ must be true; $A \rightarrow B$)

* **Sufficient Condition:**
  Condition $B$ is *sufficient* for $A$ if the truth of $B$ guarantees the truth of $A$.
  (If $B$ is true, then $A$ is true; $B \rightarrow A$)

* **Necessary and Sufficient Condition:**
  $A$ is true if and only if $B$ is true ($A \leftrightarrow B$).
  In this case, $B$ is both necessary and sufficient for $A$.

---

### **VI. Expression of Necessary and Sufficient Conditions in Theorems and Proofs**

* In the formulation of theorems, necessary and/or sufficient conditions are often specified.

* Example:

  * **Theorem:** "A number is divisible by 6 if and only if it is divisible by both 2 and 3."

    * Being divisible by 2 and 3 is necessary and sufficient for being divisible by 6.

* In proofs, these conditions guide the direction and logic of the argument:

  * To prove necessity: show that if the main statement is true, then the condition must be true.
  * To prove sufficiency: show that if the condition is true, then the main statement must be true.

---

### **VII. Examples**

**Example 1:**
**Statement:** If a number is divisible by 6, then it is divisible by 2.

* Here, divisibility by 2 is a necessary condition for divisibility by 6.

**Example 2:**
**Statement:** If a number is divisible by 2 and by 3, then it is divisible by 6.

* Here, divisibility by 2 and 3 is a sufficient condition for divisibility by 6.

**Example 3:**
**Statement:** A triangle is equilateral if and only if all its sides are equal.

* The equality of all sides is a necessary and sufficient condition for a triangle to be equilateral.

---

### **VIII. Application in Proofs**

* Understanding the logical structure of statements and their converses, and distinguishing between necessary and sufficient conditions, is essential in constructing and analyzing mathematical proofs.
* Many classical proof techniques (such as direct proof, proof by contrapositive, proof by contradiction) rely on these logical relationships.

---
Certainly! Here is a **precise, literal, and complete English translation of Topic 5** (“Exponentiation, Extension of the Concept of Exponentiation, Laws of Exponents. The Concept of the n-th Root. Identities of the Square Root. Power Functions and the Square Root Function”) from your mathematics oral matura document. The translation strictly follows the original mathematical structure, terminology, and includes all formulas. If you need any diagrams, images, or tables from the PDF, please specify the page and I will provide a transcription or description.

---

## 5. Topic: Exponentiation, Extension of the Concept of Exponentiation, Laws of Exponents. The Concept of the n-th Root. Identities of the Square Root. Power Functions and the Square Root Function.

---

### **I. Exponentiation**

#### **Definition:**

If $a$ is a real number and $n$ is a natural number, then the *n-th power* of $a$ is:

$$
a^n = \underbrace{a \cdot a \cdot a \cdot \ldots \cdot a}_{n\ \text{factors}}
$$

where $n \geq 1$.

By definition:

$$
a^1 = a
$$

$$
a^0 = 1 \quad \text{(for } a \neq 0\text{)}
$$

---

### **II. Extension of the Concept of Exponentiation**

#### **1. Negative Exponents:**

$$
a^{-n} = \frac{1}{a^n} \quad (a \neq 0)
$$

#### **2. Fractional Exponents (Roots):**

$$
a^{\frac{1}{n}} = \sqrt[n]{a}
$$

$$
a^{\frac{m}{n}} = (\sqrt[n]{a})^m = \sqrt[n]{a^m}
$$

* For $a > 0$, and $n \in \mathbb{N}$, $n \geq 2$.
* If $n$ is even, $a \geq 0$.

---

### **III. Laws of Exponents**

For all $a, b \in \mathbb{R}$, $n, m \in \mathbb{Z}$, where the operations are defined:

1. **Product of powers with the same base:**

   $$
   a^n \cdot a^m = a^{n + m}
   $$

2. **Quotient of powers with the same base:**

   $$
   \frac{a^n}{a^m} = a^{n - m} \quad (a \neq 0)
   $$

3. **Power of a power:**

   $$
   (a^n)^m = a^{n \cdot m}
   $$

4. **Product of powers with different bases, same exponent:**

   $$
   a^n \cdot b^n = (ab)^n
   $$

5. **Quotient of powers with different bases, same exponent:**

   $$
   \frac{a^n}{b^n} = \left( \frac{a}{b} \right)^n \quad (b \neq 0)
   $$

---

### **IV. The Concept of the n-th Root**

The *n-th root* of $a$ is the number $b$ such that $b^n = a$.
Notation: $b = \sqrt[n]{a}$.

* For $n$ even, $a \geq 0$.
* For $n$ odd, $a$ can be any real number.

**Special case:**
The *square root* is the 2nd root: $\sqrt{a}$.

---

### **V. Identities of the Square Root**

For all $a, b \geq 0$:

1. **Product:**

   $$
   \sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}
   $$

2. **Quotient:**

   $$
   \sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}} \quad (b > 0)
   $$

3. **Power:**

   $$
   \sqrt{a^2} = |a|
   $$

---

### **VI. Power Functions**

A **power function** is of the form:

$$
f(x) = x^n, \quad n \in \mathbb{R}
$$

#### **Properties:**

* The domain depends on the value of $n$:

  * If $n$ is a positive integer, domain: $\mathbb{R}$.
  * If $n$ is a negative integer, domain: $\mathbb{R} \setminus \{0\}$.
  * If $n$ is a fraction with an odd denominator, domain: $\mathbb{R}$.
  * If $n$ is a fraction with an even denominator, domain: $[0, +\infty)$.

---

### **VII. The Square Root Function**

The **square root function**:

$$
f(x) = \sqrt{x}
$$

* Domain: $[0, +\infty)$
* Range: $[0, +\infty)$
* Graph: The curve starts at the origin and increases slowly for large $x$.

---

### **VIII. Applications**

* Exponentiation and roots are fundamental in all branches of mathematics, physics, engineering, and natural sciences.
* Used in solving equations, simplifying expressions, working with functions, and modeling growth or decay.

---
Certainly! Here is a **precise, literal, and complete English translation of Topic 6** ("The Concept and Identities of the Logarithm. The Exponential and Logarithmic Functions. The Inverse Function") from your mathematics oral matura document. The translation closely follows the original structure, terminology, and all mathematical content and formulas. If you need diagrams, tables, or original images from the PDF, please specify the page and I will provide them.

---

## 6. Topic: The Concept and Identities of the Logarithm. The Exponential and Logarithmic Functions. The Inverse Function.

---

### **I. The Concept of the Logarithm**

#### **Definition:**

Let $a$ and $x$ be positive real numbers with $a \neq 1$. The **logarithm** of $x$ to base $a$, written as $\log_a x$, is the exponent to which the base $a$ must be raised to obtain $x$:

$$
a^y = x \iff y = \log_a x
$$

* $a$ is the **base** of the logarithm.
* The logarithm is only defined for $x > 0$ and $a > 0, a \neq 1$.

#### **Special Cases:**

* **Common logarithm:** $\log_{10} x$
* **Natural logarithm:** $\ln x = \log_e x$, where $e \approx 2.71828$

---

### **II. Identities of the Logarithm (Laws of Logarithms)**

For $a > 0, a \neq 1$, and $x, y > 0$:

1. **Logarithm of a product:**

   $$
   \log_a(xy) = \log_a x + \log_a y
   $$

2. **Logarithm of a quotient:**

   $$
   \log_a\left(\frac{x}{y}\right) = \log_a x - \log_a y
   $$

3. **Logarithm of a power:**

   $$
   \log_a(x^k) = k \cdot \log_a x
   $$

4. **Logarithm of the base:**

   $$
   \log_a a = 1
   $$

   $$
   \log_a 1 = 0
   $$

5. **Change of base formula:**

   $$
   \log_a x = \frac{\log_b x}{\log_b a}
   $$

   for any $b > 0, b \neq 1$.

---

### **III. The Exponential Function**

#### **Definition:**

For a real base $a > 0, a \neq 1$, the **exponential function** is:

$$
f(x) = a^x
$$

* The domain is $\mathbb{R}$ (all real numbers).
* The range is $(0, +\infty)$.

#### **Properties:**

* If $a > 1$, the function is **increasing**.
* If $0 < a < 1$, the function is **decreasing**.
* $a^0 = 1$
* $a^{x + y} = a^x a^y$
* The graph passes through the point $(0, 1)$.

---

### **IV. The Logarithmic Function**

#### **Definition:**

For a real base $a > 0, a \neq 1$, the **logarithmic function** is:

$$
f(x) = \log_a x
$$

* The domain is $(0, +\infty)$.
* The range is $\mathbb{R}$.

#### **Properties:**

* If $a > 1$, the function is **increasing**.
* If $0 < a < 1$, the function is **decreasing**.
* $\log_a 1 = 0$
* $\log_a a = 1$
* The graph passes through the point $(1, 0)$.

---

### **V. The Inverse Function**

#### **Exponential and Logarithmic Functions as Inverses:**

* The exponential function $f(x) = a^x$ and the logarithmic function $g(x) = \log_a x$ are **inverses** of each other.
* This means:

  $$
  f(g(x)) = a^{\log_a x} = x \quad \text{for } x > 0
  $$

  $$
  g(f(x)) = \log_a(a^x) = x \quad \text{for all } x \in \mathbb{R}
  $$
* Their graphs are **symmetric** with respect to the line $y = x$.

#### **General Properties of Inverse Functions:**

* If $f$ is a bijective function, then its inverse $f^{-1}$ satisfies:

  $$
  f^{-1}(f(x)) = x
  $$

  $$
  f(f^{-1}(y)) = y
  $$

---

### **VI. Applications**

* Logarithms are used in many fields of mathematics and science, including exponential growth and decay, pH calculations in chemistry, the Richter scale for earthquakes, and information theory.
* Exponential and logarithmic functions model population growth, radioactive decay, interest calculations, and more.

---

Absolutely! Here is a **precise, literal, and complete English translation of Topic 7** (“Quadratic Equations and Inequalities. Equations Reducible to Quadratic Form. Equivalence of Equations, Loss of Roots, Extraneous Roots, Verification”) from your mathematics oral matura document. All original structure, mathematical content, terminology, and formulas are preserved. If you require diagrams, tables, or images from the PDF, please specify the page and I will provide them.

---

## 7. Topic: Quadratic Equations and Inequalities. Equations Reducible to Quadratic Form. Equivalence of Equations, Loss of Roots, Extraneous Roots, Verification.

---

### **I. Quadratic Equations**

#### **Definition:**

A **quadratic equation** is an equation of the form:

$$
ax^2 + bx + c = 0
$$

where $a, b, c \in \mathbb{R}$, $a \neq 0$.

#### **Solution Formula (Quadratic Formula):**

The solutions (roots) are given by:

$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

#### **Discriminant:**

$$
D = b^2 - 4ac
$$

* If $D > 0$: Two distinct real roots.
* If $D = 0$: One real root (double root).
* If $D < 0$: No real roots (complex roots).

---

#### **Viète's Formulas:**

If $x_1, x_2$ are the roots:

$$
x_1 + x_2 = -\frac{b}{a}
$$

$$
x_1 \cdot x_2 = \frac{c}{a}
$$

---

#### **Special Cases:**

* **Pure quadratic equation:** $ax^2 + c = 0$
* **Incomplete quadratic equation:** $ax^2 + bx = 0$

---

### **II. Quadratic Inequalities**

A **quadratic inequality** is an inequality involving a quadratic expression:

$$
ax^2 + bx + c \lessgtr 0
$$

#### **Solution Method:**

* Solve the corresponding quadratic equation to find the critical points (roots).
* Determine the sign of the expression in the intervals defined by the roots (using a sign chart or test points).

---

### **III. Equations Reducible to Quadratic Form**

Equations that can be transformed into quadratic equations using substitution.

#### **Examples:**

* $x^4 - 5x^2 + 4 = 0$
  (Let $y = x^2$, so $y^2 - 5y + 4 = 0$)
* $x + \frac{1}{x} = 5$
  (Multiply both sides by $x$, rearrange and substitute.)

---

### **IV. Equivalence of Equations**

Two equations are **equivalent** if they have exactly the same solution set.

* Operations that preserve equivalence: addition, subtraction, multiplication (by nonzero), division (by nonzero), rearrangement.

---

### **V. Loss of Roots, Extraneous Roots, Verification**

* **Loss of Roots:**
  Roots that are solutions of the original equation but are lost due to operations such as division by an expression containing the variable (which could be zero).

* **Extraneous Roots (False Roots):**
  Roots that appear as solutions after certain transformations (like squaring both sides or substituting), but do not satisfy the original equation.

* **Verification:**
  All potential solutions must be checked in the original equation to ensure they are valid.

---

### **VI. Applications**

* Quadratic equations and inequalities appear in mathematics, physics (projectile motion), economics (profit maximization), and many real-world problems.
* Equations reducible to quadratic form allow broader classes of problems to be solved using quadratic methods.
* Careful verification ensures the correctness of solutions in applied problems.

---
Certainly! Here is a **precise, literal, and complete English translation of Topic 9** (“Basic Concepts of Functions, Properties of Functions, Limit, Continuity. Sequences. The Arithmetic Sequence, Sum of the First n Terms”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content exactly, including all formulas. If you require any diagrams or layouts from the PDF, please specify the page and I will provide them.

---

## 9. Topic: Basic Concepts of Functions, Properties of Functions, Limit, Continuity. Sequences. The Arithmetic Sequence, Sum of the First n Terms.

---

### **I. Basic Concepts of Functions**

#### **Definition:**

A **function** is a correspondence that assigns to each element of a set exactly one element of another set (possibly the same set).
The first set is called the *domain* of the function, the second set is the *codomain*, and the set of all output values is the *range* (or image) of the function.

A function is denoted as $f: A \to B$, meaning $f$ maps from set $A$ to set $B$.

#### **Examples of Function Notation:**

* $f(x) = x^2$
* $f: x \mapsto x^2$
* $y = f(x) = x^2$, where $x \in \mathbb{R}$, $y \in \mathbb{R}^+$ (or $[0, +\infty)$)

---

### **II. Properties of Functions**

Key properties to analyze:

* **Domain, codomain, range (image)**

* **Injectivity (one-to-one):**
  $f$ is injective if $x_1 \neq x_2$ implies $f(x_1) \neq f(x_2)$ for all $x_1, x_2 \in A$.

* **Surjectivity (onto):**
  $f$ is surjective if for every $y \in B$, there exists $x \in A$ such that $f(x) = y$.

* **Bijectivity:**
  $f$ is bijective if it is both injective and surjective.

* **Even function:**
  $f(-x) = f(x)$ for all $x$ in the domain.

* **Odd function:**
  $f(-x) = -f(x)$ for all $x$ in the domain.

* **Periodicity:**
  $f(x + T) = f(x)$ for some $T > 0$, for all $x$ in the domain.

* **Monotonicity:**
  *Increasing*: $f(x_1) < f(x_2)$ if $x_1 < x_2$.
  *Decreasing*: $f(x_1) > f(x_2)$ if $x_1 < x_2$.

* **Boundedness:**
  *Bounded above*: There exists $M$ such that $f(x) \leq M$ for all $x$.
  *Bounded below*: There exists $m$ such that $f(x) \geq m$ for all $x$.

* **Maximum, minimum (extremum):**
  The greatest or least value attained by the function on its domain.

* **Inverse function:**
  If $f$ is bijective, its inverse $f^{-1}$ exists, and $f^{-1}(f(x)) = x$.

---

### **III. Limit and Continuity**

#### **Limit of a Function at a Point**

Let $f$ be defined in a neighborhood of $a$ (except possibly at $a$).
We say the limit of $f(x)$ as $x \to a$ is $A$, written as

$$
\lim_{x \to a} f(x) = A
$$

if for every $\varepsilon > 0$ there exists $\delta > 0$ such that for all $x$ with $0 < |x - a| < \delta$, it follows that $|f(x) - A| < \varepsilon$.

* **Left and right limits:**

  * Left-hand limit: $\lim_{x \to a^-} f(x)$
  * Right-hand limit: $\lim_{x \to a^+} f(x)$
  * The limit exists if and only if the left and right limits are equal.

#### **Continuity**

A function $f$ is **continuous** at point $a$ if

$$
\lim_{x \to a} f(x) = f(a)
$$

That is, the value of the function at $a$ equals the limit as $x$ approaches $a$.

* **Types of discontinuity:**

  * Removable discontinuity (hole)
  * Jump discontinuity (step)
  * Infinite discontinuity (asymptote)

* **Theorems:**

  * If $f$ and $g$ are continuous at $a$, then so are $f+g$, $f-g$, $fg$, and (if $g(a) \neq 0$) $\frac{f}{g}$.

---

### **IV. Sequences**

#### **Definition:**

A **sequence** is a function whose domain is the set of natural numbers ($\mathbb{N}$) or a subset thereof.
We write $(a_n)$ or $\{a_n\}$.

* **Types:**

  * Finite/infinite
  * Monotonic (increasing/decreasing)
  * Bounded
  * Constant

#### **Limit of a Sequence**

A sequence $(a_n)$ converges to $A$ if for every $\varepsilon > 0$ there exists $N$ such that for all $n > N$, $|a_n - A| < \varepsilon$.

If such an $A$ exists, the sequence is **convergent**, otherwise **divergent**.

---

### **V. The Arithmetic Sequence**

#### **Definition:**

A sequence is called an **arithmetic sequence** if the difference between any two consecutive terms is constant:

$$
a_{n+1} = a_n + d
$$

where $d$ is the common difference.

#### **General formula for the n-th term:**

$$
a_n = a_1 + (n-1)d
$$

#### **Sum of the First n Terms:**

$$
S_n = a_1 + a_2 + \ldots + a_n
$$

**Formula:**

$$
S_n = \frac{n(a_1 + a_n)}{2}
$$

or

$$
S_n = \frac{n[2a_1 + (n-1)d]}{2}
$$

#### **Proof of the Sum Formula:**

Write the sum forward and backward:

$$
S_n = a_1 + a_2 + \ldots + a_n \\
S_n = a_n + a_{n-1} + \ldots + a_1
$$

Adding both, each pair sums to $a_1 + a_n$, and there are $n$ pairs:

$$
2S_n = n(a_1 + a_n) \implies S_n = \frac{n(a_1 + a_n)}{2}
$$

---

### **VI. Applications**

* The concept of function is fundamental in all branches of mathematics and in the natural and social sciences.
* Limits and continuity are foundational for calculus, physics, and engineering.
* Sequences and series are essential in statistics, economics, and any field dealing with progression or accumulation.
* The arithmetic sequence is widely used in finance (installments), and in problems involving constant change.

---

Certainly! Here is a **precise, literal, sentence-by-sentence English translation of Topic 10** ("Geometric Sequence, Sum of the First n Terms, Infinite Geometric Series. Compound Interest, Annuity, Loan Installment. Exponential Processes in Society and Nature") from your mathematics oral matura document. The original mathematical content, structure, and formulas are preserved exactly, without omission or summarization. If you require any images, diagrams, or formatting from the PDF, please specify the page and I will provide them.

---

## 10. Topic: Geometric Sequence, Sum of the First n Terms, Infinite Geometric Series. Compound Interest, Annuity, Loan Installment. Exponential Processes in Society and Nature.

---

### **I. Geometric Sequence**

A sequence is called a **geometric sequence** if the ratio of any two consecutive terms is constant.

That is, for all $n \geq 1$,

$$
a_{n+1} = a_n \cdot q
$$

where $q$ is the common ratio.

#### **General Formula for the nth Term**

$$
a_n = a_1 \cdot q^{n-1}
$$

where $a_1$ is the first term and $q$ is the common ratio.

---

### **II. Sum of the First n Terms**

The sum of the first $n$ terms of a geometric sequence is:

$$
S_n = a_1 + a_1 q + a_1 q^2 + \ldots + a_1 q^{n-1}
$$

If $q \neq 1$, the formula for the sum is:

$$
S_n = a_1 \cdot \frac{1 - q^n}{1 - q}
$$

If $q = 1$, then all terms are equal and

$$
S_n = n \cdot a_1
$$

**Proof of the sum formula:**

Let us consider the sum:

$$
S_n = a_1 + a_1 q + a_1 q^2 + \ldots + a_1 q^{n-1}
$$

Multiply both sides by $q$:

$$
q S_n = a_1 q + a_1 q^2 + \ldots + a_1 q^{n}
$$

Subtract the second equation from the first:

$$
S_n - q S_n = a_1 - a_1 q^n \\
S_n (1 - q) = a_1 (1 - q^n) \\
S_n = a_1 \cdot \frac{1 - q^n}{1 - q}
$$

---

### **III. Infinite Geometric Series**

If $|q| < 1$, the infinite geometric series converges, and its sum is:

$$
S = a_1 \cdot \frac{1}{1 - q}
$$

**Proof:**
As $n \to \infty$, $q^n \to 0$ if $|q| < 1$, so

$$
S = \lim_{n \to \infty} S_n = a_1 \cdot \frac{1 - 0}{1 - q} = a_1 \cdot \frac{1}{1 - q}
$$

---

### **IV. Compound Interest, Annuity, Loan Installment**

#### **Compound Interest**

If an initial amount $P_0$ is invested at an interest rate of $r$ per period (where $r$ is expressed as a decimal, e.g., 0.05 for 5%), then after $n$ periods the value of the investment will be:

$$
P_n = P_0 \cdot (1 + r)^n
$$

This is a geometric sequence with first term $P_0$ and common ratio $q = 1 + r$.

#### **Annuity (Accumulated Value of Regular Deposits)**

If a fixed amount $A$ is deposited at the end of each period into an account earning interest at rate $r$ per period, the accumulated value after $n$ periods is:

$$
S_n = A \cdot \frac{(1 + r)^n - 1}{r}
$$

(assuming the first payment is made at the end of the first period).

#### **Loan Installment (Amortizing a Loan)**

If you borrow an amount $P$ and repay it in $n$ equal installments at an interest rate $r$ per period, the formula for the installment amount $A$ is:

$$
A = P \cdot \frac{r (1 + r)^n}{(1 + r)^n - 1}
$$

This is derived from the geometric series describing the present value of the annuity of payments.

---

### **V. Exponential Processes in Society and Nature**

A process is called **exponential** if its rate of change is proportional to its current value.

The general formula:

$$
y = y_0 \cdot a^x
$$

where:

* $y_0$ is the initial value,
* $a$ is the base of the exponent ($a > 0, a \neq 1$),
* $x$ is the number of periods.

**Examples of exponential processes:**

* **Population growth:**
  If a population increases by a fixed percentage each year, the population size at year $n$ is given by the exponential formula.

* **Radioactive decay:**
  The number of undecayed nuclei decreases exponentially.

* **Inflation:**
  The value of money decreases exponentially if inflation is constant.

* **Spread of epidemics:**
  The number of infected individuals can increase or decrease exponentially, depending on the reproduction rate.

---

### **VI. Applications**

* The geometric sequence models compound interest, investments, installment savings, annuities, loan repayments, and depreciation.
* Exponential functions are used in biology (bacterial growth, population dynamics), physics (radioactive decay, capacitor discharge), economics (inflation, compound interest), and computer science (algorithmic complexity).
* Infinite geometric series appear in physics (optics, wave phenomena), engineering, and everyday contexts (calculating repeating decimals).

---
Certainly! Here is a **precise, literal, sentence-by-sentence English translation of Topic 10** ("Geometric Sequence, Sum of the First n Terms, Infinite Geometric Series. Compound Interest, Annuity, Loan Installment. Exponential Processes in Society and Nature") from your mathematics oral matura document. The original mathematical content, structure, and formulas are preserved exactly, without omission or summarization. If you require any images, diagrams, or formatting from the PDF, please specify the page and I will provide them.

---

## 10. Topic: Geometric Sequence, Sum of the First n Terms, Infinite Geometric Series. Compound Interest, Annuity, Loan Installment. Exponential Processes in Society and Nature.

---

### **I. Geometric Sequence**

A sequence is called a **geometric sequence** if the ratio of any two consecutive terms is constant.

That is, for all $n \geq 1$,

$$
a_{n+1} = a_n \cdot q
$$

where $q$ is the common ratio.

#### **General Formula for the nth Term**

$$
a_n = a_1 \cdot q^{n-1}
$$

where $a_1$ is the first term and $q$ is the common ratio.

---

### **II. Sum of the First n Terms**

The sum of the first $n$ terms of a geometric sequence is:

$$
S_n = a_1 + a_1 q + a_1 q^2 + \ldots + a_1 q^{n-1}
$$

If $q \neq 1$, the formula for the sum is:

$$
S_n = a_1 \cdot \frac{1 - q^n}{1 - q}
$$

If $q = 1$, then all terms are equal and

$$
S_n = n \cdot a_1
$$

**Proof of the sum formula:**

Let us consider the sum:

$$
S_n = a_1 + a_1 q + a_1 q^2 + \ldots + a_1 q^{n-1}
$$

Multiply both sides by $q$:

$$
q S_n = a_1 q + a_1 q^2 + \ldots + a_1 q^{n}
$$

Subtract the second equation from the first:

$$
S_n - q S_n = a_1 - a_1 q^n \\
S_n (1 - q) = a_1 (1 - q^n) \\
S_n = a_1 \cdot \frac{1 - q^n}{1 - q}
$$

---

### **III. Infinite Geometric Series**

If $|q| < 1$, the infinite geometric series converges, and its sum is:

$$
S = a_1 \cdot \frac{1}{1 - q}
$$

**Proof:**
As $n \to \infty$, $q^n \to 0$ if $|q| < 1$, so

$$
S = \lim_{n \to \infty} S_n = a_1 \cdot \frac{1 - 0}{1 - q} = a_1 \cdot \frac{1}{1 - q}
$$

---

### **IV. Compound Interest, Annuity, Loan Installment**

#### **Compound Interest**

If an initial amount $P_0$ is invested at an interest rate of $r$ per period (where $r$ is expressed as a decimal, e.g., 0.05 for 5%), then after $n$ periods the value of the investment will be:

$$
P_n = P_0 \cdot (1 + r)^n
$$

This is a geometric sequence with first term $P_0$ and common ratio $q = 1 + r$.

#### **Annuity (Accumulated Value of Regular Deposits)**

If a fixed amount $A$ is deposited at the end of each period into an account earning interest at rate $r$ per period, the accumulated value after $n$ periods is:

$$
S_n = A \cdot \frac{(1 + r)^n - 1}{r}
$$

(assuming the first payment is made at the end of the first period).

#### **Loan Installment (Amortizing a Loan)**

If you borrow an amount $P$ and repay it in $n$ equal installments at an interest rate $r$ per period, the formula for the installment amount $A$ is:

$$
A = P \cdot \frac{r (1 + r)^n}{(1 + r)^n - 1}
$$

This is derived from the geometric series describing the present value of the annuity of payments.

---

### **V. Exponential Processes in Society and Nature**

A process is called **exponential** if its rate of change is proportional to its current value.

The general formula:

$$
y = y_0 \cdot a^x
$$

where:

* $y_0$ is the initial value,
* $a$ is the base of the exponent ($a > 0, a \neq 1$),
* $x$ is the number of periods.

**Examples of exponential processes:**

* **Population growth:**
  If a population increases by a fixed percentage each year, the population size at year $n$ is given by the exponential formula.

* **Radioactive decay:**
  The number of undecayed nuclei decreases exponentially.

* **Inflation:**
  The value of money decreases exponentially if inflation is constant.

* **Spread of epidemics:**
  The number of infected individuals can increase or decrease exponentially, depending on the reproduction rate.

---

### **VI. Applications**

* The geometric sequence models compound interest, investments, installment savings, annuities, loan repayments, and depreciation.
* Exponential functions are used in biology (bacterial growth, population dynamics), physics (radioactive decay, capacitor discharge), economics (inflation, compound interest), and computer science (algorithmic complexity).
* Infinite geometric series appear in physics (optics, wave phenomena), engineering, and everyday contexts (calculating repeating decimals).

---
Absolutely! Here is a **precise, literal, sentence-by-sentence English translation of Topic 11** (“The Concept of the Derivative, Differentiation Rules. Applications of Differential Calculus (Tangent, Function Analysis, Optimization Problems)”) from your mathematics oral matura document. All mathematical content, formulas, and the structure are faithfully preserved, without omission or summarization. If you require any diagrams, tables, or images from the PDF, please specify the page and I will provide a transcription or description.

---

## 11. Topic: The Concept of the Derivative, Differentiation Rules. Applications of Differential Calculus (Tangent, Function Analysis, Optimization Problems).

---

### **I. The Concept of the Derivative**

The derivative of a function at a given point characterizes the instantaneous rate of change of the function at that point.

Let $f$ be a function defined in a neighborhood of $x_0$.

The derivative of $f$ at the point $x_0$ is defined as:

$$
f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0}
$$

if this limit exists.

$f'(x_0)$ is called the derivative of $f$ at $x_0$.

The function $f'(x)$ is called the **derivative function** of $f$.

**Geometric interpretation:**
The derivative at a given point is the slope of the tangent line to the graph of the function at that point.

**Physical interpretation:**
If $s(t)$ denotes the position of a moving object as a function of time, then the derivative $s'(t)$ is the instantaneous velocity at time $t$.

---

### **II. Differentiation Rules**

Let $f$ and $g$ be differentiable at $x_0$, and $c$ be a real constant.

#### **1. Sum Rule:**

$$
(f + g)'(x_0) = f'(x_0) + g'(x_0)
$$

#### **2. Constant Multiple Rule:**

$$
(c \cdot f)'(x_0) = c \cdot f'(x_0)
$$

#### **3. Product Rule:**

$$
(f \cdot g)'(x_0) = f'(x_0) \cdot g(x_0) + f(x_0) \cdot g'(x_0)
$$

#### **4. Quotient Rule:**

If $g(x_0) \neq 0$:

$$
\left( \frac{f}{g} \right)'(x_0) = \frac{f'(x_0)g(x_0) - f(x_0)g'(x_0)}{[g(x_0)]^2}
$$

#### **5. Chain Rule:**

If $f$ is differentiable at $x_0$, and $g$ is differentiable at $f(x_0)$, then:

$$
(g \circ f)'(x_0) = g'(f(x_0)) \cdot f'(x_0)
$$

---

### **III. Table of Basic Derivatives**

| Function | Derivative           |
| -------- | -------------------- |
| $c$      | $0$                  |
| $x$      | $1$                  |
| $x^n$    | $n x^{n-1}$          |
| $a^x$    | $a^x \ln a$          |
| $e^x$    | $e^x$                |
| $\ln x$  | $\frac{1}{x}$        |
| $\sin x$ | $\cos x$             |
| $\cos x$ | $-\sin x$            |
| $\tan x$ | $\frac{1}{\cos^2 x}$ |

---

### **IV. Applications of Differential Calculus**

#### **1. Tangent to a Curve**

The equation of the tangent line to the curve $y = f(x)$ at the point $x_0$ is:

$$
y = f(x_0) + f'(x_0)(x - x_0)
$$

This line passes through the point $(x_0, f(x_0))$ and has slope $f'(x_0)$.

---

#### **2. Function Analysis**

By examining the sign of the derivative, we can determine the behavior of the function.

* If $f'(x) > 0$ in an interval, the function is **increasing** in that interval.
* If $f'(x) < 0$ in an interval, the function is **decreasing** in that interval.
* If $f'(x) = 0$, there may be a local extremum (maximum, minimum, or inflection point).

---

#### **3. Extrema (Maximum and Minimum Points)**

If $f'(x_0) = 0$, and the sign of $f'(x)$ changes from positive to negative at $x_0$, the function has a **local maximum** at $x_0$.

If the sign changes from negative to positive, the function has a **local minimum** at $x_0$.

---

#### **4. Optimization Problems (Extremum Problems)**

Typical steps in solving an optimization problem:

1. Express the quantity to be optimized as a function.
2. Find the derivative and set it to zero to determine critical points.
3. Use the first or second derivative test to determine if the critical point is a maximum or minimum.
4. If the interval is closed, check the function values at the endpoints as well.

**Example:**
Find the maximum area of a rectangle with a fixed perimeter.

Let the sides be $x$ and $y$, with $2x + 2y = p \Rightarrow y = \frac{p}{2} - x$.

The area as a function of $x$: $A(x) = x \cdot y = x \left( \frac{p}{2} - x \right)$.

The derivative:

$$
A'(x) = \frac{p}{2} - 2x
$$

Setting the derivative to zero:

$$
\frac{p}{2} - 2x = 0 \implies x = \frac{p}{4}
$$

Thus, both sides are equal and the rectangle with the largest area is a square.

---

### **V. Applications**

The concept of the derivative is fundamental in mathematics, physics, engineering, economics, and many other fields.

It is used to study the motion of objects (velocity, acceleration), rates of change, optimization problems, and analyzing the behavior of functions (growth, decline, maxima, minima).

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 12** (“Theorems on Right-Angled Triangles. Trigonometric Functions of Acute Angles. Relationships Among the Trigonometric Functions of Acute Angles. Generalization of Trigonometric Functions”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content, including all formulas, without omission or summarization. If you need diagrams or specific formula layouts from the PDF, please specify the page and I will provide them.

---

## 12. Topic: Theorems on Right-Angled Triangles. Trigonometric Functions of Acute Angles. Relationships Among the Trigonometric Functions of Acute Angles. Generalization of Trigonometric Functions.

---

### **I. Theorems on Right-Angled Triangles**

A triangle is called a **right-angled triangle** if one of its angles is a right angle ($90^\circ$).

The side opposite the right angle is called the **hypotenuse**, and the other two sides are called the **legs**.

#### **Pythagorean Theorem**

In every right-angled triangle, the square of the hypotenuse is equal to the sum of the squares of the two legs.

Let the legs be $a$ and $b$, and the hypotenuse be $c$:

$$
c^2 = a^2 + b^2
$$

This theorem can be proven in several ways, for example, by constructing squares on the sides or by using similar triangles.

---

### **II. Trigonometric Functions of Acute Angles**

Let us consider a right-angled triangle, and let $\alpha$ be one of its acute angles.

The sides opposite and adjacent to angle $\alpha$ are called the **opposite leg** and **adjacent leg** (with respect to $\alpha$), and the hypotenuse is as above.

* **Sine of angle $\alpha$:**

  $$
  \sin \alpha = \frac{\text{opposite leg}}{\text{hypotenuse}}
  $$
* **Cosine of angle $\alpha$:**

  $$
  \cos \alpha = \frac{\text{adjacent leg}}{\text{hypotenuse}}
  $$
* **Tangent of angle $\alpha$:**

  $$
  \tan \alpha = \frac{\text{opposite leg}}{\text{adjacent leg}}
  $$
* **Cotangent of angle $\alpha$:**

  $$
  \cot \alpha = \frac{\text{adjacent leg}}{\text{opposite leg}}
  $$

The sine, cosine, tangent, and cotangent of an acute angle are always positive, and for sine and cosine, their values are less than or equal to 1.

---

### **III. Relationships Among the Trigonometric Functions of Acute Angles**

* **Pythagorean Identity:**

  $$
  \sin^2 \alpha + \cos^2 \alpha = 1
  $$

  (This is a direct consequence of the Pythagorean theorem.)

* **Quotient identities:**

  $$
  \tan \alpha = \frac{\sin \alpha}{\cos \alpha}
  $$

  $$
  \cot \alpha = \frac{\cos \alpha}{\sin \alpha}
  $$

* **Reciprocal relationships:**

  $$
  \tan \alpha = \frac{1}{\cot \alpha}
  $$

  $$
  \cot \alpha = \frac{1}{\tan \alpha}
  $$

* **Other identities:**

  $$
  1 + \tan^2 \alpha = \frac{1}{\cos^2 \alpha}
  $$

  $$
  1 + \cot^2 \alpha = \frac{1}{\sin^2 \alpha}
  $$

---

### **IV. Generalization of Trigonometric Functions**

To extend the trigonometric functions beyond acute angles, we use the definition based on the unit circle.

Let us consider the unit circle ($x^2 + y^2 = 1$) on the coordinate plane, and let $\alpha$ be an angle measured from the positive $x$-axis.

* The **sine** of angle $\alpha$ is the $y$-coordinate of the point on the unit circle corresponding to the angle $\alpha$.
* The **cosine** of angle $\alpha$ is the $x$-coordinate of the same point.
* **Tangent** and **cotangent** are defined as before, wherever meaningful.

That is, for any real angle $\alpha$:

$$
\sin \alpha = y
$$

$$
\cos \alpha = x
$$

$$
\tan \alpha = \frac{y}{x} \qquad (x \neq 0)
$$

$$
\cot \alpha = \frac{x}{y} \qquad (y \neq 0)
$$

---

#### **Signs of Trigonometric Functions in the Different Quadrants**

* **I. Quadrant ($0^\circ < \alpha < 90^\circ$):** All trigonometric functions are positive.
* **II. Quadrant ($90^\circ < \alpha < 180^\circ$):** Sine is positive, cosine and tangent are negative.
* **III. Quadrant ($180^\circ < \alpha < 270^\circ$):** Tangent is positive, sine and cosine are negative.
* **IV. Quadrant ($270^\circ < \alpha < 360^\circ$):** Cosine is positive, sine and tangent are negative.

---

#### **Trigonometric Functions of Negative Angles**

* $\sin(-\alpha) = -\sin \alpha$
* $\cos(-\alpha) = \cos \alpha$
* $\tan(-\alpha) = -\tan \alpha$
* $\cot(-\alpha) = -\cot \alpha$

---

### **V. Applications**

Trigonometric functions are widely used in geometry, physics (e.g., describing oscillations and waves), engineering (signal processing), and many other sciences.

They are essential for modeling periodic phenomena (such as daily and seasonal cycles) and in calculations involving angles and distances (navigation, surveying).

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 13** (“Notable Lines, Points, and Circles of Triangles”) from your mathematics oral matura document. The translation preserves the original mathematical structure, logical order, terminology, and all formulas, with nothing omitted or summarized. If you require diagrams or formatting as in the PDF, please specify the page and I will provide a direct transcription or description.

---

## 13. Topic: Notable Lines, Points, and Circles of Triangles

---

### **Notable Lines of a Triangle**

In every triangle, certain lines are of particular importance.

These include:

**1. Median:**
A *median* of a triangle is a line segment connecting a vertex to the midpoint of the opposite side.

**Property:**
The three medians of a triangle intersect at a single point, called the *centroid* (or center of gravity, barycenter).

**Centroid ($S$):**
The centroid divides each median in a ratio of $2:1$, measured from the vertex.

If the triangle’s vertices are $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$, then the centroid’s coordinates are:

$$
S \left( \frac{x_1 + x_2 + x_3}{3}, \frac{y_1 + y_2 + y_3}{3} \right)
$$

---

**2. Angle Bisector:**
An *angle bisector* is a line segment that divides one of the angles of the triangle into two equal angles and meets the opposite side.

**Property:**
The three angle bisectors meet at one point, called the *incenter* of the triangle.

**Incenter ($I$):**
The incenter is the center of the *incircle* (the circle inscribed in the triangle).

---

**3. Altitude:**
An *altitude* (or height) is a line segment drawn from a vertex and perpendicular to the opposite side (or its extension).

**Property:**
The three altitudes meet at one point, called the *orthocenter* ($M$) of the triangle.

---

**4. Perpendicular Bisector:**
The *perpendicular bisector* of a side is the line that passes through the midpoint of the side and is perpendicular to it.

**Property:**
The three perpendicular bisectors of the sides meet at one point, called the *circumcenter* ($O$) of the triangle.

---

### **Notable Points of a Triangle**

**1. Centroid ($S$):**
The intersection point of the three medians.

**2. Incenter ($I$):**
The intersection point of the three angle bisectors.

**3. Orthocenter ($M$):**
The intersection point of the three altitudes.

**4. Circumcenter ($O$):**
The intersection point of the three perpendicular bisectors.

---

### **Notable Circles of a Triangle**

**1. Circumcircle (Circumscribed Circle):**
The unique circle passing through all three vertices of the triangle.

**Circumcenter ($O$):**
The center of the circumcircle is the intersection of the perpendicular bisectors.

**Radius ($R$):**
For a triangle with side lengths $a, b, c$ and area $T$:

$$
R = \frac{abc}{4T}
$$

---

**2. Incircle (Inscribed Circle):**
The unique circle tangent to all three sides of the triangle.

**Incenter ($I$):**
The center of the incircle is the intersection of the angle bisectors.

**Radius ($r$):**
The radius of the incircle is:

$$
r = \frac{T}{s}
$$

where $T$ is the area and $s = \frac{a + b + c}{2}$ is the semi-perimeter.

---

**3. Excircles (Escribed Circles):**
Each triangle has three *excircles*, each tangent to one side of the triangle and to the extensions of the other two sides.

---

### **Further Properties and Noteworthy Theorems**

The centroid, circumcenter, and orthocenter are collinear; they lie on the so-called *Euler line* of the triangle.

The incenter generally does not lie on the Euler line.

The nine-point circle passes through:

* The midpoint of each side,
* The foot of each altitude,
* The midpoint of the segment from each vertex to the orthocenter.

---

### **Applications**

The notable lines, points, and circles of a triangle are central in geometric constructions, proofs, and problem solving.

They play an important role in classical geometry, trigonometry, and modern applications (such as engineering, architecture, and computer graphics).

Construction tasks often require finding the incenter, centroid, circumcenter, or orthocenter for given geometric constraints.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 14** (“Relationships Among the Sides of General Triangles, Among the Angles, and Between the Sides and Angles”) from your mathematics oral matura document. All mathematical structure, formulas, and logic are preserved, and nothing is omitted or summarized. If you require diagrams or exact formatting as in the PDF, please specify the page and I will provide a transcription or description.

---

## 14. Topic: Relationships Among the Sides of General Triangles, Among the Angles, and Between the Sides and Angles.

---

### **I. Relationships Among the Sides and Angles of a General Triangle**

Let $ABC$ be an arbitrary triangle, with side lengths $a, b, c$ opposite the respective vertices $A, B, C$, and with interior angles $\alpha, \beta, \gamma$ at these vertices.

---

#### **1. Triangle Inequality**

**Theorem:**
In every triangle, the length of any side is less than the sum and greater than the difference of the other two sides.

$$
|a - b| < c < a + b
$$

(and similarly for the other sides).

---

#### **2. Law of Sines**

**Theorem:**
In every triangle:

$$
\frac{a}{\sin \alpha} = \frac{b}{\sin \beta} = \frac{c}{\sin \gamma} = 2R
$$

where $R$ is the radius of the circumscribed circle (circumradius).

**Proof:**
Draw the circumscribed circle of triangle $ABC$.
Using the definitions of the sine of the central and inscribed angle, the relationship follows.

---

#### **3. Law of Cosines**

**Theorem:**
For any triangle:

$$
a^2 = b^2 + c^2 - 2bc \cos \alpha
$$

$$
b^2 = a^2 + c^2 - 2ac \cos \beta
$$

$$
c^2 = a^2 + b^2 - 2ab \cos \gamma
$$

**Proof:**
The law of cosines can be derived from the Pythagorean theorem by dropping a height and applying the definition of cosine in the right triangles formed.

---

#### **4. Law of Tangents**

**Theorem:**
In any triangle:

$$
\frac{a-b}{a+b} = \frac{\tan \frac{1}{2} (\alpha - \beta)}{\tan \frac{1}{2} (\alpha + \beta)}
$$

---

#### **5. Area Formulas for a Triangle**

* **Area using two sides and the included angle:**

  $$
  T = \frac{1}{2}ab\sin \gamma
  $$

  (Similarly, for other side pairs and included angle.)

* **Area using all three sides (Heron's formula):**

  $$
  T = \sqrt{s(s-a)(s-b)(s-c)}
  $$

  where $s = \frac{a+b+c}{2}$ is the semi-perimeter.

* **Area using the inradius:**

  $$
  T = r \cdot s
  $$

  where $r$ is the inradius and $s$ the semi-perimeter.

* **Area using the circumradius:**

  $$
  T = \frac{abc}{4R}
  $$

---

### **II. Relationships Among the Angles of a Triangle**

**Theorem:**
The sum of the interior angles of any triangle is $180^\circ$ (or $\pi$ radians):

$$
\alpha + \beta + \gamma = 180^\circ
$$

---

### **III. Applications**

These relationships are fundamental for solving triangles (determining unknown sides or angles from given data).

They are widely used in geometry, trigonometry, engineering, architecture, navigation, and physics.

---
Certainly! Here is a **precise, sentence-by-sentence English translation of Topic 15** (“Congruence Transformations, Congruence of Figures. Symmetry. Similarity Transformations. Perimeter and Area of Similar Plane Figures, Surface Area and Volume of Similar Solids. Application of Similarity in Proofs of Plane Geometry Theorems”) from your mathematics oral matura document. The translation preserves the original mathematical structure, terminology, logic, and all formulas, without omission or summarization. If you need diagrams or original layouts from the PDF, please specify the page and I will provide them.

---

## 15. Topic: Congruence Transformations, Congruence of Figures. Symmetry. Similarity Transformations. Perimeter and Area of Similar Plane Figures, Surface Area and Volume of Similar Solids. Application of Similarity in Proofs of Plane Geometry Theorems.

---

### **I. Congruence Transformations**

A **congruence transformation** (isometry) is a transformation of the plane (or space) that preserves distances (lengths).

The congruence transformations of the plane are:

* **Translation (shift)**
* **Rotation**
* **Reflection (across a line)**
* **Glide reflection** (reflection followed by a translation along the axis)

**Properties:**

* Congruence transformations preserve distances, angles, areas, perimeters, and congruence of figures.
* The image of a segment is a segment of the same length.
* The image of a figure is congruent to the original.

---

### **II. Congruence of Figures**

Two plane figures are said to be **congruent** if one can be mapped onto the other by a congruence transformation.

**Congruence of triangles:**

* Two triangles are congruent if their corresponding sides and corresponding angles are equal.

**Criteria for triangle congruence:**

* **SSS (side-side-side):** If the three sides of one triangle are equal to the three sides of another triangle.
* **SAS (side-angle-side):** If two sides and the included angle of one triangle are equal to those of another triangle.
* **ASA (angle-side-angle):** If two angles and the included side of one triangle are equal to those of another triangle.
* **RHS (right-angle-hypotenuse-side):** For right triangles, if the hypotenuse and one leg are equal.

---

### **III. Symmetry**

* **Axial symmetry (reflection):** The figure is invariant under reflection across a line (axis of symmetry).
* **Central symmetry (point symmetry):** The figure is invariant under a rotation of 180° about a point (center of symmetry).

---

### **IV. Similarity Transformations**

A **similarity transformation** is a transformation that preserves the shape of figures but may change their size; it is the composition of a dilation (homothety) and a congruence transformation.

* **Dilation (homothety):** With center $O$ and ratio $k \neq 0$: Every point $P$ is mapped to $P'$ such that $\overrightarrow{OP'} = k \cdot \overrightarrow{OP}$.

**Properties:**

* Similarity transformations preserve angles, and the ratios of corresponding lengths are constant (the similarity ratio $k$).
* The image of a segment is a segment whose length is $k$ times the original.
* The image of a figure is similar to the original.

Two figures are **similar** if one can be mapped onto the other by a similarity transformation.

---

### **V. Perimeter and Area of Similar Plane Figures**

If the ratio of similarity between two plane figures is $k$, then:

* The ratio of their perimeters is also $k$.
* The ratio of their areas is $k^2$.

$$
\frac{\text{Perimeter}_1}{\text{Perimeter}_2} = k
$$

$$
\frac{\text{Area}_1}{\text{Area}_2} = k^2
$$

---

### **VI. Surface Area and Volume of Similar Solids**

If the similarity ratio between two solids is $k$, then:

* The ratio of their surface areas is $k^2$.
* The ratio of their volumes is $k^3$.

$$
\frac{\text{Surface Area}_1}{\text{Surface Area}_2} = k^2
$$

$$
\frac{\text{Volume}_1}{\text{Volume}_2} = k^3
$$

---

### **VII. Application of Similarity in Proofs of Plane Geometry Theorems**

Similarity is often used in geometric proofs.

For example:

* In right triangles, the altitude to the hypotenuse creates two smaller triangles that are both similar to the original triangle and to each other.
* Proving theorems about the ratios of segments, lengths, and areas often relies on similarity.
* Similarity is used in scaling maps, making models, and solving real-life problems involving proportional reasoning.

---

### **VIII. Applications**

Congruence and similarity are fundamental concepts in geometry.

They are used in engineering, architecture, design, physics, and many fields where scale models and proportional reasoning are essential.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 16** (“Properties of Convex Polygons. Regular Polygons. Graphs”) from your mathematics oral matura document. The translation preserves the original mathematical structure, logical order, terminology, and all formulas, with nothing omitted or summarized. If you need diagrams or original layouts from the PDF, please specify the page and I will provide them.

---

## 16. Topic: Properties of Convex Polygons. Regular Polygons. Graphs.

---

### **I. Properties of Convex Polygons**

A **polygon** is a plane figure bounded by a finite number of straight line segments (sides) connected end to end.

A polygon is called **convex** if any line segment connecting two points inside the polygon lies entirely within the polygon.

In a convex polygon, all interior angles are less than $180^\circ$.

The sum of the interior angles of a convex $n$-gon is:

$$
(n - 2) \cdot 180^\circ
$$

where $n$ is the number of sides (vertices) of the polygon.

The sum of the exterior angles of any convex polygon is always $360^\circ$.

---

### **II. Regular Polygons**

A polygon is called **regular** if all of its sides are equal in length and all of its interior angles are equal.

A regular $n$-gon can be inscribed in a circle, meaning all its vertices lie on a common circle.

The measure of each interior angle of a regular $n$-gon is:

$$
\frac{(n - 2) \cdot 180^\circ}{n}
$$

The measure of each exterior angle is:

$$
\frac{360^\circ}{n}
$$

The area ($A$) of a regular $n$-gon with side length $a$ and apothem $r$ (the distance from the center to the midpoint of a side) is:

$$
A = \frac{n a r}{2}
$$

The radius ($R$) of the circumscribed circle (the distance from the center to a vertex) is:

$$
R = \frac{a}{2 \sin \frac{180^\circ}{n}}
$$

The apothem ($r$) can be expressed as:

$$
r = \frac{a}{2 \tan \frac{180^\circ}{n}}
$$

---

### **III. Graphs**

A **graph** consists of a finite set of points, called **vertices** (or nodes), and a set of **edges** (or arcs) that connect pairs of vertices.

Graphs are used to represent relationships and connections between objects.

**Types of graphs:**

* **Simple graph:** No loops (edges connecting a vertex to itself) and no multiple edges between the same pair of vertices.
* **Multigraph:** May have multiple edges between the same pair of vertices.
* **Directed graph (digraph):** The edges have a direction; they are ordered pairs of vertices.

**Degree of a vertex:**
The number of edges incident to the vertex (for directed graphs, distinguish in-degree and out-degree).

**Connected graph:**
A graph is connected if there is a path between any two vertices.

**Complete graph:**
A graph in which every pair of vertices is connected by an edge.

**Cycle:**
A sequence of edges that starts and ends at the same vertex, with all vertices and edges distinct (except for the start/end vertex).

**Tree:**
A connected graph with no cycles.

**Planar graph:**
A graph that can be drawn on the plane without edges crossing.

---

### **IV. Applications**

Convex and regular polygons are important in geometry, architecture, art, and nature (for example, honeycomb structures).

Graphs have a wide range of applications in computer science, network theory, transportation, biology, and social sciences, as they model relationships and connections.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 17** (“The Circle and Its Parts. Inscribed Angle, Central Angle, Angle of View. Cyclic Quadrilaterals, Tangential Quadrilaterals”) from your mathematics oral matura document. The translation preserves the original structure, terminology, and all formulas, with nothing omitted or summarized. If you require diagrams or original formatting from the PDF, please specify the page and I will provide them.

---

## 17. Topic: The Circle and Its Parts. Inscribed Angle, Central Angle, Angle of View. Cyclic Quadrilaterals, Tangential Quadrilaterals.

---

### **I. The Circle and Its Parts**

A **circle** is the set of all points in a plane that are at a given distance (called the radius) from a fixed point (called the center).

* The **radius** ($r$) is the distance from the center to any point on the circle.
* The **diameter** ($d$) is the segment passing through the center with endpoints on the circle; its length is $d = 2r$.
* A **chord** is a segment with both endpoints on the circle.
* A **secant** is a line that intersects the circle in two points.
* A **tangent** is a line that touches the circle at exactly one point.
* An **arc** is a part of the circle between two points.
* A **sector** is a region bounded by two radii and the arc between them.
* A **segment of a circle** is a region bounded by a chord and the corresponding arc.

---

### **II. Central Angle, Inscribed Angle, Angle of View**

* A **central angle** is an angle whose vertex is at the center of the circle and whose sides pass through two points on the circle.

  * The measure of a central angle is equal to the measure of the arc it intercepts.

* An **inscribed angle** is an angle whose vertex is on the circle and whose sides pass through two other points on the circle.

  * The measure of an inscribed angle is half the measure of the intercepted arc.

  $$
  \text{If } \alpha \text{ is the inscribed angle and } \beta \text{ is the central angle subtending the same arc:}
  $$

  $$
  \alpha = \frac{\beta}{2}
  $$

* The **angle of view** (apparent angle) from a given point to a segment or an arc is the angle under which the segment or arc is seen from that point.

---

### **III. Properties and Theorems Related to Angles**

* The measure of the angle subtended by a chord (not passing through the center) is equal to half the measure of the central angle subtending the same chord.
* Angles inscribed in the same arc are equal.
* The sum of the measures of opposite angles of a cyclic quadrilateral is $180^\circ$.

---

### **IV. Cyclic Quadrilaterals**

A **cyclic quadrilateral** is a quadrilateral whose vertices all lie on a single circle.

* **Property:** The sum of the measures of the opposite angles of a cyclic quadrilateral is $180^\circ$:

  $$
  \alpha + \gamma = 180^\circ, \quad \beta + \delta = 180^\circ
  $$

* **Theorem (Ptolemy's Theorem):** In a cyclic quadrilateral, the product of the lengths of the diagonals is equal to the sum of the products of the lengths of the two pairs of opposite sides:

  $$
  AC \cdot BD = AB \cdot CD + AD \cdot BC
  $$

---

### **V. Tangential Quadrilaterals**

A **tangential quadrilateral** is a quadrilateral for which a circle can be inscribed so that it is tangent to all four sides.

* **Property:** In a tangential quadrilateral, the sums of the lengths of the pairs of opposite sides are equal:

  $$
  a + c = b + d
  $$

  where $a, b, c, d$ are the side lengths in order.

---

### **VI. Applications**

The properties of circles, angles, cyclic and tangential quadrilaterals are fundamental in geometry, constructions, and problem solving.

They are widely used in mathematics, engineering, physics, and design.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 18** (“Vectors, Vector Operations. Vector Decomposition Theorem. Coordinates of Vectors. Scalar Product”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content, including all formulas, without omitting or summarizing anything. If you require diagrams or layouts from the PDF, please specify the page and I will provide them.

---

## 18. Topic: Vectors, Vector Operations. Vector Decomposition Theorem. Coordinates of Vectors. Scalar Product.

---

### **I. Vectors**

A **vector** is a quantity that has both magnitude (length) and direction.

A vector in the plane is represented by a directed line segment from point $A$ to point $B$, denoted as $\vec{AB}$.

The starting point is called the **origin** or **tail**, and the endpoint is called the **end** or **head** of the vector.

The length of the vector $\vec{AB}$ is the distance between $A$ and $B$.

---

### **II. Vector Operations**

#### **1. Vector Addition**

The sum of two vectors $\vec{a}$ and $\vec{b}$ is the vector $\vec{a} + \vec{b}$, which can be constructed by placing the tail of $\vec{b}$ at the head of $\vec{a}$.
The vector from the tail of $\vec{a}$ to the head of $\vec{b}$ is the sum.

Vector addition is **commutative**: $\vec{a} + \vec{b} = \vec{b} + \vec{a}$.

Vector addition is **associative**: $(\vec{a} + \vec{b}) + \vec{c} = \vec{a} + (\vec{b} + \vec{c})$.

#### **2. Scalar Multiplication**

If $\lambda$ is a real number (scalar) and $\vec{a}$ is a vector, then $\lambda \vec{a}$ is a vector in the same direction as $\vec{a}$ if $\lambda > 0$, in the opposite direction if $\lambda < 0$, and has magnitude $|\lambda|$ times that of $\vec{a}$.

#### **3. Vector Subtraction**

The difference $\vec{a} - \vec{b}$ is defined as $\vec{a} + (-\vec{b})$, where $-\vec{b}$ is the vector with the same magnitude as $\vec{b}$ but opposite direction.

---

### **III. Vector Decomposition Theorem**

Any vector $\vec{a}$ in the plane can be uniquely written as the sum of two vectors along given, non-parallel directions.

For example, if $\vec{e}_1$ and $\vec{e}_2$ are two non-parallel vectors (basis vectors), then there exist unique real numbers $x$ and $y$ such that:

$$
\vec{a} = x \vec{e}_1 + y \vec{e}_2
$$

This is called the **vector decomposition theorem**.

---

### **IV. Coordinates of Vectors**

Let the origin of the coordinate system be $O(0, 0)$.

Let $\vec{a}$ be the vector from $A(x_1, y_1)$ to $B(x_2, y_2)$.

The **components** (coordinates) of the vector $\vec{AB}$ are:

$$
\vec{AB} = (x_2 - x_1, \; y_2 - y_1)
$$

The **magnitude** (length) of the vector $\vec{a} = (a_1, a_2)$ is:

$$
|\vec{a}| = \sqrt{a_1^2 + a_2^2}
$$

---

### **V. Scalar Product (Dot Product)**

The **scalar product** (dot product) of two vectors $\vec{a} = (a_1, a_2)$ and $\vec{b} = (b_1, b_2)$ is defined as:

$$
\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2
$$

Alternatively, if the angle between $\vec{a}$ and $\vec{b}$ is $\varphi$, then:

$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos \varphi
$$

**Properties:**

* The scalar product is **commutative**: $\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$.
* If $\vec{a} \cdot \vec{b} = 0$, then the vectors are perpendicular.
* The scalar product of a vector with itself is the square of its length: $\vec{a} \cdot \vec{a} = |\vec{a}|^2$.

---

### **VI. Applications**

Vectors and their operations are widely used in mathematics, physics (e.g., forces, velocities, accelerations), engineering, computer graphics, and many other sciences.

Vector decomposition is essential in solving problems involving movement, force systems, and coordinate geometry.

The scalar product is used to compute angles between vectors, to determine orthogonality (perpendicularity), and to calculate projections.

---
Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 19** (“Segments and Lines in the Coordinate Plane. Parallel and Perpendicular Lines. Graphical Solution of First-Degree Inequalities and Systems of Equations”) from your mathematics oral matura document. The translation preserves the original mathematical structure, terminology, and all formulas, with nothing omitted or summarized. If you require diagrams or the original layout from the PDF, please specify the page and I will provide them.

---

## 19. Topic: Segments and Lines in the Coordinate Plane. Parallel and Perpendicular Lines. Graphical Solution of First-Degree Inequalities and Systems of Equations.

---

### **I. Segments and Lines in the Coordinate Plane**

A **segment** is a part of a straight line that is bounded by two endpoints.

If the endpoints of the segment are $A(x_1, y_1)$ and $B(x_2, y_2)$, then the length of the segment $AB$ is:

$$
|AB| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
$$

The **midpoint** of segment $AB$ has coordinates:

$$
M \left( \frac{x_1 + x_2}{2},\; \frac{y_1 + y_2}{2} \right)
$$

A **line** in the plane can be given in several forms:

* **General form:**

  $$
  ax + by + c = 0
  $$

  where $a, b, c \in \mathbb{R}$, $a$ and $b$ are not both zero.

* **Slope-intercept form:**

  $$
  y = mx + b
  $$

  where $m$ is the slope of the line and $b$ is the $y$-intercept.

* **Point-slope form:**

  $$
  y - y_1 = m(x - x_1)
  $$

  where $(x_1, y_1)$ is a point on the line.

The **slope** of the line (if $b \neq 0$) is:

$$
m = -\frac{a}{b}
$$

---

### **II. Parallel and Perpendicular Lines**

* Two lines are **parallel** if their slopes are equal ($m_1 = m_2$), or if the ratios $\frac{a_1}{a_2} = \frac{b_1}{b_2}$ (provided both denominators are not zero).

* Two lines are **perpendicular** if the product of their slopes is $-1$ ($m_1 \cdot m_2 = -1$), or if $a_1 a_2 + b_1 b_2 = 0$.

---

### **III. Graphical Solution of First-Degree Inequalities**

A **first-degree inequality** in two variables has the form:

$$
ax + by + c < 0 \quad \text{or} \quad ax + by + c > 0
$$

The corresponding equation ($ax + by + c = 0$) represents a line in the plane, which divides the plane into two half-planes.

* The solution set of the inequality is the set of points in the half-plane for which the inequality holds.
* If the inequality is non-strict ($\leq$ or $\geq$), then the boundary line is included in the solution set.

To determine which side of the line to shade, substitute the coordinates of a test point (e.g., the origin, if it is not on the line) into the inequality.

---

### **IV. Graphical Solution of Systems of Linear Equations and Inequalities**

A **system of linear equations** corresponds to two or more lines in the plane.

* The solution of the system is the set of points where all the equations are satisfied simultaneously, i.e., the intersection points of the corresponding lines.

A **system of linear inequalities** corresponds to the intersection of the half-planes defined by each inequality.

* The solution set is the region of the plane where all inequalities are satisfied at once.

**Graphical solution steps:**

1. Draw the boundary lines for each equation or inequality.
2. Shade the solution half-planes for inequalities.
3. The solution set is the intersection of all shaded regions.

---

### **V. Applications**

Segments and lines in the coordinate plane are fundamental in geometry, analytic geometry, engineering, and computer graphics.

The concepts of parallelism and perpendicularity are widely used in constructions, design, and problem solving.

Graphical solutions of equations and inequalities are essential in optimization, linear programming, and economics.

---

Certainly! Here is a **precise, sentence-by-sentence English translation of Topic 20** (“The Circle and the Parabola by Elementary Methods and in the Coordinate Plane. Mutual Positions of Circle and Line, Parabola and Line. Graphical Solution of Quadratic Inequalities”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content exactly, with all formulas and no omission or summarization. If you require diagrams or layouts as in the PDF, please specify the page and I will provide them.

---

## 20. Topic: The Circle and the Parabola by Elementary Methods and in the Coordinate Plane. Mutual Positions of Circle and Line, Parabola and Line. Graphical Solution of Quadratic Inequalities.

---

### **I. The Circle by Elementary Methods and in the Coordinate Plane**

A **circle** is the set of all points in a plane that are at a fixed distance (radius) from a given point (center).

The **standard equation of a circle** with center $O(a, b)$ and radius $r$ in the coordinate plane is:

$$
(x - a)^2 + (y - b)^2 = r^2
$$

If the center is at the origin ($O(0, 0)$), the equation is:

$$
x^2 + y^2 = r^2
$$

---

### **II. The Parabola by Elementary Methods and in the Coordinate Plane**

A **parabola** is the set of all points in a plane that are equidistant from a fixed point (the focus) and a fixed line (the directrix).

The **standard equation of a parabola** with its vertex at the origin and its axis along the $y$-axis is:

$$
y = a x^2
$$

where $a \neq 0$.

* If $a > 0$, the parabola opens upward.
* If $a < 0$, the parabola opens downward.

A more general equation:

$$
y = a x^2 + b x + c
$$

The **vertex** of the parabola is at the point:

$$
\left( -\frac{b}{2a},\; c - \frac{b^2}{4a} \right)
$$

---

### **III. Mutual Position of Circle and Line**

The relative position of a line and a circle in the plane depends on the distance ($d$) from the center of the circle to the line.

* **The line and the circle do not intersect** if $d > r$.
* **The line is tangent to the circle** if $d = r$.
* **The line intersects the circle in two points** if $d < r$.

To find the points of intersection, substitute the equation of the line into the equation of the circle and solve the resulting quadratic equation.

---

### **IV. Mutual Position of Parabola and Line**

The mutual position of a line and a parabola depends on the number of solutions to the system of their equations.

* The line does not intersect the parabola if the quadratic equation has no real roots.
* The line is tangent to the parabola if the quadratic equation has one real root (double root).
* The line intersects the parabola in two points if the quadratic equation has two real roots.

The **discriminant** ($D$) of the quadratic equation determines the number of intersection points:

* If $D > 0$: Two intersection points.
* If $D = 0$: The line is tangent to the parabola.
* If $D < 0$: No intersection points.

---

### **V. Graphical Solution of Quadratic Inequalities**

A **quadratic inequality** in one variable has the general form:

$$
a x^2 + b x + c < 0 \\
a x^2 + b x + c > 0 \\
a x^2 + b x + c \leq 0 \\
a x^2 + b x + c \geq 0
$$

To solve the inequality graphically:

1. Draw the graph of the quadratic function $y = a x^2 + b x + c$.
2. Determine the intervals on the $x$-axis where the graph is above (for $> 0$, $\geq 0$) or below (for $< 0$, $\leq 0$) the $x$-axis.
3. The solution set consists of those $x$-values for which the inequality is satisfied.

The roots of the quadratic equation ($a x^2 + b x + c = 0$) are the boundary points between the intervals.

---

### **VI. Applications**

Circles and parabolas are fundamental curves in mathematics and its applications.

They appear in geometry, physics (projectile motion), engineering (reflectors, satellite dishes), and many other fields.

Graphical solutions of quadratic inequalities are essential in optimization, economics, and for interpreting the feasible region in various problems.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 21** (“Distances and Angles of Spatial Elements. Spatial Figures. Surface Area and Volume Calculation”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content, including all formulas, without omitting or summarizing anything. If you require diagrams or original formatting from the PDF, please specify the page and I will provide them.

---

## 21. Topic: Distances and Angles of Spatial Elements. Spatial Figures. Surface Area and Volume Calculation.

---

### **I. Distances and Angles of Spatial Elements**

#### **1. Distance between Two Points**

In space, the distance between points $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$ is:

$$
|AB| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}
$$

---

#### **2. Distance from a Point to a Line**

The distance from point $P$ to line $e$ is the length of the perpendicular segment from $P$ to $e$.

If the line passes through point $A$ and has direction vector $\vec{v}$, and $P$ is the external point, then:

$$
d = \frac{|\vec{AP} \times \vec{v}|}{|\vec{v}|}
$$

where $\times$ denotes the vector (cross) product.

---

#### **3. Distance from a Point to a Plane**

The distance from point $P(x_0, y_0, z_0)$ to the plane $ax + by + cz + d = 0$ is:

$$
d = \frac{|a x_0 + b y_0 + c z_0 + d|}{\sqrt{a^2 + b^2 + c^2}}
$$

---

#### **4. Angle between Two Lines**

The angle between two lines is the angle between their direction vectors.

If the direction vectors are $\vec{v_1}$ and $\vec{v_2}$, then the cosine of the angle $\varphi$ between them is:

$$
\cos \varphi = \frac{|\vec{v_1} \cdot \vec{v_2}|}{|\vec{v_1}| \cdot |\vec{v_2}|}
$$

where $\cdot$ denotes the scalar product.

---

#### **5. Angle between a Line and a Plane**

The angle between a line and a plane is the complement of the angle between the line’s direction vector and the plane’s normal vector.

Let the direction vector of the line be $\vec{v}$, and the normal vector of the plane be $\vec{n}$:

$$
\sin \alpha = \frac{|\vec{v} \cdot \vec{n}|}{|\vec{v}| \cdot |\vec{n}|}
$$

where $\alpha$ is the angle between the line and the plane.

---

#### **6. Angle between Two Planes**

The angle between two planes is the angle between their normal vectors.

If the normal vectors are $\vec{n_1}$ and $\vec{n_2}$, then:

$$
\cos \varphi = \frac{|\vec{n_1} \cdot \vec{n_2}|}{|\vec{n_1}| \cdot |\vec{n_2}|}
$$

---

### **II. Spatial Figures**

**1. Prism:**
A polyhedron with two congruent, parallel bases and rectangular lateral faces.

**2. Pyramid:**
A polyhedron with a polygonal base and triangular lateral faces meeting at a common point (the apex).

**3. Cylinder:**
A solid with two parallel, congruent circular bases connected by a curved surface.

**4. Cone:**
A solid with a circular base and a curved surface connecting the base to a single point (the apex).

**5. Sphere:**
The set of all points in space at a given distance (radius) from a fixed point (the center).

---

### **III. Surface Area and Volume Calculation**

#### **Prism (with base area $T$, height $m$):**

* Surface area:

  $$
  A = 2T + P \cdot m
  $$

  where $P$ is the perimeter of the base.
* Volume:

  $$
  V = T \cdot m
  $$

---

#### **Pyramid (with base area $T$, height $m$):**

* Surface area:

  $$
  A = T + A_{\text{lateral}}
  $$
* Volume:

  $$
  V = \frac{1}{3} T m
  $$

---

#### **Cylinder (with base radius $r$, height $m$):**

* Lateral surface area:

  $$
  A_{\text{lateral}} = 2\pi r m
  $$
* Total surface area:

  $$
  A = 2\pi r m + 2\pi r^2
  $$
* Volume:

  $$
  V = \pi r^2 m
  $$

---

#### **Cone (with base radius $r$, height $m$, slant height $l$):**

* Lateral surface area:

  $$
  A_{\text{lateral}} = \pi r l
  $$
* Total surface area:

  $$
  A = \pi r l + \pi r^2
  $$
* Volume:

  $$
  V = \frac{1}{3} \pi r^2 m
  $$

---

#### **Sphere (with radius $r$):**

* Surface area:

  $$
  A = 4\pi r^2
  $$
* Volume:

  $$
  V = \frac{4}{3} \pi r^3
  $$

---

### **IV. Applications**

The calculation of distances and angles in space is essential in geometry, physics, engineering, architecture, and computer graphics.

The formulas for the surface area and volume of solids are widely used in practice, for example in material estimation, design, and measurement.

Understanding spatial figures and their properties is fundamental for solving three-dimensional geometric problems.

---
Certainly! Here is a **precise, sentence-by-sentence English translation of Topic 22** (“Calculation of Area by Elementary Methods and Using Integral Calculus”) from your mathematics oral matura document. The translation strictly follows the original structure, terminology, and mathematical content, including all formulas, with nothing omitted or summarized. If you need diagrams or the original layout from the PDF, please specify the page and I will provide them.

---

## 22. Topic: Calculation of Area by Elementary Methods and Using Integral Calculus.

---

### \*\*I. Calculation of Area by Elementary Methods

The **area** is a measure of the extent of a region on the plane.

The area is always a non-negative number.

#### **Area of Basic Plane Figures**

* **Rectangle:**
  Area = base × height

  $$
  A = a \cdot b
  $$

* **Square:**
  Area = side squared

  $$
  A = a^2
  $$

* **Parallelogram:**
  Area = base × height

  $$
  A = a \cdot m_a
  $$

  where $a$ is the base, $m_a$ is the height corresponding to base $a$.

* **Triangle:**
  Area = (base × height) / 2

  $$
  A = \frac{a \cdot m_a}{2}
  $$

* **Trapezoid:**
  Area = (sum of bases × height) / 2

  $$
  A = \frac{(a + c) \cdot m}{2}
  $$

  where $a, c$ are the bases, $m$ is the height.

* **Circle:**
  Area = π × radius squared

  $$
  A = \pi r^2
  $$

* **Sector of a circle:**
  Area = (angle/360°) × π × radius squared

  $$
  A = \frac{\alpha}{360^\circ} \cdot \pi r^2
  $$

  where $\alpha$ is the central angle in degrees.

---

### **II. Calculation of Area Using Integral Calculus**

For more complicated plane figures, the area can be calculated using definite integrals.

#### **Area Bounded by the Graph of a Function and the $x$-Axis**

Let $f(x)$ be a continuous function on $[a, b]$.

The area between the graph of $f(x)$, the $x$-axis, and the vertical lines $x = a$ and $x = b$ is:

$$
A = \int_a^b |f(x)|\,dx
$$

If $f(x) \geq 0$ on $[a, b]$, then:

$$
A = \int_a^b f(x)\,dx
$$

#### **Area Between Two Curves**

If $f(x) \geq g(x)$ for all $x$ in $[a, b]$, then the area between the graphs of $f(x)$ and $g(x)$ over $[a, b]$ is:

$$
A = \int_a^b (f(x) - g(x))\,dx
$$

#### **Approximation Using Riemann Sums**

The definite integral can be interpreted as the limit of the sum of the areas of thin rectangles under the curve (Riemann sum):

$$
\int_a^b f(x)\,dx = \lim_{n \to \infty} \sum_{i=1}^n f(x_i^*) \Delta x
$$

where $\Delta x = \frac{b - a}{n}$, and $x_i^*$ is a sample point in the $i$-th subinterval.

---

### **III. Applications**

Elementary area formulas are used to calculate the area of basic plane figures.

Integral calculus allows us to find the area of more complex, curved regions and is fundamental in mathematics, physics, engineering, and many applied sciences.

---
Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 23** (“Combinations. The Binomial Theorem, Pascal’s Triangle. The Combinatorial Model of Probability Calculation. The Hypergeometric Distribution”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content, including all formulas, with nothing omitted or summarized. If you require diagrams, tables, or original formatting from the PDF, please specify the page and I will provide them.

---

## 23. Topic: Combinations. The Binomial Theorem, Pascal’s Triangle. The Combinatorial Model of Probability Calculation. The Hypergeometric Distribution.

---

### **I. Combinations**

A **combination** is a selection of elements from a set, where the order does not matter.

The number of ways to choose $k$ elements from a set of $n$ elements is given by the binomial coefficient:

$$
\binom{n}{k} = \frac{n!}{k! \, (n - k)!}
$$

where $n! = n \cdot (n-1) \cdot \ldots \cdot 2 \cdot 1$, $k \leq n$, $n, k \in \mathbb{N}_0$.

* $\binom{n}{0} = 1$
* $\binom{n}{n} = 1$

---

### **II. The Binomial Theorem**

The **binomial theorem** gives the expansion of the power of a binomial:

$$
(a + b)^n = \sum_{k=0}^n \binom{n}{k} a^{n-k} b^k
$$

That is,

$$
(a + b)^n = \binom{n}{0} a^n + \binom{n}{1} a^{n-1} b + \ldots + \binom{n}{n} b^n
$$

The coefficients $\binom{n}{k}$ are called **binomial coefficients**.

---

### **III. Pascal’s Triangle**

**Pascal’s triangle** is a triangular array of binomial coefficients.

Each number in Pascal’s triangle is the sum of the two numbers directly above it.

$$
\begin{array}{cccccccccc}
    &&&&& 1 \\
    &&&& 1 && 1 \\
    &&& 1 && 2 && 1 \\
    && 1 && 3 && 3 && 1 \\
    & 1 && 4 && 6 && 4 && 1 \\
    \ldots
\end{array}
$$

The $n$-th row contains the coefficients for the expansion of $(a + b)^n$.

---

### **IV. The Combinatorial Model of Probability Calculation**

In the **classical model of probability**, if an experiment has $n$ equally likely outcomes, and event $A$ can occur in $k$ ways, then:

$$
P(A) = \frac{k}{n}
$$

Combinatorial enumeration (counting) is used to determine $k$ and $n$.

* For combinations: the number of possible selections is $\binom{n}{k}$.

---

### **V. The Hypergeometric Distribution**

The **hypergeometric distribution** gives the probability of obtaining exactly $k$ successes in $n$ draws, *without replacement*, from a finite population of $N$ elements, of which $M$ are successes.

The probability is:

$$
P(X = k) = \frac{\binom{M}{k} \binom{N-M}{n-k}}{\binom{N}{n}}
$$

where:

* $N$: total number of elements,
* $M$: number of successes in the population,
* $n$: number of draws,
* $k$: number of observed successes.

---

### **VI. Applications**

Combinatorial calculations are fundamental in probability, statistics, and many fields of science and engineering.

The binomial theorem is essential in algebra and combinatorics.

The hypergeometric distribution models random selection without replacement, for example in quality control, lottery, and genetics.

---
Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 24** (“Permutations, Variations. The Binomial Distribution. The Geometric Model of Probability Calculation”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content, including all formulas, with nothing omitted or summarized. If you require diagrams, tables, or the original layout from the PDF, please specify the page and I will provide them.

---

## 24. Topic: Permutations, Variations. The Binomial Distribution. The Geometric Model of Probability Calculation.

---

### **I. Permutations**

A **permutation** is an arrangement of all the elements of a set in a specific order.

The number of permutations of $n$ distinct elements is:

$$
P_n = n!
$$

where $n! = n \cdot (n-1) \cdot (n-2) \cdot \ldots \cdot 2 \cdot 1$.

If there are $n$ elements, of which $k_1$ are alike, $k_2$ are alike, ..., $k_m$ are alike (and $k_1 + k_2 + \ldots + k_m = n$), the number of distinct permutations is:

$$
P = \frac{n!}{k_1! \cdot k_2! \cdot \ldots \cdot k_m!}
$$

---

### **II. Variations (Arrangements)**

A **variation** is an ordered selection of $k$ elements from a set of $n$ elements.

* **Variations without repetition:**

  $$
  V_n^k = n \cdot (n-1) \cdot (n-2) \cdot \ldots \cdot (n-k+1) = \frac{n!}{(n-k)!}
  $$

* **Variations with repetition:**

  $$
  V_n^{k,\,r} = n^k
  $$

  (Here, each element can be chosen more than once.)

---

### **III. The Binomial Distribution**

The **binomial distribution** gives the probability of obtaining exactly $k$ successes in $n$ independent Bernoulli trials, each with probability $p$ of success.

The probability is:

$$
P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}
$$

where:

* $n$: number of trials,
* $k$: number of successes ($0 \leq k \leq n$),
* $p$: probability of success in a single trial,
* $\binom{n}{k}$: binomial coefficient.

The sum of the probabilities over all possible values of $k$ is 1.

The binomial distribution models the number of successes in repeated, independent experiments with two possible outcomes.

---

### **IV. The Geometric Model of Probability Calculation**

In the **geometric probability model**, the set of possible outcomes is represented as points in a geometric figure (interval, area, volume).

If all points in the figure are equally likely, the probability of event $A$ is:

$$
P(A) = \frac{\text{measure of the set corresponding to } A}{\text{measure of the whole sample space}}
$$

Depending on the context, the measure can be length, area, or volume.

---

### **V. Applications**

Permutations and variations are fundamental in combinatorics, probability, cryptography, coding, and scheduling problems.

The binomial distribution is widely used in statistics, quality control, biology, and finance.

The geometric probability model is applied in physics, engineering, and everyday problems involving random selection from continuous sets.

---

Absolutely! Here is a **precise, sentence-by-sentence English translation of Topic 25** (“Proof Methods and Their Presentation in Mathematical Theorems”) from your mathematics oral matura document. The translation follows the original structure, terminology, and mathematical content exactly, including all formulas, with nothing omitted or summarized. If you require diagrams or the original layout from the PDF, please specify the page and I will provide them.

---

## 25. Topic: Proof Methods and Their Presentation in Mathematical Theorems

---

### **I. The Concept of Proof**

A **proof** is a logical process that demonstrates the truth of a mathematical statement, based on previously accepted facts (axioms, definitions, already proven theorems).

The main purpose of a proof is to show, step by step, why a statement is true.

A proof must be clear, logically correct, and convincing.

---

### **II. Direct Proof**

In a **direct proof**, we start from the given assumptions (premises) and, through a sequence of logical steps, arrive at the conclusion.

**Example:**
Prove: The sum of two even numbers is even.

**Proof:**
Let the two even numbers be $2k$ and $2l$, where $k, l \in \mathbb{Z}$.
Their sum: $2k + 2l = 2(k + l)$, which is even, since $k + l$ is an integer.

---

### **III. Proof by Contrapositive**

The **contrapositive** of the statement "If $A$, then $B$" is "If not $B$, then not $A$".

A statement and its contrapositive are logically equivalent.

**Proof by contrapositive** means we prove the contrapositive statement instead of the original.

**Example:**
Prove: If $n^2$ is even, then $n$ is even.

**Proof:**
Contrapositive: If $n$ is odd, then $n^2$ is odd.
If $n = 2k + 1$ ($k \in \mathbb{Z}$), then $n^2 = (2k + 1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1$, which is odd.

---

### **IV. Proof by Contradiction (Indirect Proof)**

In **proof by contradiction**, we assume that the statement we want to prove is false, and show that this leads to a contradiction (an impossibility).

**Example:**
Prove: $\sqrt{2}$ is irrational.

**Proof:**
Suppose the contrary, that $\sqrt{2}$ is rational.
Then $\sqrt{2} = \frac{p}{q}$ in lowest terms, with $p, q$ integers, $q \neq 0$, and $\gcd(p, q) = 1$.
Then $2 = \frac{p^2}{q^2} \implies p^2 = 2q^2$.
So $p^2$ is even, so $p$ is even, so $p = 2k$.
Then $(2k)^2 = 4k^2 = 2q^2 \implies q^2 = 2k^2$, so $q^2$ is even, so $q$ is even.
Thus both $p$ and $q$ are even, contradicting $\gcd(p, q) = 1$.

---

### **V. Proof by Mathematical Induction**

**Mathematical induction** is a method used to prove statements about all natural numbers (or about infinitely many cases).

The method has two main steps:

1. **Base Case:** Prove the statement is true for the initial value (usually $n = 1$ or $n = 0$).
2. **Inductive Step:** Assume the statement is true for $n = k$ (inductive hypothesis), and show it is true for $n = k+1$.

If both steps are valid, the statement is true for all $n$ in the domain.

**Example:**
Prove that $1 + 2 + \ldots + n = \frac{n(n+1)}{2}$ for all $n \geq 1$.

**Proof:**

* **Base Case ($n = 1$)**: $1 = \frac{1 \cdot 2}{2} = 1$, true.
* **Inductive Step:**
  Assume true for $n = k$: $1 + 2 + \ldots + k = \frac{k(k+1)}{2}$.
  For $n = k+1$:
  $1 + 2 + \ldots + k + (k+1) = \frac{k(k+1)}{2} + (k+1) = \frac{k(k+1) + 2(k+1)}{2} = \frac{(k+1)(k+2)}{2}$, as required.

---

### **VI. Constructive and Non-Constructive Proofs**

A **constructive proof** provides a method or example for constructing an object that meets the required conditions.

A **non-constructive proof** shows the existence of an object without necessarily providing a way to construct it.

---

### **VII. Proofs in Theorems**

In mathematics, theorems are often formulated with conditions and conclusions, and proofs must justify the conclusion from the assumptions.

Proofs use the rules of logic and previously established results.

Proofs can be presented in words, using mathematical symbols and formulas, or with diagrams and figures as needed.

---

### **VIII. Applications**

Proof methods are fundamental to mathematics.

They are necessary in all areas of mathematics for verifying the correctness of statements, and they ensure the reliability and consistency of mathematical results.

---
