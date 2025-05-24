

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

Here is a **precise, complete, and faithful English translation of Topic 10** from your document for the oral mathematics matura exam, following the original mathematical content, formulas, and structure. All formulas, calculations, and the structure are preserved. If you need specific diagrams or page images verbatim, let me know and I can refer directly to the rendered image for you.

---

## 10. Topic: Geometric (Exponential) Sequences, Sum of the First n Terms, Infinite Geometric Series. Compound Interest, Annuities, Loan Installments. Exponential Processes in Society and Nature

---

### Geometric (Exponential) Sequence

**Definition:**
A sequence is called a geometric (or exponential) sequence if the ratio of any two consecutive terms is constant. That is,

$$
a_{n+1} = a_n \cdot q
$$

where $q$ is the common ratio (or quotient).

**General formula for the nth term:**

$$
a_n = a_1 \cdot q^{n-1}
$$

where:

* $a_1$: the first term,
* $q$: the common ratio,
* $n$: the index of the term.

---

### Sum of the First n Terms

The sum of the first $n$ terms of a geometric sequence:

$$
S_n = a_1 + a_2 + \dots + a_n
$$

**Formula:**
If $q \neq 1$, then

$$
S_n = a_1 \cdot \frac{1 - q^n}{1 - q}
$$

If $q = 1$, then all terms are equal and

$$
S_n = n \cdot a_1
$$

**Proof of the formula:**
Let us consider the sum:

$$
S_n = a_1 + a_1 q + a_1 q^2 + \ldots + a_1 q^{n-1}
$$

Multiplying both sides by $q$:

$$
q S_n = a_1 q + a_1 q^2 + \ldots + a_1 q^{n}
$$

Subtract the second equation from the first:

$$
S_n - q S_n = a_1 - a_1 q^n \\
S_n (1 - q) = a_1 (1 - q^n) \\
S_n = a_1 \frac{1 - q^n}{1 - q}
$$

//

---

### Infinite Geometric Series

If $|q| < 1$, the infinite geometric series converges and its sum is:

$$
S = a_1 \cdot \frac{1}{1 - q}
$$

**Proof:**
As $n \to \infty$, $q^n \to 0$ if $|q| < 1$, so

$$
S = \lim_{n \to \infty} S_n = a_1 \frac{1 - 0}{1 - q} = a_1 \frac{1}{1 - q}
$$

//

---

### Compound Interest, Annuities, Loan Installments

#### **Compound Interest**

If an initial principal $P_0$ is invested at an interest rate of $r$ per period (where $r$ is expressed as a decimal, e.g., 0.05 for 5%), then after $n$ periods the value of the investment will be:

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

#### **Loan Installments (Amortizing a Loan)**

If you borrow an amount $P$ and repay it in $n$ equal installments at an interest rate $r$ per period, the formula for the installment amount $A$ is:

$$
A = P \cdot \frac{r (1 + r)^n}{(1 + r)^n - 1}
$$

This is derived from the geometric series describing the present value of the annuity of payments.

---

### Exponential Processes in Society and Nature

**Exponential growth:**
A process is called exponential if its rate of change is proportional to its current value. The general formula:

$$
y = y_0 \cdot a^x
$$

where:

* $y_0$: initial value,
* $a$: base of the exponent ($a > 0$, $a \neq 1$),
* $x$: number of periods.

In natural and social sciences, many phenomena are modeled by exponential functions:

* **Population growth:** If a population increases by a fixed percentage each year.
* **Radioactive decay:** The number of undecayed nuclei decreases exponentially.
* **Inflation:** The value of money decreases exponentially if inflation is constant.
* **Spread of epidemics:** Number of infected can increase or decrease exponentially depending on the reproduction rate.

---

### Applications

* The geometric sequence models compound interest, investments, installment savings, annuities, loan repayments, and depreciation.
* Exponential functions are used in biology (bacterial growth, population dynamics), physics (radioactive decay, capacitor discharge), economics (inflation, compound interest), and computer science (algorithmic complexity).
* Infinite geometric series are used in physics (e.g., optics, wave phenomena), engineering, and even everyday contexts (calculating repeating decimals).

---

**Remark:**
If you would like the original diagrams or formulas as they appear in the PDF (for example, formulas in MathType or annotated diagrams), please let me know which page(s) or figure(s) you wish to see, and I will provide an accurate rendering or direct image snippet.

---
Here is a **precise and faithful English translation** of Topic 11 from your mathematics oral exam material, preserving all mathematical content, formulas, structure, and professional terminology. If you need the original images or formula layouts as rendered in the PDF, please specify the pages and I will refer to or transcribe them directly.

---

## 11. Topic: The Concept of the Derivative, Rules of Differentiation. Applications of Differential Calculus (Tangents, Function Analysis, Optimization Problems)

---

### The Concept of the Derivative

**Definition:**
Let $f$ be a function defined in a neighborhood of $x_0$.
The **derivative** of $f$ at the point $x_0$ is defined as:

$$
f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0}
$$

if this limit exists.
$f'(x_0)$ is called the derivative of $f$ at $x_0$, and the function $f'(x)$ is called the **derivative function** of $f$.

**Interpretation:**

* Geometric: The derivative at a point is the slope of the tangent line to the curve at that point.
* Physical: If $s(t)$ denotes the position as a function of time, then the derivative $s'(t)$ is the instantaneous velocity at time $t$.

---

### Rules of Differentiation

Let $f$ and $g$ be differentiable at $x_0$, and let $c$ be a real constant. Then:

1. **Linearity:**

   $$
   (f + g)'(x_0) = f'(x_0) + g'(x_0)
   $$

   $$
   (c \cdot f)'(x_0) = c \cdot f'(x_0)
   $$

2. **Product rule:**

   $$
   (f \cdot g)'(x_0) = f'(x_0) \cdot g(x_0) + f(x_0) \cdot g'(x_0)
   $$

3. **Quotient rule:**
   If $g(x_0) \neq 0$:

   $$
   \left( \frac{f}{g} \right)'(x_0) = \frac{f'(x_0) \cdot g(x_0) - f(x_0) \cdot g'(x_0)}{[g(x_0)]^2}
   $$

4. **Chain rule:**
   If $f$ is differentiable at $x_0$, and $g$ is differentiable at $f(x_0)$, then:

   $$
   (g \circ f)'(x_0) = g'(f(x_0)) \cdot f'(x_0)
   $$

---

### Table of Basic Derivatives

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

### Applications of Differential Calculus

#### 1. Tangent to a Curve

**Definition:**
The equation of the tangent line to the curve $y = f(x)$ at the point $x_0$ is:

$$
y = f(x_0) + f'(x_0)(x - x_0)
$$

This line passes through $(x_0, f(x_0))$ and has slope $f'(x_0)$.

#### 2. Function Analysis

By examining the derivative, we can determine:

* **Monotonicity:**

  * If $f'(x) > 0$ in an interval, $f$ is increasing there.
  * If $f'(x) < 0$ in an interval, $f$ is decreasing there.
  * If $f'(x) = 0$, possible extremum (maximum, minimum, or inflection point).

* **Extrema (maximum/minimum points):**

  * If $f'(x_0) = 0$, and the sign of $f'(x)$ changes from positive to negative at $x_0$, $f$ has a local maximum at $x_0$.
  * If the sign changes from negative to positive, $f$ has a local minimum at $x_0$.

* **Inflection point:**
  If the second derivative $f''(x_0) = 0$ and the sign of $f''(x)$ changes at $x_0$, then $x_0$ is a point of inflection.

#### 3. Optimization Problems (Extremum Problems)

Typical steps:

1. Express the quantity to be optimized as a function.
2. Find the derivative and set it to zero to locate critical points.
3. Use the first or second derivative test to determine maxima or minima.
4. Check the value(s) at endpoints if the interval is closed.

**Example:**
Find the maximum area of a rectangle with fixed perimeter.

Let the sides be $x$ and $y$, with $2x + 2y = p \implies y = \frac{p}{2} - x$.
Area $A(x) = x \cdot y = x \left( \frac{p}{2} - x \right)$.
Differentiate and set to zero:

$$
A'(x) = \frac{p}{2} - 2x = 0 \implies x = \frac{p}{4}
$$

So both sides are equal; the rectangle is a square.

---

### Applications

* The concept of the derivative is foundational in natural and social sciences, engineering, and economics.
* Used to study the motion of objects (velocity, acceleration), optimize production, determine rates of change, and much more.
* Function analysis is essential in graphing, economic modeling, and technical applications.
* Optimization problems are central in logistics, resource allocation, design, and other practical fields.

---

Certainly! Here is a **precise, literal, and complete English translation of Topic 12** from your oral mathematics matura document. All definitions, theorems, proofs, formulas, and logical structure are preserved, following the original mathematical content closely.
If you would like any images or diagrams reproduced from the PDF, please specify the page, and I will provide a direct transcription.

---

## 12. Topic: Theorems on Right-Angled Triangles. Trigonometric Functions of Acute Angles. Relationships Between Trigonometric Functions of Acute Angles. Generalization of Trigonometric Functions

---

### Theorems on Right-Angled Triangles

**Definition:**
A right-angled triangle is a triangle in which one of the angles is a right angle ($90^\circ$). The side opposite the right angle is called the *hypotenuse*, the other two sides are called the *legs*.

#### Pythagorean Theorem

**Theorem:**
In every right-angled triangle, the square of the hypotenuse equals the sum of the squares of the legs.

Let $a$ and $b$ denote the lengths of the legs, and $c$ the length of the hypotenuse:

$$
c^2 = a^2 + b^2
$$

**Proof:**
A proof can be constructed in several ways (for example, using the area of squares built on the sides, or via similar triangles).

---

### Trigonometric Functions of Acute Angles

**Definition:**
Let us consider a right-angled triangle, with an acute angle $\alpha$, legs of lengths $a$ and $b$, and hypotenuse $c$:

* **Sine of angle $\alpha$:**

  $$
  \sin \alpha = \frac{\text{opposite leg}}{\text{hypotenuse}} = \frac{a}{c}
  $$
* **Cosine of angle $\alpha$:**

  $$
  \cos \alpha = \frac{\text{adjacent leg}}{\text{hypotenuse}} = \frac{b}{c}
  $$
* **Tangent of angle $\alpha$:**

  $$
  \tan \alpha = \frac{\text{opposite leg}}{\text{adjacent leg}} = \frac{a}{b}
  $$
* **Cotangent of angle $\alpha$:**

  $$
  \cot \alpha = \frac{\text{adjacent leg}}{\text{opposite leg}} = \frac{b}{a}
  $$

**Remark:**
The sine, cosine, tangent, and cotangent of an acute angle are always positive and less than or equal to 1 (except for tangent and cotangent, which can be any positive real number).

---

### Relationships Among Trigonometric Functions of Acute Angles

* **Pythagorean Identity:**

  $$
  \sin^2 \alpha + \cos^2 \alpha = 1
  $$

  (This follows from the Pythagorean theorem: $a^2 + b^2 = c^2$, so $\frac{a^2}{c^2} + \frac{b^2}{c^2} = 1$.)

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

* **Other relationships:**

  $$
  1 + \tan^2 \alpha = \frac{1}{\cos^2 \alpha}
  $$

  $$
  1 + \cot^2 \alpha = \frac{1}{\sin^2 \alpha}
  $$

---

### Generalization of Trigonometric Functions

To extend trigonometric functions beyond acute angles, we use the *unit circle definition*.

#### **Unit Circle Definition**

Let us consider the unit circle ($x^2 + y^2 = 1$), and let $\alpha$ be a real angle measured from the positive $x$-axis.

* The **sine** of angle $\alpha$ is the $y$-coordinate of the point corresponding to $\alpha$ on the unit circle.
* The **cosine** of angle $\alpha$ is the $x$-coordinate of the point corresponding to $\alpha$.
* The **tangent** and **cotangent** are defined as before, where they are meaningful.

Thus, for any real angle $\alpha$:

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

#### **Signs of Trigonometric Functions in Different Quadrants**

* **I. Quadrant ($0^\circ < \alpha < 90^\circ$)**: All trigonometric functions are positive.
* **II. Quadrant ($90^\circ < \alpha < 180^\circ$)**: Sine is positive, cosine and tangent are negative.
* **III. Quadrant ($180^\circ < \alpha < 270^\circ$)**: Tangent is positive, sine and cosine are negative.
* **IV. Quadrant ($270^\circ < \alpha < 360^\circ$)**: Cosine is positive, sine and tangent are negative.

---

#### **Trigonometric Functions of Negative Angles**

* $\sin(-\alpha) = -\sin \alpha$
* $\cos(-\alpha) = \cos \alpha$
* $\tan(-\alpha) = -\tan \alpha$
* $\cot(-\alpha) = -\cot \alpha$

---

### Applications

* Trigonometric functions are fundamental in geometry, physics (wave motion, oscillations), engineering (signal processing), astronomy, and many other sciences.
* They are used to model periodic phenomena (day-night cycle, seasonal changes), and in calculations involving angles and distances (navigation, surveying).

---
Absolutely! Below is a **precise and complete English translation of Topic 13** from your mathematics oral matura document, following the original structure, terminology, mathematical content, and formulas as closely as possible.
If you need the original images or diagrams exactly as in the PDF, please let me know the page and I will transcribe or describe them accurately.

---

## 13. Topic: Notable Lines, Points, and Circles of Triangles

---

### **Notable Lines of a Triangle**

In every triangle, certain lines are of particular importance. These include:

1. **Median:**
   A *median* of a triangle is a line segment connecting a vertex to the midpoint of the opposite side.

   * **Property:**
     The three medians of a triangle intersect at a single point, called the *centroid* (center of gravity, or barycenter).

   * **Centroid ($S$):**
     The centroid divides each median in a ratio of $2:1$, counting from the vertex. If the triangle’s vertices are $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$, the centroid’s coordinates are:

     $$
     S \left( \frac{x_1 + x_2 + x_3}{3}, \frac{y_1 + y_2 + y_3}{3} \right)
     $$

2. **Angle Bisector:**
   An *angle bisector* is a line segment that divides one of the angles of the triangle into two equal angles and meets the opposite side.

   * **Property:**
     The three angle bisectors meet at one point, the *incenter* of the triangle.

   * **Incenter ($I$):**
     The incenter is the center of the *incircle* (the circle inscribed in the triangle).

3. **Altitude:**
   An *altitude* (or height) is a line segment drawn from a vertex and perpendicular to the opposite side (or its extension).

   * **Property:**
     The three altitudes meet at one point, called the *orthocenter* ($M$) of the triangle.

4. **Perpendicular Bisector:**
   The *perpendicular bisector* of a side is the line that passes through the midpoint of the side and is perpendicular to it.

   * **Property:**
     The three perpendicular bisectors of the sides meet at one point, called the *circumcenter* ($O$) of the triangle.

---

### **Notable Points of a Triangle**

1. **Centroid ($S$):**
   The intersection point of the three medians.

2. **Incenter ($I$):**
   The intersection point of the three angle bisectors.

3. **Orthocenter ($M$):**
   The intersection point of the three altitudes.

4. **Circumcenter ($O$):**
   The intersection point of the three perpendicular bisectors.

---

### **Notable Circles of a Triangle**

1. **Circumcircle (circumscribed circle):**
   The unique circle passing through all three vertices of the triangle.

   * **Circumcenter ($O$):**
     The center of the circumcircle is the intersection of the perpendicular bisectors.
   * **Radius ($R$):**
     For a triangle with side lengths $a, b, c$ and area $T$:

     $$
     R = \frac{abc}{4T}
     $$

2. **Incircle (inscribed circle):**
   The unique circle tangent to all three sides of the triangle.

   * **Incenter ($I$):**
     The center of the incircle is the intersection of the angle bisectors.
   * **Radius ($r$):**
     The radius of the incircle is:

     $$
     r = \frac{T}{s}
     $$

     where $T$ is the area and $s = \frac{a + b + c}{2}$ is the semi-perimeter.

3. **Excircles (escribed circles):**
   Each triangle has three *excircles*, each tangent to one side of the triangle and to the extensions of the other two sides.

---

### **Further Properties and Noteworthy Theorems**

* The centroid, circumcenter, and orthocenter are collinear; they lie on the so-called *Euler line* of the triangle.
* The incenter generally does not lie on the Euler line.
* The nine-point circle passes through:

  * The midpoint of each side,
  * The foot of each altitude,
  * The midpoint of the segment from each vertex to the orthocenter.

---

### **Applications**

* The notable lines, points, and circles of a triangle are central in geometric constructions, proofs, and problem solving.
* They play an important role in classical geometry, trigonometry, and modern applications (such as engineering, architecture, and computer graphics).
* Construction tasks often require finding the incenter, centroid, circumcenter, or orthocenter for given geometric constraints.

---
Certainly! Here is the **precise, word-for-word English translation of Topic 14** from your oral mathematics matura document. The structure, definitions, theorems, proofs, formulas, and logical flow are preserved as in the original. If you require any original diagrams or formula formatting as in the PDF, please specify the page and I will transcribe or describe them.

---

## 14. Topic: Relationships Among the Sides of a General Triangle, Among the Angles, and Between the Sides and Angles

---

### **I. Relationships Among the Sides and Angles of a General Triangle**

Consider an arbitrary triangle $ABC$, with side lengths $a, b, c$ opposite to vertices $A, B, C$, respectively, and with interior angles $\alpha, \beta, \gamma$ at these vertices.

---

### **1. Triangle Inequality**

**Theorem:**
In every triangle, the length of any side is less than the sum and greater than the difference of the lengths of the other two sides:

$$
|a - b| < c < a + b
$$

(and similarly for the other sides).

---

### **2. The Law of Sines (Sine Law)**

**Theorem:**
In every triangle:

$$
\frac{a}{\sin \alpha} = \frac{b}{\sin \beta} = \frac{c}{\sin \gamma} = 2R
$$

where $R$ is the radius of the circumscribed circle (circumradius).

**Proof:**
Draw the circumscribed circle of triangle $ABC$. Using the definition of the sine of a central angle and inscribed angle, the relationship follows.

---

### **3. The Law of Cosines (Cosine Law)**

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
The Law of Cosines can be derived using the Pythagorean Theorem by dropping a height and applying the definitions of cosine in the resulting right triangles.

---

### **4. The Law of Tangents (Tangent Law)**

**Theorem:**
In any triangle:

$$
\frac{a-b}{a+b} = \frac{\tan \frac{1}{2} (\alpha - \beta)}{\tan \frac{1}{2} (\alpha + \beta)}
$$

---

### **5. Area Formulas for a Triangle**

**Area using two sides and the included angle:**

$$
T = \frac{1}{2}ab\sin \gamma
$$

(Analogously for other pairs of sides and the included angle.)

**Area using all three sides (Heron's formula):**

$$
T = \sqrt{s(s-a)(s-b)(s-c)}
$$

where $s = \frac{a+b+c}{2}$ is the semi-perimeter.

**Area using the radius of the inscribed circle:**

$$
T = r \cdot s
$$

where $r$ is the inradius and $s$ is the semi-perimeter.

**Area using the circumradius:**

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

* These relationships are essential for solving triangles (determining unknown sides or angles given sufficient data).
* Widely used in geometry, trigonometry, engineering, architecture, navigation, and physics.

---
Of course! Below is a **precise, literal, and complete English translation of Topic 15** from your oral mathematics matura document, following the original structure, definitions, theorems, and formulas as closely as possible. If you need images or specific diagrams exactly as in the PDF, please specify the page and I will provide the transcription or a description.

---

## 15. Topic: Congruence Transformations, Congruence of Figures. Symmetry. Similarity Transformations. Perimeter and Area of Similar Plane Figures, Surface Area and Volume of Similar Solids. Application of Similarity in Proofs of Plane Geometry Theorems

---

### **I. Congruence Transformations**

**Definition:**
A *congruence transformation* (isometry) is a transformation of the plane (or space) that preserves distances (lengths).
Congruence transformations in the plane include:

* Translation (shift)
* Rotation
* Reflection (across a line)
* Glide reflection (reflection followed by translation along the axis)

**Properties:**

* Congruence transformations preserve distances, angles, areas, perimeters, and the congruence of figures.
* The image of a segment is a segment of the same length.
* The image of a figure is congruent to the original.

---

### **II. Congruence of Figures**

**Definition:**
Two plane figures are called *congruent* if one can be mapped onto the other by a congruence transformation.

* For triangles: Two triangles are congruent if and only if their corresponding sides and corresponding angles are equal.

**Criteria for triangle congruence:**

* SSS (side-side-side): If three sides of one triangle are equal to three sides of another.
* SAS (side-angle-side): If two sides and the included angle of one triangle are equal to those of another.
* ASA (angle-side-angle): If two angles and the included side of one triangle are equal to those of another.
* RHS (right-angle-hypotenuse-side): For right triangles, if the hypotenuse and one leg are equal.

---

### **III. Symmetry**

* **Axial symmetry (reflection):** The figure is invariant under reflection across a line (the axis of symmetry).
* **Central symmetry (point symmetry):** The figure is invariant under a rotation of 180° about a point (the center of symmetry).

---

### **IV. Similarity Transformations**

**Definition:**
A *similarity transformation* is a transformation that preserves the shape of figures but may change their size; it is the composition of a dilation (homothety) and a congruence transformation.

* Dilation (homothety) with center $O$ and ratio $k \neq 0$: Every point $P$ is mapped to $P'$ such that $\overrightarrow{OP'} = k \cdot \overrightarrow{OP}$.

**Properties:**

* Similarity transformations preserve angles, and the ratios of corresponding lengths are constant (the similarity ratio $k$).
* The image of a segment is a segment whose length is $k$ times the original.
* The image of a figure is *similar* to the original.

**Definition:**
Two figures are *similar* if one can be mapped onto the other by a similarity transformation.

---

### **V. Perimeter and Area of Similar Plane Figures**

* If the ratio of similarity between two plane figures is $k$, then:

  * The ratio of perimeters is also $k$.
  * The ratio of areas is $k^2$.

$$
\frac{\text{Perimeter}_1}{\text{Perimeter}_2} = k
$$

$$
\frac{\text{Area}_1}{\text{Area}_2} = k^2
$$

---

### **VI. Surface Area and Volume of Similar Solids**

* If the ratio of similarity between two solids is $k$, then:

  * The ratio of surface areas is $k^2$.
  * The ratio of volumes is $k^3$.

$$
\frac{\text{Surface Area}_1}{\text{Surface Area}_2} = k^2
$$

$$
\frac{\text{Volume}_1}{\text{Volume}_2} = k^3
$$

---

### **VII. Application of Similarity in Plane Geometry Proofs**

* Similarity is often used in geometric proofs, for example:

  * In right triangles, the altitude to the hypotenuse creates two smaller triangles, both similar to the original triangle and to each other.
  * Proving theorems about ratios of segments, lengths, and areas often relies on similarity.
  * Similarity is used in map scaling, model making, and solving real-world problems involving proportional reasoning.

---

### **Applications**

* Congruence and similarity are fundamental concepts in geometry, underpinning the study of shapes, figures, and their transformations.
* They are used in engineering, architecture, design, physics, and many fields where scale models and proportional reasoning are essential.

---
**If you need diagrams (for example, illustrations of transformations, similar triangles, or solids) or exact mathematical notation from the PDF, let me know the page, and I will provide an accurate transcription or description.
**If you would like the next topic, or further explanations on a specific subtopic, just let me k
