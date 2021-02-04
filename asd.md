---
author:
- Kion Conio
title: Geometry Algebra Pen Notes
---

The Algebra of vectors
======================

Vectors and its Algebraic Operations 
------------------------------------

### Vectors

#### Definition

A quantity with both magnitude and direction is called a vector. e.g.
Force, velocity, acceleration, displacement, etc.

#### Notation

Directed line segment: $\rightarrow$. We could draw a graph to make our
proof.

-   A directed line segment has a Initial point and a Terminal point.

-   $\overrightarrow{AB}$. An arrow upper the letters.

-   $\bold \alpha$: bold and lower case Roman letter.

-   Sometimes, $\vec a,\underline u$

-   Magnitude, size, length: $|\bold \alpha|,|\overrightarrow {AB}|$

#### Relevent Concepts

Two vectors are equal if and only if their magnitude and direction are
the same. No matter where they start.

The vector with zero magnitude is called the **zero vector**, denoted by
$\bold 0$. $\bold 0$ is the only vector is the only vector with specific
direction.We have: $$\overrightarrow {AB}=\vec 0 \iff A=B$$

A vector with magnitude $1$ is called **unit vector**.

A vector having the same length, but opposite direction of $\vec a$, is
called the negative of $\vec a$, denoted by $-\vec a$. $-\vec a$. Its a
whole notation, not an operation. Thus

$$\overrightarrow  {AB}= - \overrightarrow  {BA}$$

### Operations

#### Addition of vectors

The sum of two vectors $\vec a$ and $\vec{b}$ written as

$$\vec a +\vec b = \vec c$$ $\vec c$ is a vector.

Defined by **triangle method**, that is
$$\overrightarrow  {AB}+\overrightarrow  {BC}=\overrightarrow  {AC}$$

Defined by **parallelogram method** \...

#### Proposition of Vectors

For vectors $\vec a$ , $\vec b$ , and $\vec c$, the addition satisfies:

-   $\vec a+\vec b =\vec b+\vec a$ , commutative law,

-   $(\vec a+\vec b)+\vec c= \vec a+(\vec b+\vec c)$, association law.

-   $\vec a+\vec 0=\vec a$

-   $\vec a+(-\vec a)=\vec 0$

-   Vectors with addition is an abel group.

First two we draw a graph to prove it. Then we prove the rest ones.

3\. Set $\vec a= \overrightarrow  {AB}$ and
$\vec 0 = \overrightarrow  {BB}$. Then
$\vec a +\vec 0 = \overrightarrow  {AB} +\overrightarrow  {BB}=\overrightarrow {AB}= \vec a$

4\. Set $\vec a=\overrightarrow {AB}$. Then $-\vec a = \vec {BA}$. Thus,
$\vec a+(-\vec a)=\vec{AB}+\vec{BA}=\vec 0$

#### Definition

We can define the difference of two vectors $\vec a$ and $\vec b$ to be
$\vec a-\vec b= \vec a +(-\vec b)$

#### Triangular Inequality

For any vectors $\vec a$ and $\vec b$, we have
$$|\vec a +\vec b|\leq |\vec a|+|\vec b|$$

Scalar multiplication
---------------------

#### Definition

The product of vector $\vec a$ and a scalar $\lambda$, wirtten as
$\lambda \vec a$, is a vector, defined by
$$|\lambda \vec a|= |\lambda||\vec a|$$

#### Direction

-   $\lambda >0$, $\lambda \vec a$ has the same direction as $\vec a$

-   $\lambda <0$, $\lambda \vec a$ has the opposite direction as
    $\vec a$

#### Proposition

-   $\lambda \vec a =\vec 0 \iff \lambda = 0 \quad or \quad  \vec  a = \vec 0$

-   $1 \ \vec a=\vec a,\quad (-1)\vec a = - \vec  a$

-   $\lambda（\mu \vec a ) = (\lambda \mu )\vec  a$

-   $(\lambda + \mu )\vec  a = \lambda \vec a  + \mu \vec a$
    distributive law

-   $\lambda (\vec  a + \vec  b)= \lambda \vec a + \lambda \vec  b$
    distributive law

#### Proof

-   $\lambda \vec a  = \vec  0  \iff |\lambda \vec a | = |\vec 0 | =0 \iff |\lambda||\vec  a|=0 \iff |\lambda |=0 \quad or \quad |\vec a|=0\iff \lambda =0 \quad \vec  a = \vec 0$.

-   

-   \...

-   $|\lambda (\mu \vec a )|= |\lambda ||\mu \vec  a |\\= |\lambda||\mu||\vec  a |\\= (|\lambda ||\mu|)|\vec a|\\= |(\lambda \mu)\vec a|$

    That is, $\lambda (\mu \vec  a )$ and $(\lambda \mu )\vec a$ has the
    same **length**.

    Then we consider the **direction**.

     Case 1. $\lambda \mu=0$,
    $\vec 0 =(\lambda \mu )\vec  a= \lambda (\mu \vec a )$

     Case 2. $\lambda \mu >0$, Trivially, $\lambda (\mu \vec  a )$has
    the same direction as $\vec  a$;

     $(\lambda \mu) \vec  a$has the same direction as $\vec  a$;

     Case 3. $\lambda \mu <0$, Trivially, $\lambda (\mu \vec  a )$has
    the opposite direction of $\vec  a$;

     $(\lambda \mu) \vec  a$has the opposite direction of $\vec  a$;

     Thus, we can see that $\lambda (\mu \vec  a )$ has the same
    direction as $(\lambda \mu) \vec  a$.

     Hence,
    $$(- \lambda )\vec a  =  (-1)\lambda \vec a  = (-1)(\lambda \vec a)= -\lambda \vec a$$

    If $\lambda =0 \quad or\quad  \mu =0 \quad or \quad \vec a =\vec 0$,
    it is easily to see that
    $(\lambda + \mu )\vec  a = \lambda \vec a  + \mu \vec a$.

    consider
    $\lambda \neq 0 \quad or\quad  \mu \neq 0 \quad or \quad \vec a \neq \vec 0$.

     $1^{\circ}$ assume that $\lambda >0 , \mu >0$ then,
    $$|(\lambda + \mu)\vec a |= |\lambda +\mu ||\vec a |$$
    $$= (\lambda +\mu )|\vec a |$$ $$= \lambda |\vec a |+\mu |\vec a |$$
    $$= |\lambda||\vec a| + |\mu | |\vec  a |$$
    $$= |\lambda \vec a | + |\mu \vec a |\quad (for \quad  \vec a \parallel \vec a)$$
    $$= |\lambda \vec a +\mu \vec a |$$  $2^{\circ}$ If one of
    $\lambda ,\mu$ is negative, we can put the terms containing the
    negative scalars to the other side of the equation.

     For example:

     $\lambda >0 , \mu <0,\lambda +\mu <0$
    $$(\lambda +\mu )\vec a = \lambda \vec a +\mu \vec a \iff -\mu \vec a  = \lambda \vec a +[-(\lambda +\mu )\vec a ]$$
    $$\iff \lambda \vec  a +(-(\lambda + \mu ))\vec a  = (-\mu) \vec a$$

     (which back to the case of
    $\lambda >0 , \mu >0 ,\lambda + \mu >0$)

-   Case 1: $\lambda = 0$,or $\vec a = \vec 0$, or $\vec b= \vec 0$

    Case 2:$\lambda \neq 0$,or $\vec a \neq \vec 0$, or
    $\vec b\neq \vec 0$

    $\lambda( \vec  a + \vec  b) = \lambda \vec a +\lambda \vec b$(Graph\...(similarity
    of triangle))

Collinear and Coplanar Vectors
------------------------------

#### Definition

When we move some vectors to the same initial point, if they are on the
same line or plane, then we say these vectors are **collinear** or
**coplanar**.

Trivially,

-   $\vec 0$ Is collinear with any vector.

-   Collinear vectors must be coplanar.

-   Any two vectors must be coplanar.

###  Collinear Vectors

#### Notation

two vectors are collinear $\iff$ their directions are the same or
opposite. We write $\vec a \parallel \vec b$

#### Proposition

For vectors $\vec a$ and $\vec  b$ , if there exists a scalar $\lambda$
$s.t.$ $\vec b = \lambda \vec a$, then $\vec a , \vec b$ are collinear.

#### Theorem

(Existence): Assume that $\vec a \neq \vec 0$. If $\vec a, \vec b$
collinear, then there exists scalar
$\lambda \quad s.t. \quad  \vec b = \lambda \vec a$.

#### Proof

If $\vec b = \vec 0$, then $\lambda =0$

Consider $\vec b \neq \vec 0$, then

$$\vec{b}=|\vec{b}| \frac{\vec{b}}{|\vec{b}|}=\left\{\begin{array}{ll}
\frac{\vec{b}}{|\vec{a}|}, & \vec{a} \text { and } \vec{b} \text { have the same direction } \\
\frac{-|\vec{b}|}{|\vec{a}|}, & \vec{a} \text { and } \vec{b} \text { have the opposite direction }
\end{array}\right.$$

(Uniqueness): Assume that $\vec b = \lambda ' \vec a$ Then

$$(\lambda -\lambda ' )\vec a  = \vec 0 \\
  For \quad \vec a \neq \vec 0 \\
  \Rightarrow  \quad \lambda = \lambda '$$

### Three coplanar Vectors

#### Proposition

For vectors $\vec a, \vec b ,\vec c$ if there exists scalar
$\lambda , \mu$, such that $\vec c = \lambda \vec a +\mu \vec b$, then
$\vec a, \vec b, \vec c$ are coplanar. (Graph\...)

#### Proof

If $\vec a  = \vec 0$, then $\vec c = \lambda \vec  b$, so vectors
$\vec  b \parallel \vec  c$, then $\vec  a, \vec  b, \vec  c$ are
Coplanar;

If $\vec  a \neq \vec  0$, then consider two cases:

Case 1: $\vec  a \parallel \vec  b$. Thus, there exist $k$ s.t.
$\vec  b = k \vec  a$.

Hence,
$\vec  c = \lambda \vec  a + \mu \vec  b = \lambda \vec  a +\mu k \vec  a  = (\lambda + \mu k ) \vec  a$
.

Therefore, $\vec c \parallel \vec  a$.

Case 2: $\vec  a \not \parallel \vec  b$, then $\vec  c$ is the diagrod
of the parallelogram formed by $\lambda \vec  a, \mu \vec  b$

#### Theorem

Assume that $\vec a, \vec b$ are **not collinear**, then for any vector
$\vec c$ on the plane determined by $\vec a$ and $\vec b$ , there exist
**unique** scalars $\lambda , \mu \quad s.t. \quad$

$$\vec c = \lambda \vec a + \mu \vec b$$

#### Proof

$1^{\circ}$We first prove the existence of $\lambda, \mu$.

(Graph\...)

We can wrote
$\vec c = \vec  c_1+ \vec  c_2, \vec c_1 \parallel \vec a, \vec c_2 \parallel \vec  b$,

Since $\vec a,\vec  b \neq \vec  0$,

$\exists \lambda,\mu,\quad \vec c_1 = \lambda \vec a, \vec c_2 = \mu \vec b$

Then, $\vec c = \lambda \vec  a+\mu \vec  b$

$2^{\circ}$Suppose that $\vec c = \lambda ' \vec  a+\mu '\vec  b$

We see that
$(\lambda - \lambda ')\vec  a +(\mu - \mu ')\vec b  = \vec  0$

If $\lambda \neq \lambda '$, then
$$\vec a  = - \frac {\mu - \mu '}{\lambda - \lambda  ' }\vec b$$ then
$\vec a \parallel \vec b$, which is a contradiction.

thus, $\lambda = \lambda '$, we have $(\mu - \mu ')\vec b = \vec 0$

Since $\vec b \neq \vec 0 , \mu = \mu '$

### Three Non-coplanar Vectors

#### Theorem

If $\vec a, \vec b , \vec c$ are not coplaner, then or any vector
$\vec u$, there exist unique scalars $\lambda,\mu,\nu$,s.t.
$$\vec u =\lambda \vec a+ \mu \vec b + \nu \vec c$$

#### Proof

$1^{\circ}$Existence of $\lambda,\mu ,\nu$

 (Graph\...)

 $2^{\circ}$Assume that
$$\vec u = (\lambda  - \lambda^*)\vec a + (\mu - \mu^*)\vec b + (\nu - \nu^*)\vec c$$
​ Suppose $\lambda \neq \lambda^*$ , then
$$\vec a  = - \frac{\mu - \mu^*}{\lambda- \lambda^*}\vec b - \frac {\nu - \nu^*}{\lambda - \lambda^*}\vec c$$
​ Showing that $\vec a,\vec b \vec c$. are coplaner. This is a
contradiction.

 Hence, $\lambda = \lambda ^*$,We have
$$(\mu - \mu ^*)\vec b + (\nu - \nu ^*)\vec c = \vec 0$$ ​ Using the
similar argument in the proof of the last theorem, we know that
$\mu = \mu ^*,\nu = \nu ^*\quad (\vec b \not \parallel \vec c)$

### Three Points on the same line

Point $C$ is on the line segment $AB$ if and only if there exist scalar
$\lambda ,\mu \geq 0 \quad (\lambda + \mu = 1)$ s.t.
$$\overrightarrow{OC} = \lambda \overrightarrow{OA} + \mu \overrightarrow{OB}$$
for any point $O$.

#### Proof

Point $C$ is on
$AB \iff \overrightarrow{AC} \parallel \overrightarrow{AB}$.

$$\iff |\overrightarrow{AC}|\leq |\overrightarrow{AB}|$$

$$\iff \exists \mu \in [0,1]  \quad s.t. \quad  \overrightarrow{AC}= \mu \overrightarrow{AB}$$

$$\iff \overrightarrow {OC}-\overrightarrow {OA} = \mu (\overrightarrow{OB}- \overrightarrow{OA})$$

$$\iff \overrightarrow{OC} = (1-\mu)\overrightarrow{OA}+\mu \overrightarrow{OB}$$

$$\iff \overrightarrow{OC} = \lambda \overrightarrow{OA}+ \mu \overrightarrow{OB},\quad (\lambda + \mu  = 1)$$

Affine Coordinate System
------------------------

###  Coordinate System 

By a theorem of **1-2**, if $\vec e_1,\vec e_2,\vec e_3$ are not
coplanar, then for any vector $\vec a$, there exist unique scalar
$a_1,a_2,a_3$ s.t.
$$\vec a  = a_1 \vec e_1+ a_2 \vec e_2 + a_3\vec e_3$$ The ordered
tripe$(a_1,a_2,a_3)$ is called the coordinate of $\vec a$.

It can be show that the mapping $\vec a \mapsto   (a_1,a_2,a_3)$ is a
one-to-one correspondence.

We simply write $\vec a  = (a_1,a_2,a_3)$

Obviously,
$\vec e_1 = (1,0,0),\quad \vec e_2 = (0,1,0), \quad \vec e_3 = (0,0,1)$

Origin + Basis = Coordinate System $$[O,\vec e_1,\vec e_2,\vec e_3]$$ If
$\vec e_1 \bot \vec e_2, \vec e_2 \bot \vec e_3, \vec e_1 \bot \vec e_3$
and $\vec e_1,\vec e_2, \vec e_3$ are unit vectors, then
$[O,\vec e_1,\vec e_2,\vec e_3]$ is called the Cartesian coordinate
system.

### Algebraic Operations Using Coordinate

####  Theorem

In an affine coordinate system$[O,\vec e_1,\vec e_2,\vec e_3]$, assume
that $\vec a = (a_1, a_2, a_3)$ and $\vec b = (b_1, b_2, b_3)$, then,

$$\vec a +\vec b = (a_1+b_1,a_2+b_2,a_3+b_3)$$

####  Proof

$$\vec a + \vec b$$
$$\\ = (a_1\vec e_1 + a_2 \vec e_2 + a_3\vec e_3 )+ (b_1\vec e_1 + b_e \vec b_2 + b_3\vec e_3 )$$
$$\\ = (a_1+b_1)\vec e_1 + (a_2+b_2) \vec e_2 + (a_3+b_3) \vec e_3$$

$k \vec a  = (ka_1,ka_2,ka_3)$

#### Proof

$$k \vec a 
\\ = k(a_1\vec e_1 + a_2 \vec e_2 + a_3\vec e_3)
\\ = k a_1\vec e_1 + k a_2 \vec e_2 + k a_3\vec e_3$$

Corollary Coordinary of $\overrightarrow {AB}$ = Coordinate of $B$ -
Coordinate $A$
$$\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow {OA}$$

now let's assume that we have three vectors $\vec a ,\vec b , \vec c$,

### Scalar Products of Vectors

####  Definition

The scalar product (or inner product, or dot product) of two vectors
$\vec a$ and $\vec b$ is a scalar, denoted by $\vec a \cdot \vec b$, and
is defined by
$$\vec a \cdot \vec b  = |\vec a||\vec b|\cos<\vec a,\vec b >$$ where
$<\vec a,\vec b>\in [0,\pi]$

####  Proposition

-   $\vec a \cdot \vec a  = |\vec a |^2 \geq 0 \Rightarrow |\vec a| = \sqrt{\vec a \cdot \vec a}$

-   $\vec a \cdot \vec b  = \vec b \cdot \vec a$ (commutative)

-   $\vec a \cdot \vec b = 0 \iff \vec a \bot \vec b \quad (\vec 0$ is
    perpendicular to any vectors)

-   Cauchy-Schwarz inequality
    $|\vec a \cdot \vec b| \leq |\vec a|| \vec b|$, the equation holds
    if and only if $\vec a$ is collinear with $\vec b$.

#### Theorem

-   $(\lambda \vec a) \cdot \vec b = \lambda (\vec a \cdot \vec b) = \vec a\cdot (\lambda \vec b)$

-   $\vec a \cdot (\vec b + \vec c) = \vec a \cdot \vec b + \vec a \cdot \vec c$

#### Example

Law of Cosine

In triangle $ABC$
$$\vec c \cdot \vec c = (\vec a + \vec b)^2 = |\vec a|^2+|\vec b|^2+\vec a \cdot \vec b = |\vec a|^2 + |\vec b|^2 - 2|\vec a||\vec b| \cos {C}$$

#### Example

Three height of $\triangle ABC$ concurrent. Claim that
$\overrightarrow{CO}\bot \overrightarrow{AB}$.
$$\overrightarrow {CO} \cdot \overrightarrow{AB} = ... = 0$$

#### Calculate $\vec a \cdot \vec b$ Using Coorinates

In an affine coordinate system $[O,\vec e_1,\vec e_2,\vec e_3]$. Assume
that $\vec a = (a_1,a_2,a_3), \vec b = (b_1,b_2,b_3)$, Then
$$\vec a \cdot \vec b = \sum a_i \vec e_i \cdot \sum b_i \vec e_i = ...$$
In particular, in the Cartesian coordinate system,
$$\vec a \cdot \vec b = \sum a_ib_i$$ Moreover,
$$|\vec a| = \sqrt{\sum a_i^2}$$
$$\cos <\vec a, \vec b> = \frac{\vec a\cdot \vec b}{|\vec a||\vec b|}= \frac{\sum a_ib_i}{\sqrt{\sum a_i^2} \sqrt{\sum b_i^2}}$$

#### Example

In a regular tentrahedron $ABCD$, $E$ is the midpoint of $AB$ and $F$ is
the midpoint of $CD$. Every length equals to $a$. Find
$|\overrightarrow{EF}|$.

Consrruct an affine c.s.
$[A,\overrightarrow{AB},\overrightarrow{AC},\overrightarrow{AD}]$. Write
$$\vec e_1 = \overrightarrow{AB}, \vec e_2 = \overrightarrow{AC},\vec e_3= \overrightarrow{AD}$$
$$\overrightarrow{AF} = \frac{1}{2}(\vec e_2+ \vec e_3)= (0,\frac{1}{2},\frac{1}{2})$$
$$\overrightarrow{AE}= ...$$ Since
$\vec e_i^2= a^2, \vec e_i \cdot \vec e_j = \frac{1}{2} a^2$
$$\overrightarrow{EF}^2= (-\frac{1}{2},\frac{1}{2},\frac{1}{2})^2 = \frac{a^2}{2}$$
Thus $|\overrightarrow{EF}|= \frac{\sqrt{2}}{2}a$

### Vector Product of Vectors

#### Definition

The vector product (or cross product) of two vectors$\vec a$ and
$\vec b$ is a vector, denoted by $\vec a \times \vec b$, and is defined
by
$$\text{magnitude:} |\vec a \times \vec b | = |\vec a| |\vec b| \sin <\vec a,\vec b>  \quad
\text{direction: Right hand rule}$$ Note: $|\vec a \times \vec b| =$
area of parallelogram formed by $\vec a, \vec b$

#### Proposition

-   $\vec a \times \vec b = - \vec b \times \vec a$

-   $\vec a \times \vec b = \vec 0 \iff \vec a \parallel \vec b$

-   $(\lambda \vec a)\times \vec b  = \lambda (\vec a \times \vec b) = \vec a \times (\lambda \vec b)$

-   $\vec a \times (\vec b + \vec c) = \vec a \times \vec b+ \vec a \times \vec c$

#### Introdection to Determinant

$$\left|\begin{array}{ll}
  a_{1,1} & a_{1,2} \\
  a_{2,1} & a_{2,2}
  \end{array}\right|=a_{1,1} a_{2,2}-a_{1,2} a_{2,1}$$

$$\begin{array}{|lll|l}
  a_{1,1} & a_{1,2} & a_{1,3} \\
  a_{2,1} & a_{2,2} & a_{2,3} \\
  a_{3,1} & a_{3,2} & a_{3,3}
  \end{array} 
  =a_{1,1} a_{2,2} a_{3,3}+a_{1,2} a_{2,3} a_{3,1}+a_{1,3} a_{2,1} a_{3,2}-a_{1,3} a_{2,2} a_{3,1}-a_{1,1} a_{2,3} a_{3,2}-a_{1,2} a_{2,1} a_{3,3}$$