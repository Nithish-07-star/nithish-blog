---
layout: post
title:  " MATHS MIDSEM CONCEPTS"
date:   2026-09-24 
categories: jekyll update
---
### MATHS MIDSEM CONCEPTS - INTRODUCTION TO MATH THINK ...

## courseflow

GEOMETRY
↓
RATIOS
↓
DIVISIBILITY
↓
COMMON DIVISORS
↓
GCD
↓
EUCLIDEAN ALGORITHM
↓
LINEAR COMBINATIONS
↓
BEZOUT IDENTITY
↓
SOLVABILITY OF ax + by = N

==============================================================
|| GENERAL CASES + FORMULAS + PROOFS + CONSTRUCTION METHODS ||
==============================================================
## BOO'S CONCEPTS
# PART 1 — BOOs / BASIC CONSTRUCTIONS

The five BOOs used in the worksheets are:

O1:
Given two points P1 and P2, construct the crease/line joining P1 and P2.

O2:
Given two creases/lines, construct their intersection.

O3:
Given two points P1 and P2, fold P1 onto P2.

The crease obtained is the perpendicular bisector of P1P2.

Therefore every point on the crease is equally distant from P1 and P2.

O4:
Given two creases/lines, fold one onto the other.

The crease obtained is an angle bisector.

O5:
Given a point P and a crease/line L, construct a crease through P perpendicular to L.

IMPORTANT BOO RESULTS:

O3 -> perpendicular bisector

O4 -> angle bisector

O5 -> perpendicular through a given point

Two lines perpendicular to the same line are parallel.

Therefore, to construct a parallel line:

Construct a perpendicular to the given line.
Construct another perpendicular to that perpendicular.
The second line is parallel to the original line.
=============================
 #PART 2 — SIMILAR TRIANGLES

Similar triangles have the same shape but may have different sizes.

Corresponding angles are equal.

Corresponding sides are proportional.

If triangle ABC is similar to triangle DEF, then:

AB/DE = BC/EF = CA/FD

GENERAL IDEA:

If:

a/b = c/d

then:

ad = bc.

MAIN USE IN THIS COURSE:

Similar triangles are used to construct ratios such as:

1/n

m/n

other rational lengths.

============================================================
PART 3 — CONSTRUCTING 1/2

Given AB = 1.

Use O3 on A and B.

O3 gives the perpendicular bisector of AB.

Let it meet AB at M.

Then:

AM = MB.

Also:

AM + MB = AB = 1.

Therefore:

2AM = 1

AM = 1/2.

Hence:

AM = MB = 1/2.

GENERAL IDEA:

To divide a segment into two equal parts, use its perpendicular bisector.

============================================================
PART 4 — GENERAL CONSTRUCTION OF 1/n

Suppose AB = 1.

We want to construct:

1/n.

GENERAL CONSTRUCTION:

Start with AB = 1.
Draw an auxiliary ray from A.
Mark n equal consecutive lengths on this ray.
Let the first point be C1.
Let the nth point be Cn.
Join Cn to B.
Through C1 construct a line parallel to CnB.
Let this parallel meet AB at P.

By similar triangles:

AP/AB = AC1/ACn.

Since:

AC1 = 1 unit

and:

ACn = n units,

we get:

AP/AB = 1/n.

Since:

AB = 1,

AP = 1/n.

Therefore:

AP = 1/n.

IMPORTANT:

The construction works because of proportionality from similar triangles.

Whenever the question asks for 1/n, think:

EQUAL AUXILIARY STEPS + PARALLEL LINE + SIMILAR TRIANGLES.

============================================================
PART 5 — GENERAL CONSTRUCTION OF m/n

First construct:

1/n.

Then copy that length m times.

Therefore:

m/n = m(1/n).

Hence:

m/n can be constructed by repeating the constructed length 1/n exactly m times.

GENERAL FORM:

1/n -> construct unit fraction

m/n -> repeat 1/n m times.

============================================================
PART 6 — PYTHAGORAS

For a right triangle with perpendicular sides a and b and hypotenuse c:

c^2 = a^2 + b^2.

Therefore:

c = sqrt(a^2 + b^2).

MAIN USE:

Constructing square roots.

============================================================
PART 7 — CONSTRUCTING sqrt(2)

Start with a unit segment:

AB = 1.

Construct:

BC = 1

such that:

AB perpendicular BC.

Then triangle ABC is right angled.

By Pythagoras:

AC^2 = AB^2 + BC^2

AC^2 = 1^2 + 1^2

AC^2 = 2.

Therefore:

AC = sqrt(2).

So:

sqrt(2) = diagonal of a unit square.

============================================================
PART 8 — GENERAL CONSTRUCTION OF sqrt(n+1)

Suppose we already have:

AB = sqrt(n).

Construct:

BC = 1

such that:

AB perpendicular BC.

Then:

AC^2 = AB^2 + BC^2

AC^2 = (sqrt(n))^2 + 1^2

AC^2 = n + 1.

Therefore:

AC = sqrt(n+1).

GENERAL FORMULA:

If sqrt(n) is already available, then:

sqrt(n+1) = sqrt((sqrt(n))^2 + 1^2).

So one square root can be used to construct the next one.

============================================================
PART 9 — CONSTRUCTING sqrt(3)/2

Take an equilateral triangle of side 1.

Let its altitude be h.

The altitude bisects the base.

Therefore:

half base = 1/2.

Using Pythagoras:

h^2 + (1/2)^2 = 1^2.

Therefore:

h^2 + 1/4 = 1.

h^2 = 3/4.

Therefore:

h = sqrt(3/4)

h = sqrt(3)/2.

Hence:

sqrt(3)/2 = altitude of an equilateral triangle of side 1.

============================================================
PART 10 — GENERAL SQUARE ROOT STRATEGY

Whenever you are asked to construct sqrt(K), try to express K in the form:

K = a^2 + b^2

or:

K = a^2 - b^2.

Then use a right triangle.

For:

K = a^2 + b^2:

construct perpendicular sides a and b.

The hypotenuse is sqrt(K).

For:

K = a^2 - b^2:

construct a right triangle with hypotenuse a and one side b.

The other side is:

sqrt(a^2 - b^2).

============================================================
PART 11 — ANGLES

BASIC CONSTRUCTIONS:

90 degrees:

Use O5 to construct a perpendicular.

45 degrees:

Start with 90 degrees and use O4 to bisect it.

45 = 90/2.

60 degrees:

Construct an equilateral triangle.

Every angle of an equilateral triangle is:

60 degrees.

30 degrees:

Bisect 60 degrees using O4.

30 = 60/2.

SUMMARY:

90 -> O5

45 -> bisect 90 using O4

60 -> equilateral triangle

30 -> bisect 60 using O4

============================================================
PART 12 — GENERAL ANGLE PROBLEM

Suppose you are given two angles:

x degrees and y degrees.

By adding and subtracting angles, we can form integer combinations:

mx + ny

where:

m,n are integers.

If x > y, replace:

x by x - y.

This does not change the greatest common divisor.

gcd(x,y) = gcd(x-y,y).

Continue.

If y > x:

gcd(x,y) = gcd(x,y-x).

Eventually both become equal to d.

Then:

d = gcd(x,y).

Therefore:

THE SMALLEST POSITIVE INTEGER ANGLE OBTAINABLE FROM x AND y BY INTEGER ADDITION/SUBTRACTION IS gcd(x,y).

This is exactly the same mathematical structure as the subtraction Euclidean algorithm.

============================================================
PART 13 — RECTANGLE / SQUARE METHOD

Suppose a rectangle has side lengths:

a and b

with:

a > b.

Cut/fold squares of side b.

The remaining rectangle has dimensions:

a-b and b.

Therefore:

(a,b) -> (a-b,b).

Continue.

If the remaining side is still larger, subtract again.

Eventually a square remains.

The side length of the final square is:

gcd(a,b).

WHY?

Because:

gcd(a,b) = gcd(a-b,b).

This follows from preservation of common divisors.

============================================================
PART 14 — SUBTRACTION PROPERTY OF DIVISIBILITY

Suppose:

c divides a

and:

c divides b.

Then:

a = cm

and:

b = cn

for some integers m,n.

Subtract:

a-b = cm-cn

a-b = c(m-n).

Therefore:

c divides (a-b).

Hence:

c | a and c | b
implies
c | (a-b).

REVERSE DIRECTION:

Suppose:

c divides (a-b)

and:

c divides b.

Since:

a = (a-b) + b,

we get:

c divides a.

Therefore:

c | (a-b) and c | b
implies
c | a.

IMPORTANT CONCLUSION:

c | a and c | b

if and only if:

c | (a-b) and c | b.

Therefore the set of common divisors does not change.

============================================================
PART 15 — GCD SUBTRACTION PROPERTY

If a > b:

gcd(a,b) = gcd(a-b,b).

More generally:

gcd(a,b) = gcd(a-qb,b)

for any integer q for which the reduction is useful.

Why?

Because:

a-qb

is an integer linear combination of a and b.

The common divisors remain exactly the same.

============================================================
PART 16 — DIVISION ALGORITHM

For positive integers a and b, there exist unique integers q and r such that:

a = bq + r

where:

0 <= r < b.

q is the quotient.

r is the remainder.

IMPORTANT:

The condition:

0 <= r < b

is essential.

============================================================
PART 17 — WHY QUOTIENT AND REMAINDER ARE UNIQUE

Suppose:

a = bq1 + r1

and:

a = bq2 + r2.

Equate them:

bq1 + r1 = bq2 + r2.

Therefore:

b(q1-q2) = r2-r1.

Because:

0 <= r1 < b

and:

0 <= r2 < b,

we have:

-b < r2-r1 < b.

But:

b(q1-q2)

is a multiple of b.

The only multiple of b strictly between -b and b is 0.

Therefore:

r2-r1 = 0.

So:

r1 = r2.

Then:

q1 = q2.

Therefore quotient and remainder are unique.

============================================================
PART 18 — DIVISIBILITY

Definition:

a divides b, written:

a | b

if and only if:

b = ak

for some integer k.

For natural numbers, k is usually taken to be a natural number according to the convention being used.

IMPORTANT:

a | b does NOT mean:

a/b is necessarily a natural number written as a decimal.

It means there exists an integer multiplier k such that:

b = ak.

============================================================
PART 19 — BASIC DIVISIBILITY PROPERTIES

PROPERTY 1: REFLEXIVITY

a | a

because:

a = a(1).

PROPERTY 2: TRANSITIVITY

If:

a | b

and:

b | c,

then:

a | c.

Proof:

b = am

c = bn.

Therefore:

c = amn.

Hence:

a | c.

PROPERTY 3: ADDITION

If:

c | a

and:

c | b,

then:

c | (a+b).

Proof:

a = cm

b = cn.

Therefore:

a+b = c(m+n).

PROPERTY 4: SUBTRACTION

If:

c | a

and:

c | b,

then:

c | (a-b).

Proof:

a-b = c(m-n).

PROPERTY 5: INTEGER LINEAR COMBINATION

If:

c | a

and:

c | b,

then:

c | (ma+nb)

for any integers m,n.

Proof:

a = cu

b = cv.

Then:

ma+nb = mcu + ncv

= c(mu+nv).

Therefore:

c | (ma+nb).

THIS IS THE MASTER DIVISIBILITY PROPERTY.

============================================================
PART 20 — COMMON DIVISORS

A common divisor of a and b is a number c such that:

c | a

and:

c | b.

The set of all common divisors can be thought of as:

CD(a,b).

The GCD is the greatest positive common divisor.

============================================================
PART 21 — DEFINITION OF GCD

d = gcd(a,b)

means:

d divides a.
d divides b.
Every common divisor of a and b divides d.

Formally:

d | a

d | b

and if:

c | a and c | b,

then:

c | d.

This definition is stronger and more useful in proofs than simply saying:

"GCD is the largest common divisor."

============================================================
PART 22 — GCD AND EUCLIDEAN ALGORITHM

Suppose:

a = bq + r.

Then:

r = a - bq.

Therefore:

gcd(a,b) = gcd(b,r).

So:

gcd(a,b) = gcd(b,a mod b).

Repeat.

Eventually:

r = 0.

The last non-zero remainder is the GCD.

GENERAL ALGORITHM:

Input: a,b.

Step 1:
Assume a >= b.

Step 2:
Divide:

a = bq + r.

Step 3:
If r = 0, return b.

Step 4:
Otherwise replace:

a <- b

b <- r.

Step 5:
Repeat.

FINAL ANSWER:

Last non-zero remainder = gcd(a,b).

============================================================
PART 23 — WHY EUCLIDEAN ALGORITHM WORKS

Start with:

a = bq+r.

Take any common divisor c of a and b.

Then:

c | a

and:

c | b.

Therefore:

c | (a-qb).

But:

a-qb = r.

Therefore:

c | r.

So every common divisor of a,b is also a common divisor of b,r.

Conversely, if:

c | b

and:

c | r,

then:

a = bq+r

so:

c | a.

Therefore the common divisor sets are identical.

Hence:

gcd(a,b) = gcd(b,r).

============================================================
PART 24 — WHY EUCLIDEAN ALGORITHM TERMINATES

At each division step:

a = bq+r

with:

0 <= r < b.

Therefore the next remainder is smaller than the previous divisor.

So we get:

b > r1 > r2 > r3 > ...

All are non-negative integers.

A strictly decreasing sequence of positive integers cannot continue forever.

Therefore the algorithm terminates.

============================================================
PART 25 — EA1: SUBTRACTION VERSION

Input:

a,b.

If:

a = b,

return a.

If:

a > b,

replace:

(a,b) -> (a-b,b).

If:

b > a,

replace:

(a,b) -> (a,b-a).

Repeat.

Why does this work?

Because:

gcd(a,b) = gcd(a-b,b)

and:

gcd(a,b) = gcd(a,b-a).

Why does it terminate?

Because a+b decreases at every subtraction.

Since a+b is a positive integer, it cannot decrease forever.

Therefore EA1 terminates.

============================================================
PART 26 — EA2: DIVISION VERSION

Input:

a,b.

Divide:

a = bq+r.

If:

r=0,

then:

gcd(a,b)=b.

Otherwise:

(a,b) -> (b,r).

Repeat.

This is faster than repeated subtraction because one division can replace many subtractions.

============================================================
PART 27 — GCD PROPERTIES

gcd(a,b) = gcd(b,a).

gcd(a,b) = gcd(|a|,|b|).

gcd(a,b) = gcd(a-b,b), when a>b.

gcd(a,b) = gcd(a-qb,b).

gcd(a,b) = gcd(b,a mod b).

gcd(ka,kb) = |k| gcd(a,b).

If:

gcd(a,b)=1,

then a and b are coprime.

============================================================
PART 28 — COPRIME NUMBERS

Two integers a and b are coprime if:

gcd(a,b)=1.

Equivalent statement:

There exist integers x,y such that:

ax+by=1.

Therefore:

gcd(a,b)=1

if and only if:

1 can be expressed as an integer linear combination of a and b.

============================================================
PART 29 — LINEAR COMBINATION

A linear combination of a and b is:

ax+by

where:

x,y are integers.

Define:

L(a,b) = {ax+by : x,y are integers}.

This is the set of all integer linear combinations of a and b.

============================================================
PART 30 — COMMON DIVISOR AND LINEAR COMBINATION

Suppose:

c | a

and:

c | b.

Then:

c | (ax+by)

for every:

x,y in Z.

Proof:

a=cm

b=cn.

Then:

ax+by

= cmx + cny

= c(mx+ny).

Therefore:

c | (ax+by).

IMPORTANT:

Every common divisor of a and b divides every integer linear combination of a and b.

============================================================
PART 31 — BEZOUT IDENTITY

BEZOUT'S IDENTITY:

For integers a,b not both zero, there exist integers x,y such that:

ax+by = gcd(a,b).

Therefore:

gcd(a,b)

is an integer linear combination of a and b.

============================================================
PART 32 — FINDING BEZOUT COEFFICIENTS

GENERAL METHOD:

Run Euclidean algorithm.
Find the last non-zero remainder d.
d is the GCD.
Start from the equation producing d.
Substitute the previous remainder.
Continue backwards.
Eventually express d using only a and b.

Final form:

d=ax+by.

The x and y obtained are Bézout coefficients.

============================================================
PART 33 — MASTER LINEAR COMBINATION THEOREM

The equation:

ax+by=N

has integer solutions if and only if:

gcd(a,b) divides N.

Symbolically:

ax+by=N

has integer solutions

IF AND ONLY IF

gcd(a,b) | N.

PROOF — FORWARD DIRECTION:

Suppose:

N=ax+by.

Let:

d=gcd(a,b).

Then:

d|a

and:

d|b.

Therefore:

d | (ax+by).

Hence:

d|N.

PROOF — REVERSE DIRECTION:

Suppose:

d|N.

Then:

N=kd

for some integer k.

By Bezout:

d=ax0+by0.

Therefore:

N=k(ax0+by0).

So:

N=a(kx0)+b(ky0).

Therefore integer solutions exist.

============================================================
PART 34 — THE SET L(a,b) AND GCD

Consider:

L(a,b) = {ax+by : x,y in Z}.

There are positive elements in this set when a,b are not both zero.

By the well-ordering principle, there is a smallest positive element.

Call it d.

So:

d=ax+by.

SHOW d DIVIDES a:

Use division algorithm:

a=qd+r

where:

0 <= r < d.

Then:

r=a-qd.

Since a is in L(a,b) and d is in L(a,b), r is also in L(a,b).

But d is the smallest positive element.

Therefore r cannot be positive.

So:

r=0.

Hence:

d|a.

Similarly:

d|b.

NOW TAKE ANY COMMON DIVISOR c:

Suppose:

c|a

and:

c|b.

Since:

d=ax+by,

we know:

c|d.

Therefore every common divisor divides d.

Thus:

d=gcd(a,b).

FINAL RESULT:

The smallest positive element of L(a,b) is:

gcd(a,b).

============================================================
PART 35 — THE COMPLETE CONNECTION

START:

a,b.

DIVISIBILITY:

If c divides a and b, then c divides every:

ma+nb.

Therefore integer linear combinations preserve common divisors.

EUCLIDEAN STEP:

a=bq+r.

Therefore:

r=a-qb.

Since r is a linear combination of a and b, the common divisors remain unchanged.

Hence:

gcd(a,b)=gcd(b,r).

REPEAT:

Euclidean algorithm.

Eventually:

last non-zero remainder = gcd(a,b).

BACK-SUBSTITUTION:

Since every remainder is a linear combination of earlier numbers:

gcd(a,b)=ax+by.

BEZOUT:

Therefore the GCD is an integer linear combination.

SOLVABILITY:

ax+by=N

is solvable exactly when:

gcd(a,b)|N.

THE COMPLETE CHAIN:

DIVISIBILITY
↓
INTEGER LINEAR COMBINATIONS
↓
SUBTRACTION PROPERTY
↓
DIVISION PROPERTY
↓
EUCLIDEAN ALGORITHM
↓
GCD
↓
BACK-SUBSTITUTION
↓
BEZOUT IDENTITY
↓
ax+by = N
↓
gcd(a,b) | N

============================================================
PART 36 — HOW TO PROVE SOMETHING IS THE GCD

If a question says:

"Prove d = gcd(a,b)."

Do exactly this:

STEP 1:

Show:

d|a.

STEP 2:

Show:

d|b.

STEP 3:

Take an arbitrary common divisor c.

Assume:

c|a

and:

c|b.

STEP 4:

Prove:

c|d.

STEP 5:

Conclude:

d=gcd(a,b).

DO NOT ONLY SAY:

"d is the largest common divisor."

The divisibility characterization is much more useful for proofs.

============================================================
PART 37 — HOW TO PROVE TWO GCDs ARE EQUAL

To prove:

gcd(a,b)=gcd(c,d),

one powerful method is to show that the two pairs have exactly the same common divisors.

Show:

x divides a and b

if and only if

x divides c and d.

Then their common divisor sets are identical.

Therefore their GCDs are equal.

For Euclidean algorithm:

gcd(a,b)=gcd(b,r)

because:

CD(a,b)=CD(b,r).

============================================================
PART 38 — HOW TO PROVE A NUMBER IS NOT THE GCD

If someone claims:

d=gcd(a,b),

try to find a contradiction.

Either:

d does not divide a,
d does not divide b,
there is another common divisor larger than d,
or a common divisor does not divide d.

Any one of these disproves the claim.

============================================================
PART 39 — HOW TO PROVE TWO NUMBERS ARE COPRIME

METHOD 1:

Run Euclidean algorithm.

If final GCD = 1:

gcd(a,b)=1.

Therefore they are coprime.

METHOD 2:

Find integers x,y such that:

ax+by=1.

Then:

gcd(a,b)=1.

METHOD 3:

If you can directly construct:

1 = ma+nb,

then immediately conclude:

gcd(a,b)=1.

============================================================
PART 40 — USEFUL GCD TRICK FOR LINEAR EXPRESSIONS

Suppose:

A(n)=an+b

and:

B(n)=cn+d.

Consider:

cA(n)-aB(n).

Then:

c(an+b)-a(cn+d)

= acn+bc-acn-ad

= bc-ad.

Therefore:

gcd(an+b,cn+d)

divides:

bc-ad.

So:

gcd(an+b,cn+d) | (bc-ad).

If:

bc-ad = ±1,

then:

gcd(an+b,cn+d)=1.

============================================================
PART 41 — RELATIONS

A relation R from A to B is a subset of:

A x B.

A relation tells us which elements are related.

Divisibility is a relation:

a R b

if and only if:

a | b.

============================================================
PART 42 — FUNCTION VS RELATION

A function requires:

EVERY input has EXACTLY ONE output.

A relation does not require that.

Divisibility is not a function because one number may divide many numbers.

For example, generally:

a|b1,

a|b2,

a|b3,

etc.

So one input may correspond to multiple outputs.

Therefore:

divisibility = relation.

GCD is a function because each input pair has exactly one positive GCD.

Therefore:

gcd = function.

============================================================
PART 43 — PARTIAL ORDER

A partial order requires:

Reflexivity
Antisymmetry
Transitivity

DIVISIBILITY:

Reflexive:

a|a.

Antisymmetric:

a|b and b|a implies a=b for positive integers.

Transitive:

a|b and b|c implies a|c.

Therefore divisibility on positive integers is a partial order.

It is NOT generally a total order because two numbers may be incomparable.

For some a,b:

a does not divide b

and:

b does not divide a.

============================================================
PART 44 — HASSE DIAGRAM

A Hasse diagram represents a partial order.

For divisibility:

a is below b when:

a|b.

But we do not draw every relation.

We only draw COVER relations.

a is covered by b if:

a|b

and there is no c such that:

a|c|b

with:

c different from a,b.

So:

HASSE DIAGRAM = partial-order diagram with transitive relations removed.

============================================================
PART 45 — GENERAL PRACTICE PROBLEM STRATEGIES

PROBLEM TYPE 1:

"Find gcd(a,b)."

METHOD:

Use Euclidean algorithm.

a=bq1+r1

b=r1q2+r2

r1=r2q3+r3

...

last non-zero remainder = gcd.

PROBLEM TYPE 2:

"Find x,y such that ax+by=d."

METHOD:

Find d using Euclidean algorithm.
Back-substitute.
Obtain:

d=ax+by.

PROBLEM TYPE 3:

"Determine whether ax+by=N has a solution."

METHOD:

Calculate:

d=gcd(a,b).

If:

d|N,

solutions exist.

If:

d does not divide N,

no integer solution exists.

PROBLEM TYPE 4:

"Prove gcd(A,B)=1."

Try to find:

mA+nB=1.

If successful:

gcd(A,B)=1.

PROBLEM TYPE 5:

"Prove a number is the gcd."

Use:

d|a

d|b

and:

every common divisor c divides d.

PROBLEM TYPE 6:

"Prove gcd(a,b)=gcd(b,r)."

Use:

r=a-qb.

Then prove common divisor sets are equal.

PROBLEM TYPE 7:

"Prove Euclidean algorithm terminates."

Show the remainders satisfy:

b>r1>r2>r3>...

A decreasing sequence of positive integers cannot continue indefinitely.

PROBLEM TYPE 8:

"Construct a fraction."

Use:

similar triangles + proportionality.

PROBLEM TYPE 9:

"Construct a square root."

Use:

right triangle + Pythagoras.

PROBLEM TYPE 10:

"Construct 30,45,60,90 degrees."

90 -> perpendicular

45 -> bisect 90

60 -> equilateral triangle

30 -> bisect 60.

PROBLEM TYPE 11:

"Find smallest angle obtainable from x and y."

Use subtraction Euclidean algorithm.

Answer:

gcd(x,y).

============================================================
PART 46 — REGULAR HEXAGON GENERAL IDEA

A regular hexagon can be divided into six equilateral triangles from its centre.

Total angle around centre:

360 degrees.

Therefore each central angle is:

360/6 = 60 degrees.

Each triangle is equilateral.

Therefore each side of the hexagon equals the radius.

Key facts:

central angle = 60 degrees

radius = side length

six equal equilateral triangles make the hexagon.

============================================================
PART 47 — BALANCE / WEIGHT PROBLEMS

If two available weights are:

a and b,

then integer combinations have the form:

ax+by.

The smallest positive integer combination is:

gcd(a,b).

A target N can be represented as:

N=ax+by

if and only if:

gcd(a,b)|N.

IMPORTANT:

If the physical problem restricts x,y to non-negative numbers or to a specific balance arrangement, the pure integer-linear-combination theorem alone is not sufficient; the physical constraints must also be checked.

============================================================
PART 48 — CURRENCY / NOTE PROBLEMS

If available denominations are:

a and b,

then possible integer combinations have form:

ax+by.

If the problem allows arbitrary integer coefficients:

N is possible iff:

gcd(a,b)|N.

If only non-negative numbers of notes are allowed:

x>=0

and:

y>=0

must also be satisfied.

So distinguish:

NUMBER THEORY CONDITION:

gcd(a,b)|N.

PHYSICAL/REAL-WORLD CONDITION:

x,y satisfy the allowed restrictions.

============================================================
PART 49 — FIBONACCI GCD IDEA

Fibonacci numbers:

F1=1

F2=1

Fn=Fn-1+Fn-2.

Important theorem:

gcd(Fm,Fn)=F_gcd(m,n).

The reason is connected to Euclidean reduction of the indices.

When m>n:

gcd(Fm,Fn)

can be reduced using Fibonacci identities in the same spirit as:

gcd(m,n)=gcd(n,m-n).

============================================================
PART 50 — FINAL PROOF TEMPLATES

PROOF TEMPLATE A — DIVISIBILITY

Assume:

c|a and c|b.

Then:

a=cm

and:

b=cn.

Therefore:

ma+nb = c(mu+nv)

for suitable integer coefficients.

Hence:

c|(ma+nb).

PROOF TEMPLATE B — SUBTRACTION

a=cm

b=cn.

Therefore:

a-b=c(m-n).

Hence:

c|(a-b).

PROOF TEMPLATE C — GCD PRESERVATION

Let:

r=a-qb.

If c divides a and b, then:

c divides r.

If c divides b and r, then:

c divides a=qb+r.

Therefore common divisor sets are identical.

Hence:

gcd(a,b)=gcd(b,r).

PROOF TEMPLATE D — EUCLIDEAN ALGORITHM

Repeatedly use:

a=bq+r.

Replace:

(a,b) by (b,r).

The GCD remains unchanged.

Since remainders decrease, the algorithm terminates.

The last non-zero remainder is the GCD.

PROOF TEMPLATE E — BEZOUT

Euclidean algorithm gives:

d=gcd(a,b).

Back-substitute until:

d=ax+by.

Therefore:

gcd(a,b)=ax+by.

PROOF TEMPLATE F — LINEAR COMBINATION SOLVABILITY

If:

N=ax+by,

then:

gcd(a,b)|N.

Conversely, if:

gcd(a,b)|N,

use Bézout:

gcd(a,b)=ax0+by0

and multiply by N/gcd(a,b).

Therefore:

N=ax+by.

PROOF TEMPLATE G — QUOTIENT/REMAINDER UNIQUENESS

Assume:

a=bq1+r1=bq2+r2.

Then:

b(q1-q2)=r2-r1.

Since:

-b<r2-r1<b,

the only possible multiple of b is 0.

Therefore:

r1=r2

and:

q1=q2.

PROOF TEMPLATE H — GCD DEFINITION

To prove:

d=gcd(a,b),

show:

d|a

d|b

and:

c|a,c|b implies c|d.

Then:

d=gcd(a,b).

============================================================
PART 51 — MASTER FORMULA BANK

BOOs:

O1 = join two points

O2 = intersection of two lines

O3 = perpendicular bisector

O4 = angle bisector

O5 = perpendicular through a point

SIMILARITY:

corresponding sides are proportional.

PYTHAGORAS:

c^2=a^2+b^2.

FRACTIONS:

1/n -> equal auxiliary divisions + similar triangles.

m/n = m(1/n).

SQUARE ROOTS:

sqrt(2)=sqrt(1^2+1^2).

sqrt(n+1)=sqrt((sqrt(n))^2+1^2).

sqrt(a^2+b^2) = hypotenuse.

ANGLES:

90 -> perpendicular.

45 = 90/2.

60 -> equilateral triangle.

30 = 60/2.

smallest positive integer angle from x,y = gcd(x,y).

DIVISIBILITY:

a|b iff b=ak.

TRANSITIVITY:

a|b and b|c -> a|c.

LINEAR COMBINATION:

c|a and c|b -> c|(ma+nb).

DIVISION:

a=bq+r

0<=r<b.

GCD:

gcd(a,b)=gcd(b,a).

gcd(a,b)=gcd(|a|,|b|).

gcd(a,b)=gcd(a-b,b).

gcd(a,b)=gcd(a-qb,b).

gcd(a,b)=gcd(b,a mod b).

gcd(ka,kb)=|k|gcd(a,b).

EUCLIDEAN ALGORITHM:

a=bq+r.

Repeat:

(a,b)->(b,r).

Last non-zero remainder = gcd.

BEZOUT:

gcd(a,b)=ax+by.

SOLVABILITY:

ax+by=N

iff:

gcd(a,b)|N.

COPRIME:

gcd(a,b)=1.

Equivalent to:

ax+by=1.

PARTIAL ORDER:

reflexive + antisymmetric + transitive.

DIVISIBILITY:

partial order on positive integers.

HASSE:

draw only cover relations.

============================================================
PART 52 — ULTRA-SHORT EXAM REVISION

If you have only 10 minutes before the exam, memorise this:

a|b means:

b=ak.

If:

c|a and c|b,

then:

c|(ma+nb).

If:

a=bq+r,

then:

gcd(a,b)=gcd(b,r).

Repeat Euclidean algorithm until:

r=0.

Last non-zero remainder:

gcd(a,b).

Back-substitution:

gcd(a,b)=ax+by.

Therefore:

ax+by=N

has an integer solution iff:

gcd(a,b)|N.

To prove d is GCD:

d|a

d|b

every common divisor c divides d.

To prove Euclidean algorithm terminates:

remainders strictly decrease.

To construct 1/n:

equal divisions + similar triangles.

To construct square roots:

right triangle + Pythagoras.

To construct angles:

O5 -> 90

O4 -> bisect

equilateral -> 60.

Smallest positive angle obtained from x,y:

gcd(x,y).

Divisibility is a relation.

GCD is a function.

Divisibility on positive integers is a partial order.

============================================================
PART 53 — THE ULTIMATE MEMORY MAP

Remember these four ideas:

IDEA 1:

"DIVISIBILITY IS ABOUT MULTIPLES."

a|b

means:

b=ak.

IDEA 2:

"LINEAR COMBINATIONS PRESERVE COMMON DIVISORS."

If c divides both a and b:

c divides every ax+by.

IDEA 3:

"EUCLIDEAN ALGORITHM IS JUST SMART SUBTRACTION."

a=bq+r

means:

r=a-qb.

Therefore common divisors don't change.

So:

gcd(a,b)=gcd(b,r).

IDEA 4:

"THE GCD IS THE SMALLEST POSITIVE LINEAR COMBINATION."

gcd(a,b)=ax+by.

Therefore:

N is a linear combination of a,b

exactly when:

gcd(a,b)|N.

============================================================
THE FINAL CHAIN TO MEMORISE

DIVISIBILITY

a|b means b=ak.

    ↓

COMMON DIVISORS

c|a and c|b.

    ↓

LINEAR COMBINATION

c|(ma+nb).

    ↓

EUCLIDEAN STEP

a=bq+r.

    ↓

SUBTRACTION

r=a-qb.

    ↓

COMMON DIVISORS DON'T CHANGE

CD(a,b)=CD(b,r).

    ↓

GCD DOESN'T CHANGE

gcd(a,b)=gcd(b,r).

    ↓

REPEAT

Euclidean Algorithm.

    ↓

LAST NON-ZERO REMAINDER

gcd(a,b).

    ↓

BACK-SUBSTITUTION

gcd(a,b)=ax+by.

    ↓

BEZOUT

GCD is an integer linear combination.

    ↓

LINEAR EQUATION

ax+by=N.

    ↓

SOLVABILITY CONDITION

gcd(a,b)|N.

============================================================
END
