# Mathematics Study Guide 04 — SPLTV, Linear Inequalities and Linear Programming

**Grade X-6 Pre-IB school SAS.** New source inputs: LKPD-SPLTV, DIGIBOOK Ch.5 SPLTV/SPtLDV, LKPD-SPtLDV; official IB AA AHL1.16 (three-equation linear systems) and SL2.1–2.4 (lines, graphing, solutions); Pearson AA HL Ch.1. **Linear programming is REQUIRED by the school kisi-kisi even though it should not be claimed as a distinct IB DP AA core topic.** These notes are original.

## A. Why systems of equations exist — intuition
Suppose three types of fruit have unknown unit prices: $x$, $y$, $z$. One receipt gives one relation, such as $x+y+z=6$. Infinitely many triples satisfy that one equation. Another receipt constrains the possibilities; a third may pin down exactly one triple. **A system of equations asks for values that make ALL equations true at once**, not one equation at a time.

In two variables, one linear equation represents a straight line; two nonparallel lines intersect at exactly one point. In three variables, each equation is a plane in 3D. Three independent planes may intersect at a point.

Possible solution types: **one solution** (unique intersection), **no solution** (contradiction), or **infinitely many solutions** (constraints are dependent). A method that mechanically produces an answer without checking may miss cases.

## B. Solve a three-variable linear system (SPLTV) step by step
Consider the example structure in your assigned SPLTV worksheet:
$$
\begin{aligned}
x+y+z&=6 &&(1)\\
x-y+2z&=7 &&(2)\\
2x+y-z&=2 &&(3).
\end{aligned}
$$
**Intuition:** we want to eliminate one variable from two different pairs and get TWO equations with only two unknowns. There is no magic: adding or subtracting equations known to be true yields other true equations.

Eliminate $y$:
- Add (1) and (2): $\boxed{2x+3z=13}$, call this (4).
- Subtract (1) from (3): $\boxed{x-2z=-4}$, call this (5).

Now (5) gives $x=2z-4$. Substitute into (4):
$$2(2z-4)+3z=13\Rightarrow 7z=21\Rightarrow \boxed{z=3}.$$
Then $x=2(3)-4=\boxed2$, and from (1) $y=6-2-3=\boxed1$.

**CHECK all equations:** $2+1+3=6$, $2-1+6=7$, $4+1-3=2$. Hence $\boxed{(x,y,z)=(2,1,3)}$.

### What to write for method marks
Define unknowns and units; label each equation; show what you added/subtracted; solve the resulting 2-variable system; back-substitute to all three unknowns; substitute the final triple to verify. These are the natural places for **method and accuracy credit** in an IB-style essay.

### A note on the Grade XII advanced worksheet
It also explores Gauss–Jordan row reduction, determinants and inverse matrices. These are valid ways to study linear systems, and IB AA HL mentions matrices/technological approaches. **Do not assume Grade 10 SAS requires advanced matrix calculations simply because the worksheet contains them.** Prioritise elimination/substitution until the teacher specifically says otherwise.

## C. Why an inequality shades a HALF-PLANE
The equation $x+y=6$ describes the boundary line. The inequality $x+y\le6$ describes **every point on or below that line**.

At $(0,0)$, $0+0\le6$ is true, so the origin belongs to that half-plane. At $(5,5)$, $10\le6$ is false, so that point lies in the excluded half-plane. A test point tells you which side to shade.

Boundary notation matters:
- $<$ or $>$: boundary NOT included; typically dashed line.
- $\le$ or $\ge$: boundary included; solid line.

When several inequalities are imposed simultaneously, **the feasible region is the intersection** (overlap) of all the permitted half-planes. No point outside the overlap is an allowable solution.

## D. Linear programming: WHY extrema occur at corners
Imagine choosing production quantities $x,y$ under material and time limits. Each limitation is a linear inequality. We want a choice that is feasible and earns as much as possible. The **objective** is a linear expression such as $P=3x+2y$.

For a bounded convex polygon, a linear objective reaches a maximum and minimum at some corner (and sometimes along an entire edge). Geometric intuition: lines $3x+2y=P$ are parallel. Slide one toward larger $P$ until it touches the feasible polygon for the last time: a vertex or an edge is encountered.

**Caution:** an unbounded feasible region may have no finite maximum; infeasible constraints have no solution. This is also a lesson from the teacher's flawed quadratic maximisation problem.

## E. Fully worked optimization example
Maximize
$$P=3x+2y$$
subject to
$$x\ge0,\qquad y\ge0,\qquad 2x+y\le10,\qquad x+2y\le8.$$

### Step 1: Understand the boundary lines
$2x+y=10$ has intercepts $(5,0)$ and $(0,10)$.
$x+2y=8$ has intercepts $(8,0)$ and $(0,4)$.
Because both inequalities are $\le$, the origin is allowed; because $x,y\ge0$, only the first quadrant is allowed.

### Step 2: Find corners of the common feasible region
The axes and each more restrictive line give $(0,0)$, $(5,0)$ and $(0,4)$.
The two sloping boundary lines intersect where
$$2x+y=10,\quad x+2y=8.$$
Multiply second by 2: $2x+4y=16$. Subtract first: $3y=6\Rightarrow y=2$, then $2x+2=10\Rightarrow x=4$.
So the fourth corner is $(4,2)$.

### Step 3: Evaluate the objective at EVERY corner
| Corner $(x,y)$ | Feasible? | $P=3x+2y$ |
| --- | --- | ---: |
| $(0,0)$ | Yes | $0$ |
| $(5,0)$ | Yes | $15$ |
| $(4,2)$ | Yes | **$16$** |
| $(0,4)$ | Yes | $8$ |

Thus
$$\boxed{P_{\max}=16\text{ at }(x,y)=(4,2)}.$$
Check both limits at that point: $2(4)+2=10$ and $4+2(2)=8$. We **interpret** the answer in words: choose four units of the first activity and two of the second; both constraints are fully utilized.

### Illustrated M/A/R thought process (not an official allocation)
**M:** translate words to decision variables and constraints; draw or compute boundary lines; solve for intersections; evaluate linear objective at feasible corners.
**A:** correct intersections, arithmetic and optimum.
**R:** explain why all chosen points are feasible and why corners suffice for a bounded linear optimization problem; present contextual units.

## F. Linking SPLTV with linear programming without confusing them
**SPLTV** has three unknowns linked by equations (usually three conditions), and asks for an exact triple $(x,y,z)$.
**SPtLDV/linear programming** uses two decision variables with inequalities, gives a *region* of many feasible points, then chooses the best point via an objective. It is NOT the same thing as solving three equations, even when the school teaches them together in one topic.

Both depend on **representation, mathematical modelling, elimination, and accurate checking**.

## G. Five-minute revision memory script
**SPLTV: Pair -> Eliminate -> Solve 2 variables -> Back-substitute -> Check all 3.**
**Linear programming: Define -> Constraints -> Lines -> Common region -> Corners -> Objective -> Interpret.**
**Endpoint habit:** strict inequalities exclude boundary; inclusive inequalities include it.
**Diagram habit:** label axes, lines and units, and only highlight the common overlap.
**IB habit:** "show that" asks you to justify a supplied result with working; "hence" asks you to USE the preceding part.

## H. Optional original attempt after reading
A small workshop produces $x$ notebooks and $y$ bookmarks, with $x,y\ge0$, $x+y\le9$, and $2x+y\le12$. Profit is $P=4x+3y$ dollars. First describe (or sketch) the feasible region, then use each vertex to justify the maximum. Explain the significance of an included boundary point. Try only when you understand the worked example.
