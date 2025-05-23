

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

Here is the **precise English translation of Topic 4** from the uploaded Hungarian mathematics oral exam preparation document. The translation preserves the original structure, mathematical content, formulas, and definitions accurately and without omissions:

---

## **Topic 4: Operations with Functions, Function Transformations. Inverse Functions, Composite Functions. Monotonicity and Extremes of Functions.**

---

### **Basic Operations on Functions**

Let $f$ and $g$ be functions whose domains are subsets of $\mathbb{R}$.

> **D:** The **sum** of $f$ and $g$ is the function
>
> $$
> $$

(f + g)(x) = f(x) + g(x)
]

> defined on $D(f) \cap D(g)$.

> **D:** The **difference** of $f$ and $g$:
>
> $$
> $$

(f - g)(x) = f(x) - g(x)
]

> defined on $D(f) \cap D(g)$.

> **D:** The **product** of $f$ and $g$:
>
> $$
> $$

(f \cdot g)(x) = f(x) \cdot g(x)
]

> defined on $D(f) \cap D(g)$.

> **D:** The **quotient** of $f$ and $g$:
>
> $$
> $$

\left( \frac{f}{g} \right)(x) = \frac{f(x)}{g(x)} \quad \text{where } g(x) \neq 0
]

> defined on $D(f) \cap D(g) \setminus \{x : g(x) = 0\}$.

In school mathematics, we usually define **new functions** by applying these operations to known functions.

---

### **Function Transformations**

Let $f(x)$ be a given base function.

We can derive other functions by transforming $f$:

* **Vertical translation**: $f(x) + c$ (upward if $c > 0$, downward if $c < 0$)
* **Horizontal translation**: $f(x - c)$ (rightward if $c > 0$, leftward if $c < 0$)
* **Vertical scaling**: $a \cdot f(x)$ (stretch if $|a| > 1$, compress if $0 < |a| < 1$, reflect over x-axis if $a < 0$)
* **Horizontal scaling**: $f(bx)$ (compress if $|b| > 1$, stretch if $0 < |b| < 1$, reflect over y-axis if $b < 0$)
* **Reflection over the x-axis**: $-f(x)$
* **Reflection over the y-axis**: $f(-x)$

⚠️ Transformations should be applied in the following order:
**inside the function first** (horizontal), then **outside** (vertical).

**Example**:
Given $f(x) = x^2$, analyze $g(x) = -2(x - 3)^2 + 4$:

* shift right by 3
* scale vertically by 2
* reflect over x-axis
* shift up by 4

Graph these step-by-step starting from the base parabola.

---

### **Inverse Function**

> **D:** A function $f$ has an **inverse** if it is **bijective** (i.e., both **injective** and **surjective**).

> **D:** The **inverse function** of $f$, denoted $f^{-1}$, satisfies:

$$
f(f^{-1}(x)) = f^{-1}(f(x)) = x
$$

The graph of $f^{-1}$ is the **reflection** of the graph of $f$ across the **line $y = x$**.

**Procedure for finding an inverse**:

1. Write $y = f(x)$
2. Swap $x$ and $y$
3. Solve for $y$ to get $f^{-1}(x)$

**Example**:
$f(x) = 2x + 3$
→ $y = 2x + 3$
→ $x = 2y + 3$
→ $y = \frac{x - 3}{2}$
So, $f^{-1}(x) = \frac{x - 3}{2}$

**Note**: Not every function has an inverse on its entire domain!
If necessary, restrict the domain so that the function becomes injective.

---

### **Composite Function**

> **D:** Given $f: A \to B$ and $g: B \to C$, the **composition** of $g$ and $f$ is:

$$
(g \circ f)(x) = g(f(x))
$$

* The domain of $g \circ f$ is:

  $$
  \{ x \in D(f) : f(x) \in D(g) \}
  $$

**Example**:
Let $f(x) = x^2$, $g(x) = \sqrt{x}$
Then $(g \circ f)(x) = \sqrt{x^2} = |x|$

But $(f \circ g)(x) = (\sqrt{x})^2 = x$, defined only for $x \geq 0$

⚠️ **Composition is not commutative**: $f \circ g \ne g \circ f$

---

### **Monotonicity**

> **D:** A function $f$ is:

* **Increasing** on $I \subset \mathbb{R}$ if $x_1 < x_2 \Rightarrow f(x_1) \leq f(x_2)$
* **Decreasing** if $x_1 < x_2 \Rightarrow f(x_1) \geq f(x_2)$
* **Strictly increasing/decreasing** if the inequalities are strict.

A function can be:

* Monotonic on its whole domain
* Monotonic on specific intervals only

**How to analyze monotonicity**:

* Study the graph (slope)
* Analyze the sign of the **derivative** (at higher levels)

---

### **Extrema (Maximum and Minimum Values)**

> **D:** A function has a **local maximum** at $x_0$ if:

$$
\exists \varepsilon > 0: \forall x \in (x_0 - \varepsilon, x_0 + \varepsilon), f(x) \leq f(x_0)
$$

> **D:** A function has a **local minimum** at $x_0$ if:

$$
\exists \varepsilon > 0: \forall x \in (x_0 - \varepsilon, x_0 + \varepsilon), f(x) \geq f(x_0)
$$

> **D:** A **global maximum** or **minimum** satisfies the same inequality **for all** $x \in D(f)$

To determine extrema:

* Use **graphical analysis** at the secondary school level
* Look for **turning points**, **vertex** (e.g. parabolas), or endpoints

---

### **Applications**

Understanding these concepts is fundamental for:

* Analyzing function behavior
* Solving inequalities
* Sketching graphs
* Modeling real-world phenomena
* Optimization problems in economics, physics, engineering

---
Here is the **complete and precise English translation of Topic 5** from the oral exam preparation document, following the original Hungarian content exactly—without omitting or summarizing any part, and preserving all mathematical structure and notation:

---

## **Topic 5: Exponentiation, Extension of the Concept of Exponentiation, Laws of Exponents. The Concept of the n-th Root. Identities of the Square Root. Power Functions and the Square Root Function**

---

### **Exponentiation with Natural Exponents**

> **D:** Let $a \in \mathbb{R}$ and $n \in \mathbb{N}$. Then we define:

$$
a^n = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}, \quad a^0 = 1
$$

Basic laws of exponents (for $a, b \in \mathbb{R}$, $n, m \in \mathbb{N}$):

1. $a^n \cdot a^m = a^{n+m}$
2. $\frac{a^n}{a^m} = a^{n-m}$ (if $a \ne 0$)
3. $(a^n)^m = a^{nm}$
4. $(ab)^n = a^n b^n$
5. $\left( \frac{a}{b} \right)^n = \frac{a^n}{b^n}$ (if $b \ne 0$)

⚠️ Be careful: $a^n + a^m \ne a^{n+m}$ and $(a + b)^n \ne a^n + b^n$ (in general)

---

### **Extension to Integer Exponents**

> **D:** For $a \ne 0$ and $n \in \mathbb{Z}$, we define:

$$
a^{-n} = \frac{1}{a^n}
$$

Thus:

$$
a^n = \frac{1}{a^{-n}}, \quad a^0 = 1
$$

---

### **Extension to Rational Exponents**

> **D:** Let $a > 0$, $m \in \mathbb{Z}$, and $n \in \mathbb{N}$, then:

$$
a^{\frac{m}{n}} = \sqrt[n]{a^m} = \left( \sqrt[n]{a} \right)^m
$$

---

### **The n-th Root and the Square Root**

> **D:** The **n-th root** of a number $a$ (denoted $\sqrt[n]{a}$) is the non-negative number $x$ for which $x^n = a$, if such exists.

If $n$ is **even**, then:

* $\sqrt[n]{a}$ is defined **only for $a \ge 0$**.
* The result is **non-negative**.

If $n$ is **odd**, then:

* $\sqrt[n]{a}$ is defined for **all real numbers $a$**.
* The result can be **negative**.

> **D:** The **square root** of a non-negative number $a$ is the non-negative number $x$ such that $x^2 = a$.
> Notation: $\sqrt{a}$

Identities involving square roots:

1. $\sqrt{a^2} = |a|$
2. $\sqrt{ab} = \sqrt{a} \cdot \sqrt{b}$ (if $a, b \ge 0$)
3. $\frac{\sqrt{a}}{\sqrt{b}} = \sqrt{\frac{a}{b}}$ (if $a, b \ge 0, b \ne 0$)

⚠️ Be cautious: $\sqrt{a^2} \ne a$ in general (e.g., if $a = -5$, then $\sqrt{a^2} = 5$, but $a = -5$)

---

### **Power Functions**

> **D:** A **power function** is a function of the form $f(x) = x^r$, where $r \in \mathbb{Q}$ (in higher studies $r \in \mathbb{R}$)

**Key special cases**:

* $f(x) = x$: identity function
* $f(x) = x^2$: parabola
* $f(x) = x^{-1}$: reciprocal function
* $f(x) = \sqrt{x} = x^{1/2}$: square root function

**Properties** depend on the exponent $r$:

* If $r > 1$: increasing, convex
* If $0 < r < 1$: increasing, concave
* If $r < 0$: hyperbola-like behavior, discontinuity at 0

Domain and range vary:

* For even roots: domain $x \ge 0$
* For negative exponents: domain $x \ne 0$

---

### **Graph of the Square Root Function**

Function: $f(x) = \sqrt{x}$

* **Domain**: $x \ge 0$
* **Range**: $y \ge 0$
* **Increasing**
* **Concave**
* Not defined for negative $x$

**Graph**: half parabola opening to the right

---

### **Application Examples**

1. **Physics**: Kinematic equations include square root or quadratic forms.
2. **Economics**: Power functions in utility or cost functions.
3. **Geometry**: Pythagorean theorem involves square roots.
4. **Computer science**: Exponential time algorithms, root approximations.

---

**Note:** In many practical problems (e.g., with radicals), it is essential to consider **domain restrictions** and whether simplifications such as $\sqrt{x^2} = x$ are **valid** over the entire domain.

---
Here is the **full and accurate English translation of Topic 6** from the uploaded Hungarian oral mathematics exam guide. The translation preserves every definition, formula, and structure, without omissions or summarizations:

---

## **Topic 6: The Concept and Properties of the Logarithm. The Exponential and Logarithmic Function. The Inverse Function.**

---

### **Definition of Logarithm**

> **D:** For any $a > 0$, $a \ne 1$, and $x > 0$, the **logarithm of $x$ to base $a$** is the number $y$ such that:

$$
a^y = x
$$

This number is denoted:

$$
\log_a x = y
$$

In words: **"logarithm is the exponent to which the base must be raised to yield the argument."**

---

### **Laws of Logarithms**

Let $a > 0$, $a \ne 1$, and $x, y > 0$:

1. **Product rule**:

   $$
   \log_a(x \cdot y) = \log_a x + \log_a y
   $$
2. **Quotient rule**:

   $$
   \log_a\left(\frac{x}{y}\right) = \log_a x - \log_a y
   $$
3. **Power rule**:

   $$
   \log_a(x^r) = r \cdot \log_a x \quad \text{for } r \in \mathbb{Q}
   $$

From the definition:

* $\log_a 1 = 0$
* $\log_a a = 1$

⚠️ **Beware of common mistakes**:

* $\log_a(x + y) \ne \log_a x + \log_a y$
* $\log_a(x - y) \ne \log_a x - \log_a y$

---

### **Change of Base Formula**

> **T:** For any $a, b > 0$, $a \ne 1$, $b \ne 1$, and $x > 0$:

$$
\log_a x = \frac{\log_b x}{\log_b a}
$$

**Special bases**:

* $\log_{10} x$: **common logarithm** (often written as $\log x$)
* $\log_e x$: **natural logarithm** (written as $\ln x$, base $e \approx 2.718$)

---

### **The Exponential Function**

> **D:** For any base $a > 0$, $a \ne 1$, the **exponential function** is:

$$
f(x) = a^x
$$

**Properties**:

* Domain: $\mathbb{R}$
* Range: $\mathbb{R}^+$
* Continuous and strictly monotonic:

  * **Increasing** if $a > 1$
  * **Decreasing** if $0 < a < 1$
* Graph passes through $(0, 1)$
* Horizontal asymptote: $y = 0$

**Applications**: compound interest, population growth, radioactive decay.

---

### **The Logarithmic Function**

> **D:** For base $a > 0$, $a \ne 1$, the **logarithmic function** is the inverse of the exponential:

$$
f(x) = \log_a x
$$

**Properties**:

* Domain: $\mathbb{R}^+$
* Range: $\mathbb{R}$
* Continuous and strictly monotonic:

  * **Increasing** if $a > 1$
  * **Decreasing** if $0 < a < 1$
* Graph passes through $(1, 0)$
* Vertical asymptote: $x = 0$

---

### **Graphical Relationship: Exponential and Logarithmic Functions**

* They are **inverse functions** of each other.
* Their graphs are **symmetric** with respect to the line $y = x$.

---

### **Inverse Function**

> **D:** A function $f$ has an inverse $f^{-1}$ if it is **bijective** (injective and surjective).

* $f(f^{-1}(x)) = x$
* $f^{-1}(f(x)) = x$

**Graph**: Reflection of $f$ across the line $y = x$

Examples:

* $f(x) = a^x \Rightarrow f^{-1}(x) = \log_a x$
* $f(x) = \log_a x \Rightarrow f^{-1}(x) = a^x$

⚠️ Always verify domain restrictions!

---

### **Applications**

1. **Mathematics**: solving exponential and logarithmic equations
2. **Physics**: half-life calculations, decibel scale
3. **Economics**: growth models, elasticity
4. **Biology**: pH scale, population models
5. **Computer science**: algorithm complexity (e.g. $\log n$)

---
Here is the English translation of **Tétel 7** ("Theorem 7") from the Hungarian high school advanced level oral mathematics exam preparation document:

---

## **Topic 7: Quadratic Equations and Inequalities. Equations Reducible to Quadratics. Equivalence of Equations, Loss of Roots, Extraneous Roots, Verification.**

### **Definition:**

An *equation (or inequality)* is a type of logical function (open sentence) that connects two mathematical expressions with an equals sign (or relational operator). The parts of the equation are referred to as the *left-hand side* and the *right-hand side*. The domain of the logical function is called the *domain of the equation (or inequality)*. The subset of the domain for which the logical function evaluates to true is called the *solution set* (or truth set) of the equation (or inequality). In the case of an equation, the elements of the solution set are referred to as *roots*.

Depending on the domain and the logical assertion, we may refer to scalar equations, vector equations, tensor equations, etc.

### **Definitions:**

* Two equations (or inequalities) with the same domain and solution set are called **identities**.
* Two equations (or inequalities) are said to be **equivalent** if they have the same domain and solution set.

> **Note:** In practice, the domain of the equation (or inequality) is often not explicitly stated, or only an initial set is given.

---

### **Quadratic Equations**

A general quadratic equation has the form:

$$
ax^2 + bx + c = 0 \quad \text{where } a \neq 0
$$

Let $D = b^2 - 4ac$ be the discriminant.

**Case 1:** If $D > 0$, then the equation has two distinct real roots:

$$
x_1 = \frac{-b - \sqrt{D}}{2a}, \quad x_2 = \frac{-b + \sqrt{D}}{2a}
$$

**Case 2:** If $D = 0$, then the equation has one real root:

$$
x = \frac{-b}{2a}
$$

**Case 3:** If $D < 0$, then the equation has no real roots.

---

### **Relationships Between Roots and Coefficients (Viète’s Formulas):**

For a quadratic equation $ax^2 + bx + c = 0$ with real roots $x_1$ and $x_2$:

$$
x_1 + x_2 = -\frac{b}{a}, \quad x_1 x_2 = \frac{c}{a}
$$

---

### **Quadratic Inequalities**

We typically solve simple quadratic inequalities graphically (sometimes with algebraic support). After setting the expression to zero, we sketch the graph of the quadratic function and read off the solution set.

**Example:**
Solve:

$$
x(x + 6) \leq 27, \quad x \in \mathbb{R}
$$

Distribute and rearrange:

$$
x^2 + 6x - 27 \leq 0
$$

Graphing the parabola reveals the solution:

$$
M = [-9, 3]
$$

---

### **Inequalities with Fractions**

These are best solved by:

1. Moving all terms to one side.
2. Finding a common denominator.
3. Rewriting as a product (factored form).
4. Analyzing signs (sign chart).

**Example:**
Solve in $\mathbb{R} \setminus \{1, 3\}$:

$$
\frac{x - 1}{x - 3} < \frac{2}{x - 1}
$$

Bring to common denominator and simplify:

$$
\frac{(x - 1)^2 - 2(x - 3)}{(x - 3)(x - 1)} < 0
$$

Factor:

$$
\frac{(x - 2)^2 - 3}{(x - 3)(x - 1)} < 0
$$

Sign analysis yields:

$$
M = (-\infty, 1) \cup (2, 3) \cup (3, \infty)
$$

---

### **Inequalities with Square Roots**

These are often solved graphically. Once the points of intersection are known (through solving the equality), the solution set can be determined.

**Example:**

$$
\sqrt{x - 5} \leq \sqrt{9 - x}
$$

After algebraic manipulation and domain analysis:

$$
D = [5, 9]
$$

Solving gives:

$$
M = [5, 9]
$$

---

### **Equations Reducible to Quadratics**

There are two main types:

**a) Square root equations** that become quadratic after squaring:

$$
\sqrt{x + 2} + x = 5
$$

> Beware of extraneous roots!

**b) Equations involving suitable substitutions**, e.g., exponential, trigonometric, or higher-order equations:

* Let $y = x^2$, or $y = \cos x$, etc.

---

### **Loss of Roots and Extraneous Roots**

During algebraic manipulations (especially squaring), we may perform non-equivalent operations. For example:

* Squaring both sides may introduce **extraneous roots**—solutions not valid in the original domain.
* Dividing by an expression that might be zero may result in **loss of roots**.

Always verify candidate solutions by substitution into the original equation.

---
Here is the English translation of the **8th topic** from the Hungarian advanced-level mathematics oral exam preparation guide, rendered faithfully and with complete preservation of mathematical content, definitions, theorems, formulas, and visual elements:

---

## **Topic 8: Characteristics of Descriptive Statistics, Diagrams. Notable Measures of Central Tendency**

### **Definition and Purpose of Descriptive Statistics**

Descriptive statistics serve to summarize, organize, and describe the main features of a dataset through numerical values and visual tools. It forms the basis of statistical analysis and helps us understand the structure and distribution of data.

### **Key Concepts in Descriptive Statistics**

#### **1. Types of Data**

* **Qualitative (categorical):** data that can be grouped into categories (e.g., colors, brands).
* **Quantitative (numerical):** measurable data (e.g., height, temperature).

Quantitative data can further be subdivided:

* **Discrete:** countable values (e.g., number of students).
* **Continuous:** measurable within an interval (e.g., weight, time).

#### **2. Frequency Tables**

These summarize how often each value (or group of values) occurs in a dataset. Components:

* Absolute frequency (fi)
* Relative frequency (hi = fi / n)
* Cumulative frequency (Fi)
* Cumulative relative frequency (Hi)

#### **3. Visual Representations (Diagrams)**

* **Bar chart:** used for qualitative or discrete data.
* **Histogram:** suitable for continuous data; bars are adjacent.
* **Pie chart:** shows the proportion of categories in a whole.
* **Line chart:** shows trends over intervals.
* **Box plot (box-and-whisker):** represents the five-number summary (min, Q1, median, Q3, max).

### **Notable Measures of Central Tendency**

#### **1. Arithmetic Mean**

$$
\overline{x} = \frac{1}{n} \sum_{i=1}^{n} x_i
$$

If data has frequencies:

$$
\overline{x} = \frac{1}{n} \sum_{i=1}^{k} x_i f_i
$$

It provides a balanced value that equalizes deviations.

#### **2. Median (Me)**

The middle value when data is sorted in increasing order. If n is:

* Odd: middle element.
* Even: mean of the two middle values.

#### **3. Mode (Mo)**

The most frequently occurring value(s). There can be:

* No mode (no repetitions),
* One mode (unimodal),
* Two modes (bimodal),
* Multiple modes (multimodal).

#### **4. Weighted Mean**

If different data points have different "weights":

$$
\overline{x}_{\text{weighted}} = \frac{\sum_{i=1}^{k} w_i x_i}{\sum_{i=1}^{k} w_i}
$$

#### **5. Geometric Mean**

$$
\text{G.M.} = \sqrt[n]{x_1 \cdot x_2 \cdots x_n}
$$

Only defined for positive values.

#### **6. Harmonic Mean**

$$
\text{H.M.} = \frac{n}{\sum_{i=1}^{n} \frac{1}{x_i}}
$$

### **Comparison of Central Tendencies**

* **Mean** is sensitive to outliers.
* **Median** is robust and useful in skewed distributions.
* **Mode** is useful for categorical data.

### **Application Example**

Consider a dataset with student test scores. We can summarize it with:

* A frequency table,
* Diagrams (e.g., histogram),
* Calculate central tendencies to determine class performance.

---
Rendben, elkészítem a 9. tétel (Függvénytani alapismeretek, függvények tulajdonságai, határérték, folytonosság. Számsorozatok. A számtani sorozat, az első n tag összege) **szó szerinti, precíz angol fordítását** matematikatanári, anyanyelvi minőségben. Minden képletet, ábrát, szerkezeti felosztást, alcímet megőrzök és a matematikai nyelvezetet angol érettségi szintre emelem. A képletek, szakszavak pontos angol megfelelőit használom.

---

## 9. Topic: Basic Concepts of Functions, Properties of Functions, Limits, Continuity. Sequences. Arithmetic Sequence, Sum of the First n Terms

### Functions

**Definition:**
A function is a mapping that assigns to each element of a set exactly one element of another set (possibly the same set). The first set is called the *domain* of the function, the second is the *codomain*, and the set of all output values is the *range* (or image) of the function.
We denote a function as $f: A \to B$, meaning $f$ maps from set $A$ to set $B$.

**Examples of function notations:**

* $f(x) = x^2$
* $f: x \mapsto x^2$
* $y = f(x) = x^2$, where $x \in \mathbb{R}$, $y \in \mathbb{R}^+$ (or $[0, +\infty)$)

**Properties of functions:**
The most important properties we analyze are:

* Domain, codomain, range
* Injectivity (one-to-one)
* Surjectivity (onto)
* Bijectivity (both one-to-one and onto)
* Even and odd functions
* Periodicity
* Monotonicity (increasing or decreasing)
* Boundedness (above, below)
* Extrema (maximum, minimum)
* Inverse function

#### Definitions and Properties

* **Domain:** The set of all possible inputs ($x$) for which the function is defined.

* **Range (image):** The set of all possible output values ($y$) that the function can attain.

* **Injective (one-to-one):** The function is injective if different elements of the domain are mapped to different elements of the codomain:
  $\forall x_1, x_2 \in A, x_1 \ne x_2 \implies f(x_1) \ne f(x_2)$

* **Surjective (onto):** The function is surjective if for every element of the codomain there is a preimage in the domain:
  $\forall y \in B, \exists x \in A: f(x) = y$

* **Bijective:** A function is bijective if it is both injective and surjective.

* **Even function:**
  $f(-x) = f(x)$ for all $x$ in the domain (e.g., $x^2$)

* **Odd function:**
  $f(-x) = -f(x)$ for all $x$ in the domain (e.g., $x^3$, $\sin x$)

* **Periodic function:**
  There exists a positive real number $T$ such that $f(x + T) = f(x)$ for all $x$ in the domain (e.g., $\sin x$, period $2\pi$)

* **Monotonicity:**

  * Increasing: $f(x_1) < f(x_2)$ if $x_1 < x_2$
  * Decreasing: $f(x_1) > f(x_2)$ if $x_1 < x_2$

* **Bounded above/below:**

  * There exists an $M$ such that $f(x) \leq M$ for all $x$ in the domain (bounded above)
  * There exists an $m$ such that $f(x) \geq m$ for all $x$ in the domain (bounded below)

* **Maximum, minimum (extremum):**
  The greatest or least value attained by the function on its domain.

* **Inverse function:**
  If $f$ is bijective, then its inverse $f^{-1}$ exists, such that $f^{-1}(f(x)) = x$ and $f(f^{-1}(y)) = y$.

---

### Limits and Continuity

#### Limit of a function at a point

**Definition:**
Let $f$ be defined in a neighborhood of $a$ (except possibly at $a$). We say that the limit of $f(x)$ as $x \to a$ is $A$,

$$
\lim_{x \to a} f(x) = A
$$

if for every $\varepsilon > 0$, there exists $\delta > 0$ such that for all $x$ with $0 < |x - a| < \delta$, it follows that $|f(x) - A| < \varepsilon$.

**Left and right limits:**

* The **left-hand limit** as $x \to a^-$: $\lim_{x \to a^-} f(x)$
* The **right-hand limit** as $x \to a^+$: $\lim_{x \to a^+} f(x)$
* The limit exists if and only if the left and right limits are equal.

#### Continuity

**Definition:**
A function $f$ is *continuous* at point $a$ if

$$
\lim_{x \to a} f(x) = f(a)
$$

i.e., the function’s value at $a$ is equal to the limit as $x$ approaches $a$.

**Types of discontinuity:**

* Removable discontinuity (hole)
* Jump discontinuity (step)
* Infinite discontinuity (asymptote)

**Theorems related to continuity:**

* If $f$ and $g$ are continuous at $a$, then $f+g$, $f-g$, $fg$, and (if $g(a)\ne 0$) $\frac{f}{g}$ are also continuous at $a$.

---

### Sequences

**Definition:**
A sequence is a function whose domain is the set of natural numbers ($\mathbb{N}$) or a subset thereof. We write the sequence as $(a_n)$ or $\{a_n\}$.

**Types of sequences:**

* Finite/infinite
* Monotonic (increasing, decreasing)
* Bounded
* Constant

#### Limit of a sequence

A sequence $(a_n)$ converges to $A$ if for every $\varepsilon > 0$ there exists $N$ such that for all $n > N$, $|a_n - A| < \varepsilon$.
If such an $A$ exists, the sequence is **convergent**, otherwise **divergent**.

---

### Arithmetic Sequence

**Definition:**
A sequence is called an arithmetic sequence if the difference between any two consecutive terms is constant. That is,

$$
a_{n+1} = a_n + d
$$

where $d$ is the common difference.

**General formula for the nth term:**

$$
a_n = a_1 + (n-1)d
$$

**Sum of the first n terms:**

$$
S_n = a_1 + a_2 + \dots + a_n
$$

This can be calculated by the formula:

$$
S_n = \frac{n(a_1 + a_n)}{2}
$$

or

$$
S_n = \frac{n\left[2a_1 + (n-1)d\right]}{2}
$$

**Proof of the sum formula:**
Let us write the sum forwards and backwards:

$$
S_n = a_1 + a_2 + \ldots + a_n \\
S_n = a_n + a_{n-1} + \ldots + a_1
$$

Adding both, each pair sums to $a_1 + a_n$, and there are $n$ pairs:

$$
2S_n = n(a_1 + a_n) \implies S_n = \frac{n(a_1 + a_n)}{2}
$$

---

### Applications

* The concept of function is fundamental in all branches of mathematics, as well as in natural and social sciences.
* Limits and continuity are crucial for calculus, physics, and engineering (e.g., studying motion, rates of change).
* Sequences and series appear in statistics, economics (e.g., payments, annuities), and many fields involving progression or accumulation.
* The arithmetic sequence is frequently used in financial calculations, such as installment payments, and in various real-life problems involving uniform change.

---
