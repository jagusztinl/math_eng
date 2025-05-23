Here is the **precise English translation** of **Tétel 1** (Topic 1) from the uploaded document, faithfully preserving all mathematical content, terminology, formulas, and structure, including visuals:

---

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
