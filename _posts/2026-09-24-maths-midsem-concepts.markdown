---
layout: post
title:  " MATHS MIDSEM CONCEPTS"
date:   2026-09-24 10:00:00 +0530
categories: jekyll update
---
### MATHS MIDSEM CONCEPTS - INTRODUCTION TO MAth minor
 
> **Course:** Introduction to Mathematical Thinking

---

## 🧭 Concept Roadmap

**Geometry**  
↓  
**Ratios**  
↓  
**Divisibility**  
↓  
**Common Divisors**  
↓  
**GCD**  
↓  
**Euclidean Algorithm**  
↓  
**Linear Combinations**  
↓  
**Bézout Identity**  
↓  
**Solvability of `ax + by = N`**

---

# Part 1 — BOOs / Basic Constructions

The five BOOs used in the worksheets are:

### O1 — Join Two Points

Given two points `P₁` and `P₂`, construct the crease/line joining `P₁` and `P₂`.

### O2 — Intersection of Two Lines

Given two creases/lines, construct their intersection.

### O3 — Perpendicular Bisector

Given two points `P₁` and `P₂`, fold `P₁` onto `P₂`.

The crease obtained is the **perpendicular bisector** of `P₁P₂`.

Therefore every point on the crease is equally distant from `P₁` and `P₂`.

### O4 — Angle Bisector

Given two creases/lines, fold one onto the other.

The crease obtained is an **angle bisector**.

### O5 — Perpendicular Through a Point

Given a point `P` and a crease/line `L`, construct a crease through `P` perpendicular to `L`.

### Important BOO Results

| BOO | Result |
|---|---|
| **O3** | Perpendicular bisector |
| **O4** | Angle bisector |
| **O5** | Perpendicular through a given point |

> **Parallel-line construction:**  
> Two lines perpendicular to the same line are parallel.
>
> Therefore, to construct a parallel line:
> 1. Construct a perpendicular to the given line.
> 2. Construct another perpendicular to that perpendicular.
> 3. The second line is parallel to the original line.

---

# Part 2 — Similar Triangles

Similar triangles have the same shape but may have different sizes.

- Corresponding angles are equal.
- Corresponding sides are proportional.

If triangle `ABC` is similar to triangle `DEF`, then:

`AB/DE = BC/EF = CA/FD`

### General Idea

If:

`a/b = c/d`

then:

`ad = bc`

### Main Use in This Course

Similar triangles are used to construct ratios such as:

- `1/n`
- `m/n`
- other rational lengths.

---

# Part 3 — Constructing `1/2`

Given `AB = 1`.

Use **O3** on `A` and `B`.

O3 gives the perpendicular bisector of `AB`.

Let it meet `AB` at `M`.

Then:

`AM = MB`

Also:

`AM + MB = AB = 1`

Therefore:

`2AM = 1`

`AM = 1/2`

Hence:

`AM = MB = 1/2`

### General Idea

To divide a segment into two equal parts, use its perpendicular bisector.

---

# Part 4 — General Construction of `1/n`

Suppose `AB = 1`.

We want to construct:

`1/n`

### General Construction

1. Start with `AB = 1`.
2. Draw an auxiliary ray from `A`.
3. Mark `n` equal consecutive lengths on this ray.
4. Let the first point be `C₁`.
5. Let the nth point be `Cₙ`.
6. Join `Cₙ` to `B`.
7. Through `C₁` construct a line parallel to `CₙB`.
8. Let this parallel meet `AB` at `P`.

By similar triangles:

`AP/AB = AC₁/ACₙ`

Since:

`AC₁ = 1 unit`

and:

`ACₙ = n units`

we get:

`AP/AB = 1/n`

Since:

`AB = 1`

`AP = 1/n`

Therefore:

`AP = 1/n`

> **IMPORTANT:**  
> The construction works because of proportionality from similar triangles.
>
> Whenever the question asks for `1/n`, think:
>
> **EQUAL AUXILIARY STEPS + PARALLEL LINE + SIMILAR TRIANGLES**

---

# Part 5 — General Construction of `m/n`

First construct:

`1/n`

Then copy that length `m` times.

Therefore:

`m/n = m(1/n)`

Hence:

`m/n` can be constructed by repeating the constructed length `1/n` exactly `m` times.

### General Form

`1/n → construct unit fraction`

`m/n → repeat 1/n m times`

---

# Part 6 — Pythagoras

For a right triangle with perpendicular sides `a` and `b` and hypotenuse `c`:

`c² = a² + b²`

Therefore:

`c = √(a² + b²)`

### Main Use

Constructing square roots.

---

# Part 7 — Constructing `√2`

Start with a unit segment:

`AB = 1`

Construct:

`BC = 1`

such that:

`AB ⟂ BC`

Then triangle `ABC` is right angled.

By Pythagoras:

`AC² = AB² + BC²`

`AC² = 1² + 1²`

`AC² = 2`

Therefore:

`AC = √2`

So:

> **`√2` = diagonal of a unit square.**

---

# Part 8 — General Construction of `√(n+1)`

Suppose we already have:

`AB = √n`

Construct:

`BC = 1`

such that:

`AB ⟂ BC`

Then:

`AC² = AB² + BC²`

`AC² = (√n)² + 1²`

`AC² = n + 1`

Therefore:

`AC = √(n+1)`

### General Formula

If `√n` is already available, then:

`√(n+1) = √((√n)² + 1²)`

So one square root can be used to construct the next one.

---

# Part 9 — Constructing `√3/2`

Take an equilateral triangle of side `1`.

Let its altitude be `h`.

The altitude bisects the base.

Therefore:

`half base = 1/2`

Using Pythagoras:

`h² + (1/2)² = 1²`

Therefore:

`h² + 1/4 = 1`

`h² = 3/4`

Therefore:

`h = √(3/4)`

`h = √3/2`

Hence:

> **`√3/2` = altitude of an equilateral triangle of side 1.**

---

# Part 10 — General Square Root Strategy

Whenever you are asked to construct `√K`, try to express `K` in the form:

`K = a² + b²`

or:

`K = a² - b²`

Then use a right triangle.

### For `K = a² + b²`

Construct perpendicular sides `a` and `b`.

The hypotenuse is:

`√K`

### For `K = a² - b²`

Construct a right triangle with hypotenuse `a` and one side `b`.

The other side is:

`√(a² - b²)`

---

# Part 11 — Angles

### Basic Constructions

| Angle | Construction |
|---|---|
| **90°** | Use O5 to construct a perpendicular |
| **45°** | Start with 90° and use O4 to bisect it |
| **60°** | Construct an equilateral triangle |
| **30°** | Bisect 60° using O4 |

`45 = 90/2`

Every angle of an equilateral triangle is:

`60°`

`30 = 60/2`

### Summary

**90° → O5**

**45° → bisect 90° using O4**

**60° → equilateral triangle**

**30° → bisect 60° using O4**

---

# Part 12 — General Angle Problem

Suppose you are given two angles:

`x°` and `y°`

By adding and subtracting angles, we can form integer combinations:

`mx + ny`

where:

`m,n` are integers.

If `x > y`, replace:

`x` by `x - y`

This does not change the greatest common divisor.

`gcd(x,y) = gcd(x-y,y)`

Continue.

If `y > x`:

`gcd(x,y) = gcd(x,y-x)`

Eventually both become equal to `d`.

Then:

`d = gcd(x,y)`

Therefore:

> **THE SMALLEST POSITIVE INTEGER ANGLE OBTAINABLE FROM `x` AND `y` BY INTEGER ADDITION/SUBTRACTION IS `gcd(x,y)`.**

This is exactly the same mathematical structure as the subtraction Euclidean algorithm.

---

## Part 13 — Rectangle / Square Method

Suppose a rectangle has side lengths:

`a` and `b`

with:

`a > b`

Cut/fold squares of side `b`.

The remaining rectangle has dimensions:

`a-b` and `b`

Therefore:

`(a,b) → (a-b,b)`

Continue.

If the remaining side is still larger, subtract again.

Eventually a square remains.

The side length of the final square is:

> **`gcd(a,b)`**

### Why?

Because:

`gcd(a,b) = gcd(a-b,b)`

This follows from preservation of common divisors.

---

# Part 14 — Subtraction Property of Divisibility

Suppose:

`c | a`

and:

`c | b`

Then:

`a = cm`

and:

`b = cn`

for some integers `m,n`.

Subtract:

`a-b = cm-cn`

`a-b = c(m-n)`

Therefore:

`c | (a-b)`

Hence:

> `c | a` and `c | b` implies `c | (a-b)`.

### Reverse Direction

Suppose:

`c | (a-b)`

and:

`c | b`

Since:

`a = (a-b) + b`

we get:

`c | a`

Therefore:

`c | (a-b)` and `c | b` implies `c | a`.

### Important Conclusion

The common divisors do not change:

`c | a` and `c | b`

**if and only if**

`c | (a-b)` and `c | b`.

Therefore the set of common divisors does not change.

---

# Part 15 — GCD Subtraction Property

If:

`a > b`

then:

`gcd(a,b) = gcd(a-b,b)`

More generally:

`gcd(a,b) = gcd(a-qb,b)`

for any integer `q` for which the reduction is useful.

Why?

Because:

`a-qb`

is an integer linear combination of `a` and `b`.

The common divisors remain exactly the same.

---

# Part 16 — Division Algorithm

For positive integers `a` and `b`, there exist unique integers `q` and `r` such that:

`a = bq + r`

where:

`0 ≤ r < b`

`q` is the quotient.

`r` is the remainder.

> **IMPORTANT:**  
> The condition `0 ≤ r < b` is essential.

---

# Part 17 — Why Quotient and Remainder Are Unique

Suppose:

`a = bq₁ + r₁`

and:

`a = bq₂ + r₂`

Equate them:

`bq₁ + r₁ = bq₂ + r₂`

Therefore:

`b(q₁-q₂) = r₂-r₁`

Because:

`0 ≤ r₁ < b`

and:

`0 ≤ r₂ < b`

we have:

`-b < r₂-r₁ < b`

But:

`b(q₁-q₂)`

is a multiple of `b`.

The only multiple of `b` strictly between `-b` and `b` is `0`.

Therefore:

`r₂-r₁ = 0`

So:

`r₁ = r₂`

Then:

`q₁ = q₂`

Therefore quotient and remainder are unique.

---

# Part 18 — Divisibility

### Definition

`a | b`

if and only if:

`b = ak`

for some integer `k`.

For natural numbers, `k` is usually taken to be a natural number according to the convention being used.

> **IMPORTANT:**  
> `a | b` does NOT mean `a/b` is necessarily a natural number written as a decimal.
>
> It means there exists an integer multiplier `k` such that:
>
> `b = ak`.

---

# Part 19 — Basic Divisibility Properties

## Property 1 — Reflexivity

`a | a`

because:

`a = a(1)`

## Property 2 — Transitivity

If:

`a | b`

and:

`b | c`

then:

`a | c`

Proof:

`b = am`

`c = bn`

Therefore:

`c = amn`

Hence:

`a | c`

## Property 3 — Addition

If:

`c | a`

and:

`c | b`

then:

`c | (a+b)`

Proof:

`a = cm`

`b = cn`

Therefore:

`a+b = c(m+n)`

## Property 4 — Subtraction

If:

`c | a`

and:

`c | b`

then:

`c | (a-b)`

Proof:

`a-b = c(m-n)`

## Property 5 — Integer Linear Combination

If:

`c | a`

and:

`c | b`

then:

`c | (ma+nb)`

for any integers `m,n`.

Proof:

`a = cu`

`b = cv`

Then:

`ma+nb`

`= mcu + ncv`

`= c(mu+nv)`

Therefore:

`c | (ma+nb)`

> **THIS IS THE MASTER DIVISIBILITY PROPERTY.**

---

# Part 20 — Common Divisors

A common divisor of `a` and `b` is a number `c` such that:

`c | a`

and:

`c | b`

The set of all common divisors can be thought of as:

`CD(a,b)`

The GCD is the greatest positive common divisor.

---

# Part 21 — Definition of GCD

`d = gcd(a,b)` means:

- `d | a`
- `d | b`
- Every common divisor of `a` and `b` divides `d`.

Formally:

`d | a`

`d | b`

and if:

`c | a` and `c | b`

then:

`c | d`

This definition is stronger and more useful in proofs than simply saying:

> “GCD is the largest common divisor.”

---

# Part 22 — GCD and Euclidean Algorithm

Suppose:

`a = bq + r`

Then:

`r = a - bq`

Therefore:

`gcd(a,b) = gcd(b,r)`

So:

`gcd(a,b) = gcd(b,a mod b)`

Repeat.

Eventually:

`r = 0`

The last non-zero remainder is the GCD.

### General Algorithm

**Input:** `a,b`

**Step 1:** Assume `a ≥ b`.

**Step 2:** Divide:

`a = bq + r`

**Step 3:** If `r = 0`, return `b`.

**Step 4:** Otherwise replace:

`a ← b`

`b ← r`

**Step 5:** Repeat.

### Final Answer

> **Last non-zero remainder = `gcd(a,b)`**

---

# Part 23 — Why Euclidean Algorithm Works

Start with:

`a = bq+r`

Take any common divisor `c` of `a` and `b`.

Then:

`c | a`

and:

`c | b`

Therefore:

`c | (a-qb)`

But:

`a-qb = r`

Therefore:

`c | r`

So every common divisor of `a,b` is also a common divisor of `b,r`.

Conversely, if:

`c | b`

and:

`c | r`

then:

`a = bq+r`

so:

`c | a`

Therefore the common divisor sets are identical.

Hence:

`gcd(a,b) = gcd(b,r)`

---

# Part 24 — Why Euclidean Algorithm Terminates

At each division step:

`a = bq+r`

with:

`0 ≤ r < b`

Therefore the next remainder is smaller than the previous divisor.

So we get:

`b > r₁ > r₂ > r₃ > …`

All are non-negative integers.

A strictly decreasing sequence of positive integers cannot continue forever.

Therefore the algorithm terminates.

---

# Part 25 — EA1: Subtraction Version

**Input:** `a,b`

If:

`a = b`

return `a`.

If:

`a > b`

replace:

`(a,b) → (a-b,b)`

If:

`b > a`

replace:

`(a,b) → (a,b-a)`

Repeat.

### Why does this work?

Because:

`gcd(a,b) = gcd(a-b,b)`

and:

`gcd(a,b) = gcd(a,b-a)`

### Why does it terminate?

Because `a+b` decreases at every subtraction.

Since `a+b` is a positive integer, it cannot decrease forever.

Therefore EA1 terminates.

---

# Part 26 — EA2: Division Version

**Input:** `a,b`

Divide:

`a = bq+r`

If:

`r=0`

then:

`gcd(a,b)=b`

Otherwise:

`(a,b) → (b,r)`

Repeat.

This is faster than repeated subtraction because one division can replace many subtractions.

---

# Part 27 — GCD Properties

`gcd(a,b) = gcd(b,a)`

`gcd(a,b) = gcd(|a|,|b|)`

`gcd(a,b) = gcd(a-b,b)`, when `a>b`

`gcd(a,b) = gcd(a-qb,b)`

`gcd(a,b) = gcd(b,a mod b)`

`gcd(ka,kb) = |k|gcd(a,b)`

If:

`gcd(a,b)=1`

then `a` and `b` are coprime.

---

# Part 28 — Coprime Numbers

Two integers `a` and `b` are coprime if:

`gcd(a,b)=1`

Equivalent statement:

There exist integers `x,y` such that:

`ax+by=1`

Therefore:

`gcd(a,b)=1`

if and only if:

`1` can be expressed as an integer linear combination of `a` and `b`.

---

# Part 29 — Linear Combination

A linear combination of `a` and `b` is:

`ax+by`

where:

`x,y` are integers.

Define:

`L(a,b) = {ax+by : x,y are integers}`

This is the set of all integer linear combinations of `a` and `b`.

---

# Part 30 — Common Divisor and Linear Combination

Suppose:

`c | a`

and:

`c | b`

Then:

`c | (ax+by)`

for every:

`x,y ∈ Z`

Proof:

`a=cm`

`b=cn`

Then:

`ax+by`

`= cmx + cny`

`= c(mx+ny)`

Therefore:

`c | (ax+by)`

> **IMPORTANT:**  
> Every common divisor of `a` and `b` divides every integer linear combination of `a` and `b`.

---

# Part 31 — Bézout Identity

### Bézout's Identity

For integers `a,b` not both zero, there exist integers `x,y` such that:

`ax+by = gcd(a,b)`

Therefore:

> **`gcd(a,b)` is an integer linear combination of `a` and `b`.**

---

# Part 32 — Finding Bézout Coefficients

### General Method

1. Run Euclidean algorithm.
2. Find the last non-zero remainder `d`.
3. `d` is the GCD.
4. Start from the equation producing `d`.
5. Substitute the previous remainder.
6. Continue backwards.
7. Eventually express `d` using only `a` and `b`.

Final form:

`d=ax+by`

The `x` and `y` obtained are Bézout coefficients.

---

# Part 33 — Master Linear Combination Theorem

The equation:

`ax+by=N`

has integer solutions if and only if:

`gcd(a,b) | N`

Symbolically:

> `ax+by=N` has integer solutions **IF AND ONLY IF** `gcd(a,b) | N`.

### Proof — Forward Direction

Suppose:

`N=ax+by`

Let:

`d=gcd(a,b)`

Then:

`d | a`

and:

`d | b`

Therefore:

`d | (ax+by)`

Hence:

`d | N`

### Proof — Reverse Direction

Suppose:

`d | N`

Then:

`N=kd`

for some integer `k`.

By Bézout:

`d=ax₀+by₀`

Therefore:

`N=k(ax₀+by₀)`

So:

`N=a(kx₀)+b(ky₀)`

Therefore integer solutions exist.

---

# Part 34 — The Set `L(a,b)` and GCD

Consider:

`L(a,b) = {ax+by : x,y ∈ Z}`

There are positive elements in this set when `a,b` are not both zero.

By the well-ordering principle, there is a smallest positive element.

Call it `d`.

So:

`d=ax+by`

### Show `d` divides `a`

Use division algorithm:

`a=qd+r`

where:

`0 ≤ r < d`

Then:

`r=a-qd`

Since `a` is in `L(a,b)` and `d` is in `L(a,b)`, `r` is also in `L(a,b)`.

But `d` is the smallest positive element.

Therefore `r` cannot be positive.

So:

`r=0`

Hence:

`d | a`

Similarly:

`d | b`

### Now Take Any Common Divisor `c`

Suppose:

`c | a`

and:

`c | b`

Since:

`d=ax+by`

we know:

`c | d`

Therefore every common divisor divides `d`.

Thus:

`d=gcd(a,b)`

### Final Result

> **The smallest positive element of `L(a,b)` is `gcd(a,b)`.**

---

# Part 35 — The Complete Connection

### START

`a,b`

### DIVISIBILITY

If `c | a` and `c | b`, then `c` divides every:

`ma+nb`

Therefore integer linear combinations preserve common divisors.

### EUCLIDEAN STEP

`a=bq+r`

Therefore:

`r=a-qb`

Since `r` is a linear combination of `a` and `b`, the common divisors remain unchanged.

Hence:

`gcd(a,b)=gcd(b,r)`

### REPEAT

Euclidean algorithm.

Eventually:

`last non-zero remainder = gcd(a,b)`

### BACK-SUBSTITUTION

Since every remainder is a linear combination of earlier numbers:

`gcd(a,b)=ax+by`

### BÉZOUT

Therefore the GCD is an integer linear combination.

### SOLVABILITY

`ax+by=N`

is solvable exactly when:

`gcd(a,b) | N`

> ## The Complete Chain
>
> **DIVISIBILITY**  
> ↓  
> **INTEGER LINEAR COMBINATIONS**  
> ↓  
> **SUBTRACTION PROPERTY**  
> ↓  
> **DIVISION PROPERTY**  
> ↓  
> **EUCLIDEAN ALGORITHM**  
> ↓  
> **GCD**  
> ↓  
> **BACK-SUBSTITUTION**  
> ↓  
> **BÉZOUT IDENTITY**  
> ↓  
> **`ax+by=N`**  
> ↓  
> **`gcd(a,b) | N`**

---

# Part 36 — How to Prove Something Is the GCD

If a question says:

> **“Prove `d = gcd(a,b)`.”**

Do exactly this:

### Step 1

Show:

`d | a`

### Step 2

Show:

`d | b`

### Step 3

Take an arbitrary common divisor `c`.

Assume:

`c | a`

and:

`c | b`

### Step 4

Prove:

`c | d`

### Step 5

Conclude:

`d=gcd(a,b)`

> **DO NOT ONLY SAY:**  
> “d is the largest common divisor.”
>
> The divisibility characterization is much more useful for proofs.

---

# Part 37 — How to Prove Two GCDs Are Equal

To prove:

`gcd(a,b)=gcd(c,d)`

one powerful method is to show that the two pairs have exactly the same common divisors.

Show:

`x` divides `a` and `b`

**if and only if**

`x` divides `c` and `d`.

Then their common divisor sets are identical.

Therefore their GCDs are equal.

For Euclidean algorithm:

`gcd(a,b)=gcd(b,r)`

because:

`CD(a,b)=CD(b,r)`

---

# Part 38 — How to Prove a Number Is Not the GCD

If someone claims:

`d=gcd(a,b)`

try to find a contradiction.

Either:

- `d` does not divide `a`,
- `d` does not divide `b`,
- there is another common divisor larger than `d`, or
- a common divisor does not divide `d`.

Any one of these disproves the claim.

---

# Part 39 — How to Prove Two Numbers Are Coprime

### Method 1

Run Euclidean algorithm.

If final GCD = `1`:

`gcd(a,b)=1`

Therefore they are coprime.

### Method 2

Find integers `x,y` such that:

`ax+by=1`

Then:

`gcd(a,b)=1`

### Method 3

If you can directly construct:

`1=ma+nb`

then immediately conclude:

`gcd(a,b)=1`

---

# Part 40 — Useful GCD Trick for Linear Expressions

Suppose:

`A(n)=an+b`

and:

`B(n)=cn+d`

Consider:

`cA(n)-aB(n)`

Then:

`c(an+b)-a(cn+d)`

`= acn+bc-acn-ad`

`= bc-ad`

Therefore:

`gcd(an+b,cn+d) | (bc-ad)`

If:

`bc-ad = ±1`

then:

`gcd(an+b,cn+d)=1`

---

# Part 41 — Relations

A relation `R` from `A` to `B` is a subset of:

`A × B`

A relation tells us which elements are related.

Divisibility is a relation:

`a R b`

if and only if:

`a | b`

---

# Part 42 — Function vs Relation

A function requires:

> **EVERY input has EXACTLY ONE output.**

A relation does not require that.

Divisibility is not a function because one number may divide many numbers.

For example, generally:

`a | b₁`

`a | b₂`

`a | b₃`

etc.

So one input may correspond to multiple outputs.

Therefore:

> **divisibility = relation**

GCD is a function because each input pair has exactly one positive GCD.

Therefore:

> **gcd = function**

---

# Part 43 — Partial Order

A partial order requires:

1. Reflexivity
2. Antisymmetry
3. Transitivity

### Divisibility

**Reflexive:**

`a | a`

**Antisymmetric:**

`a | b` and `b | a` implies `a=b` for positive integers.

**Transitive:**

`a | b` and `b | c` implies `a | c`

Therefore divisibility on positive integers is a partial order.

It is **NOT** generally a total order because two numbers may be incomparable.

For some `a,b`:

`a` does not divide `b`

and:

`b` does not divide `a`

---

# Part 44 — Hasse Diagram

A Hasse diagram represents a partial order.

For divisibility:

`a` is below `b` when:

`a | b`

But we do not draw every relation.

We only draw **COVER relations**.

`a` is covered by `b` if:

`a | b`

and there is no `c` such that:

`a | c | b`

with:

`c` different from `a,b`.

Therefore:

> **HASSE DIAGRAM = partial-order diagram with transitive relations removed.**

---

# Part 45 — General Practice Problem Strategies

### Problem Type 1 — Find `gcd(a,b)`

Use Euclidean algorithm.

`a=bq₁+r₁`

`b=r₁q₂+r₂`

`r₁=r₂q₃+r₃`

…

Last non-zero remainder = GCD.

### Problem Type 2 — Find `x,y` such that `ax+by=d`

Find `d` using Euclidean algorithm.

Back-substitute.

Obtain:

`d=ax+by`

### Problem Type 3 — Determine Whether `ax+by=N` Has a Solution

Calculate:

`d=gcd(a,b)`

If:

`d | N`

solutions exist.

If:

`d` does not divide `N`,

no integer solution exists.

### Problem Type 4 — Prove `gcd(A,B)=1`

Try to find:

`mA+nB=1`

If successful:

`gcd(A,B)=1`

### Problem Type 5 — Prove a Number Is the GCD

Use:

`d | a`

`d | b`

and:

`every common divisor c divides d`

### Problem Type 6 — Prove `gcd(a,b)=gcd(b,r)`

Use:

`r=a-qb`

Then prove common divisor sets are equal.

### Problem Type 7 — Prove Euclidean Algorithm Terminates

Show the remainders satisfy:

`b>r₁>r₂>r₃>…`

A decreasing sequence of positive integers cannot continue indefinitely.

### Problem Type 8 — Construct a Fraction

Use:

**similar triangles + proportionality**

### Problem Type 9 — Construct a Square Root

Use:

**right triangle + Pythagoras**

### Problem Type 10 — Construct `30°,45°,60°,90°`

`90° → perpendicular`

`45° → bisect 90°`

`60° → equilateral triangle`

`30° → bisect 60°`

### Problem Type 11 — Find Smallest Angle Obtainable from `x` and `y`

Use subtraction Euclidean algorithm.

Answer:

`gcd(x,y)`

---

# Part 46 — Regular Hexagon General Idea

A regular hexagon can be divided into six equilateral triangles from its centre.

Total angle around centre:

`360°`

Therefore each central angle is:

`360/6 = 60°`

Each triangle is equilateral.

Therefore each side of the hexagon equals the radius.

### Key Facts

- central angle = `60°`
- radius = side length
- six equal equilateral triangles make the hexagon

---

# Part 47 — Balance / Weight Problems

If two available weights are:

`a` and `b`

then integer combinations have the form:

`ax+by`

The smallest positive integer combination is:

`gcd(a,b)`

A target `N` can be represented as:

`N=ax+by`

if and only if:

`gcd(a,b) | N`

> **IMPORTANT:**  
> If the physical problem restricts `x,y` to non-negative numbers or to a specific balance arrangement, the pure integer-linear-combination theorem alone is not sufficient; the physical constraints must also be checked.

---

# Part 48 — Currency / Note Problems

If available denominations are:

`a` and `b`

then possible integer combinations have form:

`ax+by`

If the problem allows arbitrary integer coefficients:

`N` is possible iff:

`gcd(a,b) | N`

If only non-negative numbers of notes are allowed:

`x>=0`

and:

`y>=0`

must also be satisfied.

So distinguish:

### Number Theory Condition

`gcd(a,b) | N`

### Physical / Real-World Condition

`x,y` satisfy the allowed restrictions.

---

# Part 49 — Fibonacci GCD Idea

Fibonacci numbers:

`F₁=1`

`F₂=1`

`Fₙ=Fₙ₋₁+Fₙ₋₂`

Important theorem:

`gcd(Fₘ,Fₙ)=F_gcd(m,n)`

The reason is connected to Euclidean reduction of the indices.

When `m>n`:

`gcd(Fₘ,Fₙ)`

can be reduced using Fibonacci identities in the same spirit as:

`gcd(m,n)=gcd(n,m-n)`

---

# Part 50 — Final Proof Templates

## Proof Template A — Divisibility

Assume:

`c | a`

and:

`c | b`

Then:

`a=cm`

and:

`b=cn`

Therefore:

`ma+nb = c(mu+nv)`

for suitable integer coefficients.

Hence:

`c | (ma+nb)`

---

## Proof Template B — Subtraction

`a=cm`

`b=cn`

Therefore:

`a-b=c(m-n)`

Hence:

`c | (a-b)`

---

## Proof Template C — GCD Preservation

Let:

`r=a-qb`

If `c` divides `a` and `b`, then:

`c` divides `r`.

If `c` divides `b` and `r`, then:

`c` divides `a=qb+r`

Therefore common divisor sets are identical.

Hence:

`gcd(a,b)=gcd(b,r)`

---

## Proof Template D — Euclidean Algorithm

Repeatedly use:

`a=bq+r`

Replace:

`(a,b)` by `(b,r)`

The GCD remains unchanged.

Since remainders decrease, the algorithm terminates.

The last non-zero remainder is the GCD.

---

## Proof Template E — Bézout

Euclidean algorithm gives:

`d=gcd(a,b)`

Back-substitute until:

`d=ax+by`

Therefore:

`gcd(a,b)=ax+by`

---

## Proof Template F — Linear Combination Solvability

If:

`N=ax+by`

then:

`gcd(a,b) | N`

Conversely, if:

`gcd(a,b) | N`

use Bézout:

`gcd(a,b)=ax₀+by₀`

and multiply by:

`N/gcd(a,b)`

Therefore:

`N=ax+by`

---

## Proof Template G — Quotient / Remainder Uniqueness

Assume:

`a=bq₁+r₁=bq₂+r₂`

Then:

`b(q₁-q₂)=r₂-r₁`

Since:

`-b<r₂-r₁<b`

the only possible multiple of `b` is `0`.

Therefore:

`r₁=r₂`

and:

`q₁=q₂`

---

## Proof Template H — GCD Definition

To prove:

`d=gcd(a,b)`

show:

`d | a`

`d | b`

and:

`c | a, c | b` implies `c | d`

Then:

`d=gcd(a,b)`

---

# Part 51 — Master Formula Bank

## BOOs

| BOO | Meaning |
|---|---|
| **O1** | Join two points |
| **O2** | Intersection of two lines |
| **O3** | Perpendicular bisector |
| **O4** | Angle bisector |
| **O5** | Perpendicular through a point |

## Similarity

Corresponding sides are proportional.

## Pythagoras

`c²=a²+b²`

## Fractions

`1/n → equal auxiliary divisions + similar triangles`

`m/n = m(1/n)`

## Square Roots

`√2=√(1²+1²)`

`√(n+1)=√((√n)²+1²)`

`√(a²+b²) = hypotenuse`

## Angles

`90° → perpendicular`

`45° = 90°/2`

`60° → equilateral triangle`

`30° = 60°/2`

Smallest positive integer angle from `x,y`:

`gcd(x,y)`

## Divisibility

`a | b iff b=ak`

## Transitivity

`a | b` and `b | c → a | c`

## Linear Combination

`c | a` and `c | b → c | (ma+nb)`

## Division

`a=bq+r`

`0≤r<b`

## GCD

`gcd(a,b)=gcd(b,a)`

`gcd(a,b)=gcd(|a|,|b|)`

`gcd(a,b)=gcd(a-b,b)`

`gcd(a,b)=gcd(a-qb,b)`

`gcd(a,b)=gcd(b,a mod b)`

`gcd(ka,kb)=|k|gcd(a,b)`

## Euclidean Algorithm

`a=bq+r`

Repeat:

`(a,b)→(b,r)`

Last non-zero remainder = GCD.

## Bézout

`gcd(a,b)=ax+by`

## Solvability

`ax+by=N`

iff:

`gcd(a,b) | N`

## Coprime

`gcd(a,b)=1`

Equivalent to:

`ax+by=1`

## Partial Order

Reflexive + antisymmetric + transitive.

## Divisibility

Partial order on positive integers.

## Hasse

Draw only cover relations.

---

# Part 52 — Ultra-Short Exam Revision

> ## If You Have Only 10 Minutes Before the Exam

`a | b` means:

`b=ak`

If:

`c | a` and `c | b`

then:

`c | (ma+nb)`

If:

`a=bq+r`

then:

`gcd(a,b)=gcd(b,r)`

Repeat Euclidean algorithm until:

`r=0`

Last non-zero remainder:

`gcd(a,b)`

Back-substitution:

`gcd(a,b)=ax+by`

Therefore:

`ax+by=N`

has an integer solution iff:

`gcd(a,b) | N`

### To prove `d` is GCD

`d | a`

`d | b`

every common divisor `c` divides `d`

### To prove Euclidean algorithm terminates

Remainders strictly decrease.

### To construct `1/n`

Equal divisions + similar triangles.

### To construct square roots

Right triangle + Pythagoras.

### To construct angles

`O5 → 90°`

`O4 → bisect`

`equilateral → 60°`

Smallest positive angle obtained from `x,y`:

`gcd(x,y)`

Divisibility is a relation.

GCD is a function.

Divisibility on positive integers is a partial order.

---

# Part 53 — The Ultimate Memory Map

Remember these four ideas:

## IDEA 1 — DIVISIBILITY IS ABOUT MULTIPLES

`a | b`

means:

`b=ak`

## IDEA 2 — LINEAR COMBINATIONS PRESERVE COMMON DIVISORS

If `c` divides both `a` and `b`:

`c` divides every `ax+by`

## IDEA 3 — EUCLIDEAN ALGORITHM IS JUST SMART SUBTRACTION

`a=bq+r`

means:

`r=a-qb`

Therefore common divisors don't change.

So:

`gcd(a,b)=gcd(b,r)`

## IDEA 4 — THE GCD IS THE SMALLEST POSITIVE LINEAR COMBINATION

`gcd(a,b)=ax+by`

Therefore:

`N` is a linear combination of `a,b`

exactly when:

`gcd(a,b) | N`

---

# 🔗 The Final Chain to Memorise

**DIVISIBILITY**

`a | b` means `b=ak`

↓

**COMMON DIVISORS**

`c | a` and `c | b`

↓

**LINEAR COMBINATION**

`c | (ma+nb)`

↓

**EUCLIDEAN STEP**

`a=bq+r`

↓

**SUBTRACTION**

`r=a-qb`

↓

**COMMON DIVISORS DON'T CHANGE**

`CD(a,b)=CD(b,r)`

↓

**GCD DOESN'T CHANGE**

`gcd(a,b)=gcd(b,r)`

↓

**REPEAT**

Euclidean Algorithm

↓

**LAST NON-ZERO REMAINDER**

`gcd(a,b)`

↓

**BACK-SUBSTITUTION**

`gcd(a,b)=ax+by`

↓

**BÉZOUT**

GCD is an integer linear combination.

↓

**LINEAR EQUATION**

`ax+by=N`

↓

**SOLVABILITY CONDITION**

`gcd(a,b) | N`

---

<div align="right">

**Jinnwooo'**

</div>


