

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

## **Topic 3: The Concept of a Function. Representations and Properties of Functions. Types of Functions.**

---

### **Definition and Basic Concepts**

> **D:** A **function** (or mapping) from set `A` to set `B` is a relation that assigns *exactly one* element of `B` to each element of `A`.
> Notation: `f: A → B`
> The **domain** is `A`, the **codomain** is `B`, and `f(a)` denotes the value assigned to `a ∈ A`.

The **range** or **image** of the function is the set of all values `f(a)` for `a ∈ A`.
Notation: `f(A) = {f(a) | a ∈ A}`

In secondary school, we usually work with **real-valued functions of one real variable**, i.e., `f: ℝ → ℝ`.

A function can be defined in several ways:

* **Analytically**: using an algebraic expression (e.g., `f(x) = 2x + 3`)
* **Graphically**: via its graph
* **Table**: especially for discrete domains
* **Verbal description**: e.g., “the square of a number”

---

### **Representation**

The most common representation of a function is by **graphing in a coordinate system**:

> **D:** The **graph** of a function `f` is the set of ordered pairs:
> `G(f) = {(x, f(x)) | x ∈ Dom(f)}`
> This is a set of points in the Cartesian plane.

To determine whether a graph represents a function, we use:

> **Vertical Line Test:** A curve in the plane is the graph of a function if no vertical line intersects it more than once.

---

### **Properties of Functions**

Let `f: A → ℝ` be a real-valued function.

1. **Domain**: the set of `x` values for which the function is defined.
2. **Range**: the set of possible output values `f(x)`.
3. **Zeros**: `f(x) = 0`
4. **Sign**: Where the function is positive, negative, or zero.
5. **Monotonicity**:

   * **Increasing**: `f(x₁) ≤ f(x₂)` whenever `x₁ < x₂`
   * **Decreasing**: `f(x₁) ≥ f(x₂)` whenever `x₁ < x₂`
   * **Strictly** increasing or decreasing if inequalities are strict.
6. **Extrema**:

   * **Local maximum** at `x₀` if `f(x₀) ≥ f(x)` for values of `x` near `x₀`
   * **Local minimum** at `x₀` if `f(x₀) ≤ f(x)` for values of `x` near `x₀`
   * **Global max/min** if the inequality holds for all `x ∈ Dom(f)`
7. **Periodicity**:

   * `f(x + p) = f(x)` for all `x`, `p ≠ 0`: the function is **periodic** with period `p`
8. **Parity**:

   * **Even** function: `f(-x) = f(x)` (symmetric to the y-axis)
   * **Odd** function: `f(-x) = -f(x)` (symmetric about the origin)
9. **Continuity**:

   * A function is **continuous** at a point `x₀` if `limₓ→ₓ₀ f(x) = f(x₀)`
10. **Asymptotes**:

    * **Vertical** at `x = a` if `limₓ→ₐ f(x) = ±∞`
    * **Horizontal** at `y = b` if `limₓ→∞ f(x) = b` or `limₓ→−∞ f(x) = b`
    * **Oblique (slant)** if `f(x) ≈ mx + b` as `x → ∞`

---

### **Types of Functions**

Let us examine **basic function types** frequently encountered in school mathematics:

#### **Constant Function**

`f(x) = c`

* Graph: horizontal line
* Properties: even, continuous, bounded, not invertible

#### **Identity Function**

`f(x) = x`

* Graph: line through origin at 45°
* Properties: odd, increasing, continuous, invertible

#### **Linear Function**

`f(x) = mx + b`

* Graph: line with slope `m`, y-intercept `b`
* Properties:

  * If `m > 0`: increasing
  * If `m < 0`: decreasing
  * Continuous, invertible

#### **Quadratic Function**

`f(x) = ax² + bx + c`

* Graph: parabola
* Vertex at: `x = -b/2a`
* Axis of symmetry: `x = -b/2a`
* Direction: opens upward if `a > 0`, downward if `a < 0`
* Properties: even if `b = 0`; bounded if `a > 0`

#### **Absolute Value Function**

`f(x) = |x|`

* Graph: V-shaped
* Properties:

  * Even
  * Not differentiable at 0
  * Minimum at 0

#### **Square Root Function**

`f(x) = √x`

* Domain: `x ≥ 0`
* Graph: half parabola sideways
* Properties: increasing, not even/odd, not defined for negatives

#### **Reciprocal Function**

`f(x) = 1/x`

* Domain: `x ≠ 0`
* Graph: two hyperbola branches
* Properties: odd, asymptotes at `x = 0` and `y = 0`, not bounded

#### **Cubic Function**

`f(x) = x³`

* Graph: S-shaped curve
* Properties: odd, increasing, continuous, invertible

#### **Step Function (Floor Function)**

`f(x) = ⌊x⌋`

* Rounds down to nearest integer
* Graph: horizontal segments with open and closed endpoints
* Discontinuous at integers

#### **Sign Function**

`f(x) = sign(x)`

$$
f(x) = 
\begin{cases}
-1 & \text{if } x < 0 \\
0 & \text{if } x = 0 \\
1 & \text{if } x > 0
\end{cases}
$$

* Graph: three flat parts
* Properties: odd, discontinuous at 0

#### **Exponential Function**

`f(x) = a^x`, `a > 0`, `a ≠ 1`

* Properties: strictly positive, continuous, increasing if `a > 1`, decreasing if `0 < a < 1`
* Inverse: logarithmic function

#### **Logarithmic Function**

`f(x) = logₐ(x)`, `a > 0`, `a ≠ 1`

* Domain: `x > 0`
* Properties: increasing if `a > 1`, decreasing if `0 < a < 1`
* Inverse of the exponential function

#### **Trigonometric Functions**

* `sin(x)`, `cos(x)`: periodic with period `2π`, bounded
* `tan(x)`: vertical asymptotes at odd multiples of `π/2`, period `π`
* Properties:

  * `sin` and `tan` are odd
  * `cos` is even

---

### **Piecewise Functions**

> **D:** A function can be defined by different expressions over different parts of its domain.
> These are **piecewise-defined functions**.

Example:

$$
f(x) = 
\begin{cases}
x^2 & \text{if } x ≤ 0 \\
x + 1 & \text{if } x > 0
\end{cases}
$$

Analysis includes:

* Checking continuity at `x = 0`
* Identifying extrema, parity, etc.

---

### **Transformations of Functions**

Let `f(x)` be a base function. Then:

* **Vertical shift**: `f(x) + c`
* **Horizontal shift**: `f(x - c)`
* **Vertical stretch/shrink**: `a·f(x)`
* **Horizontal stretch/shrink**: `f(bx)`
* **Reflection over x-axis**: `-f(x)`
* **Reflection over y-axis**: `f(-x)`

Transformations are **composed** from inside-out:

1. Modify inside the function (`x`)
2. Then apply outside transformations

---

### **Applications**

Functions are used in every area of mathematics and applied fields:

* Physics (e.g., position vs. time)
* Economics (e.g., cost functions)
* Computer science (e.g., hash functions)
* Biology (e.g., growth models)

Understanding function behavior is critical for modeling, interpreting graphs, solving equations, and optimization.

---

**Note:**
In exam tasks, students may be asked to:

* Identify properties from a graph
* Sketch the graph from a formula
* Solve function-related problems
* Transform base functions


