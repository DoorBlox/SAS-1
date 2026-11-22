# PRE-IB SAS MATHEMATICS — MASTER FORMULA + DOMAIN CHEAT SHEET

**Grade X-6 | MAN Insan Cendekia Serpong | 23 November 2026.**

**Source priority:** actual school Pre-IB kisi-kisi (15 essays); teacher's 20-question/160-mark IB Prep paper; quadratic teacher formative and 92-mark M/A/R scheme; exponent/log formative; CCC regular paper; 9-page SPtLDV/linear programming LKPD; official IB Mathematics AA guide, Oxford IB Prepared AA §§1.3, 2.3, 2.4; Pearson AA HL 2019 relevant Ch.1, Ch.2, Ch.4 via publisher sample/preview. This is an independently written synthesis, not an official exam formula booklet.

**LATEST TEACHER UPDATE:** **NO SPLTV ON THE REAL SAS**. Linear **inequalities** / graphing feasible regions / linear programming are **still in scope** (not reported excluded). Do not study matrices, row reduction or solving three-variable systems for this Math exam.

**Readability key:** **MEMORIZE** means reconstruct confidently; **CHECK** is a compulsory validity condition; **OPTIONAL** is extension for tough teacher questions. Exact original questions remain in the student's permissioned Drive collection. All content here is original explanations/identities.

---

## 0 — Universal domain and validity checklist

| Expression / situation | Conditions |
|---|---|
| $\dfrac{N(x)}{D(x)}$ | **$D(x)\ne0$** |
| $\sqrt{g(x)}$ over real numbers | **$g(x)\ge0$** |
| $\dfrac{1}{\sqrt{g(x)}}$ | **$g(x)>0$** |
| $\sqrt[n]{g(x)}$ with **even** $n$ | **$g(x)\ge0$** |
| $\sqrt[n]{g(x)}$ with **odd** positive integer $n$ | all real $g(x)$ allowed |
| $\log_a(g(x))$ over real numbers | **$a>0,\ a\ne1,\ g(x)>0$** |
| $\log_{h(x)}g(x)$ with variable base | **$h(x)>0,\ h(x)\ne1,\ g(x)>0$** |
| $a^x$ for arbitrary real $x$ | positive real base $a>0$; $a^x>0$ |
| $f(x)=a x^2+bx+c$ called quadratic | **$a\ne0$** (a parameter may make it zero) |
| physical width/length | usually **$>0$**, plus budget/fence constraints |
| elapsed time | often **$t\ge0$** |
| integer production quantities | $x,y\in\mathbb Z_{\ge0}$; continuous LP vertex may be noninteger |
| strict inequalities $<$, $>$ | boundary points **excluded** |
| inclusive inequalities $\le,\ge$ | boundary points **included** |

**Always:** identify allowable inputs $\rightarrow$ transform/solve $\rightarrow$ test candidates in the **original**, not merely the simplified equation. Squaring, multiplying by a variable, rationalising, taking logs, and substitution may change or mask domain restrictions.

**Dangerous simplifications:**
- $\sqrt{x^2}=\lvert x\rvert$, not necessarily $x$.
- $\sqrt{a+b}\ne\sqrt a+\sqrt b$ generally.
- $\log_a(M+N)\ne\log_a M+\log_a N$ generally.
- $a^m+a^n\ne a^{m+n}$ generally.
- $(a+b)^2\ne a^2+b^2$.
- $(a/b)^{-n}=(b/a)^n$ for nonzero $a,b$; negative exponent is a **reciprocal**, not a negative number.
- $\log_a x$ may be negative even though its **argument** must be positive.
- Never cancel a factor containing $x$ before checking where the factor equals zero; cancellation might remove a solution or make an illegal division.

---

## 1 — Algebraic identities (the foundation)

**MEMORIZE**

```math
\begin{aligned}
(a+b)^2&=a^2+2ab+b^2\\
(a-b)^2&=a^2-2ab+b^2\\
(a+b)(a-b)&=a^2-b^2\\
(a+b)^3&=a^3+3a^2b+3ab^2+b^3\\
(a-b)^3&=a^3-3a^2b+3ab^2-b^3\\
a^3+b^3&=(a+b)(a^2-ab+b^2)\\
a^3-b^3&=(a-b)(a^2+ab+b^2).
\end{aligned}
```

Useful rearrangements:

```math
a^2+b^2=(a+b)^2-2ab=(a-b)^2+2ab
```

```math
(a-b)^2=(a+b)^2-4ab,\qquad
a^3+b^3=(a+b)^3-3ab(a+b).
```

**Special rational-power pattern in teacher Q4:**

```math
\left(\sqrt{x}-\frac1{\sqrt{x}}\right)^2=x-2+\frac1x\quad(x>0).
```

If $s=x+1/x$, then $x^2+1/x^2=s^2-2$, valid for $x\ne0$. This avoids expanding repeatedly.

---

## 2 — Indices, powers, surds and exact values

For $a>0$ and real exponents (quotients require nonzero denominator):

```math
\boxed{a^ma^n=a^{m+n}},\quad
\boxed{\frac{a^m}{a^n}=a^{m-n}},\quad
\boxed{(a^m)^n=a^{mn}}
```

```math
\boxed{(ab)^n=a^nb^n},\quad
\boxed{(a/b)^n=a^n/b^n},\quad
\boxed{a^0=1},\quad
\boxed{a^{-n}=\frac1{a^n}}
```

```math
\boxed{a^{1/n}=\sqrt[n]a},\qquad
\boxed{a^{m/n}=\sqrt[n]{a^m}=(\sqrt[n]a)^m}.
```

Fractional-power formulas are simplest for $a>0$; negative bases with even roots may not be real. For all real $x$, $\sqrt{x^2}=\lvert x\rvert$.

**Common base strategy:** $9^{x+4}=27^{2x-1}$ $\rightarrow$ $3^{2x+8}=3^{6x-3}$ $\rightarrow$ $2x+8=6x-3$. Equality of exponents works for **same positive base $\ne1$**.

**Disguised quadratic:** set $u=a^x>0$ whenever powers of $a^{2x}$ and $a^x$ recur:

```math
a^{2x}+ba^x+c=0\ \rightarrow\ u^2+bu+c=0;\quad u=a^x>0.
```

Reject $u\le0$ before returning to $x$.

**Exact surd rules** for nonnegative $A,B$:

```math
\sqrt{AB}=\sqrt A\sqrt B,\qquad \sqrt{\frac AB}=\frac{\sqrt A}{\sqrt B}\ (B>0).
```

Extract largest square: $\sqrt{72}=6\sqrt2$; combine like surds such as $4\sqrt3+5\sqrt3=9\sqrt3$.

**Conjugates and rationalisation:**

```math
(u+\sqrt v)(u-\sqrt v)=u^2-v
```

```math
\frac{N}{u+\sqrt v}
=\frac{N(u-\sqrt v)}{u^2-v}
\quad\text{provided the original denominator is nonzero.}
```

More generally $(a+b\sqrt c)(a-b\sqrt c)=a^2-b^2c$.

**Geometry used in teacher paper:** rectangle area $A=\ell w$; perimeter $2(\ell+w)$; diagonal $d=\sqrt{\ell^2+w^2}$. Right triangle $c^2=a^2+b^2$. If the aspect ratio $\ell/w=\sqrt2$, then $A=\sqrt2\,w^2$.

---

## 3 — Exponential functions, equations and inequalities

**Base model:** $f(x)=a^x$ with $a>0$, $a\ne1$:
- Domain $\mathbb R$.
- Range $(0,\infty)$.
- $y$-intercept $(0,1)$.
- Horizontal asymptote $y=0$ **not attained**.
- $a>1$: increasing. $0<a<1$: decreasing.

**Transformations / range:**
For $f(x)=A\,a^{B(x-h)}+k$ with $a>0,\ a\ne1,\ A\ne0,\ B\ne0$:
- Horizontal asymptote $y=k$; never reached.
- Domain $\mathbb R$.
- Range $(k,\infty)$ if $A>0$, and $(-\infty,k)$ if $A<0$.
- $h$ controls horizontal translation; $k$ the vertical translation; negative $A$ reflects vertically.
- The sign of $A B\ln a$ determines increasing/decreasing.

**Inequalities — direction of graph matters:**

```math
a^u>a^v\iff u>v\qquad(a>1)
```

```math
a^u>a^v\iff u<v\qquad(0<a<1).
```

With $a^{u(x)}\ge a^{v(x)}$, equality endpoints are included. After solving algebraic inequalities, intersect solution sets with any required domain.

**Growth, depreciation and timescale:**

```math
P(t)=P_0 b^{t/T},\qquad b=1+r,\quad P_0>0,\ T>0,\ b>0.
```

$r=0.25$ means 25% increase per interval $T$; $b=0.8$ means 20% decrease per interval. Solve for time using

```math
t=T\,\frac{\log(P/P_0)}{\log b}\qquad(b\ne1,\ P>0).
```

For repeated halving/doubling use $b=1/2$ or $2$ respectively.

---

## 4 — Logarithms: inverse of exponentiation

**Definition and conditions:**

```math
\boxed{a^y=x\iff\log_a x=y},
\qquad \boxed{a>0,\ a\ne1,\ x>0}.
```

**MEMORIZE:**

```math
\log_a1=0,\qquad \log_a a=1,
```

```math
\log_a(a^x)=x,\qquad a^{\log_a x}=x\ (x>0).
```

For $M,N>0$:

```math
\boxed{\log_a(MN)=\log_aM+\log_aN}
```

```math
\boxed{\log_a(M/N)=\log_aM-\log_aN}
```

```math
\boxed{\log_a(M^r)=r\log_aM}.
```

**CHECK:** The last identity requires $M>0$ for its RHS to be real. If $M\ne0$, $\log_a(M^2)=2\log_a|M|$.

**Change of base:**

```math
\boxed{\log_a x=\frac{\log_b x}{\log_b a}=\frac{\ln x}{\ln a}},\qquad a,b>0,\quad a,b\ne1,\ x>0.
```

**Reciprocal identities / telescoping:**

```math
\log_a b=\frac1{\log_b a}\quad(a,b>0,\ a,b\ne1),
```

```math
\log_a b\cdot\log_b c=\log_a c,
```

```math
\log_{n-1}n\cdot\log_{n-2}(n-1)\cdots\log_2 3=\log_2n.
```

For teacher Q7, chain ending in $\log_{63}64$ yields $\log_2 64=6$.

**Log equations, fixed order:**
1. For EACH log, argument **$>0$**; variable base also $>0$, $\ne1$.
2. Apply product/quotient/power laws.
3. Convert $\log_a F(x)=c$ to $F(x)=a^c$.
4. Solve the algebraic equation; reject candidates violating original restrictions.
5. Check **original** log equation.

**Log graphs:**
- $y=\log_a x$: domain $(0,\infty)$; range $\mathbb R$; vertical asymptote $x=0$; point $(1,0)$.
- If $a>1$, increasing; if $0<a<1$, decreasing.
- For $y=A\log_a(x-h)+k$ with $A\ne0$, domain **$x>h$**, vertical asymptote **$x=h$**, range $\mathbb R$.
- For $y=A\log_a(g(x))+k$, domain **$g(x)>0$**; asymptotes and range require analyzing $g$, not blindly using $x=h$.

**Log inequality direction:**

```math
\log_a u>\log_a v\iff u>v\quad(a>1;\ u,v>0)
```

```math
\log_a u>\log_a v\iff u<v\quad(0<a<1;\ u,v>0).
```

When dividing an inequality by $\log b$ or $\ln b$, check whether that logarithm is positive or negative before deciding the sign.

---

## 5 — Quadratics: equations, graphs, factorisation, discriminant

**Definition:** $f(x)=ax^2+bx+c$, **$a\ne0$**.

**THREE FORMS — all equivalent:**
1. Standard: $ax^2+bx+c$, gives $y$-intercept $(0,c)$.
2. Factored: $a(x-\alpha)(x-\beta)$, when real roots $\alpha,\beta$ exist; gives $(\alpha,0)$, $(\beta,0)$.
3. Vertex: $a(x-h)^2+k$; gives vertex $(h,k)$, axis $x=h$, and optimization.

**Vertex via completing square (MEMORIZE):**

```math
\boxed{h=-\frac b{2a}},\qquad
\boxed{k=f(h)=c-\frac{b^2}{4a}=-\frac{\Delta}{4a}},
```

```math
\boxed{ax^2+bx+c=a\left(x+\frac b{2a}\right)^2-\frac{\Delta}{4a}}.
```

- If $a>0$: minimum $k$, range $[k,\infty)$.
- If $a<0$: maximum $k$, range $(-\infty,k]$.
- Quadratic has domain $\mathbb R$ unless **problem context restricts it**.
- Axis midpoint of real roots: $h=(\alpha+\beta)/2$.

**Roots / discriminant:**

```math
\boxed{\Delta=b^2-4ac},\qquad
\boxed{x=\frac{-b\pm\sqrt\Delta}{2a}}\quad(a\ne0).
```

- $\Delta>0$: two distinct real roots.
- $\Delta=0$: one repeated real root; graph just touches the $x$-axis.
- $\Delta<0$: no real roots (complex conjugate pair if complex numbers permitted).
- Tangent line + parabola: equate line/curve, require resulting **quadratic** to have $\Delta=0$; check leading coefficient isn't zero.
- If requiring **$f(x)\ge0$ for all real $x$** and $a>0$, need $\Delta\le0$.
- If requiring **$f(x)>0$ for all real $x$** and $a>0$, need $\Delta<0$.

**Quadratic inequality sign chart** (two distinct real roots $r_1<r_2$):
- If $a>0$, $f(x)>0$ for $x<r_1$ or $x>r_2$; $f(x)<0$ for $r_1<x<r_2$.
- If $a<0$, **reverse** signs.
- $\ge,\le$ include real roots; $>,<$ exclude roots.
- If $\Delta<0$, a genuine quadratic always has the sign of $a$.

**Basic factoring:**

```math
x^2-Sx+P=(x-\alpha)(x-\beta)\quad\text{if }\alpha+\beta=S,\ \alpha\beta=P.
```

If $a$ is common to **all** coefficients in an equation $ax^2+bx+c=0$, dividing by that nonzero common factor preserves roots; for the original *polynomial factorization*, restore it.

**Slide-and-divide / AC method** (learner-preferred; MEMORIZE):
For integer coefficients $ax^2+bx+c$ with $a\ne0$, find integers $m,n$ such that

```math
m+n=b,\qquad mn=ac.
```

Use the **auxiliary**, generally **not equal** expression:

```math
x^2+bx+ac=(x+m)(x+n).
```

Restore the original polynomial:

```math
\boxed{ax^2+bx+c=a\left(x+\frac ma\right)\left(x+\frac na\right)
=\frac{(ax+m)(ax+n)}a.}
```

Then simplify integer factors. E.g. $6x^2+11x+3$:
$ac=18$, pair $9,2$ $\Rightarrow (x+9)(x+2)$ auxiliary.
Restore: $6(x+9/6)(x+2/6)=\boxed{(2x+3)(3x+1)}$.

**Equivalent split-middle-term:** $ax^2+bx+c=ax^2+mx+nx+c$, then factor by grouping, with the SAME $m+n=b,\ mn=ac$.

---

## 6 — Vieta, transformed roots, new quadratic equations

If roots of $ax^2+bx+c=0$ are $\alpha,\beta$ (possibly complex):

```math
\boxed{S=\alpha+\beta=-\frac ba},\qquad
\boxed{P=\alpha\beta=\frac ca}.
```

The root-to-factor identity follows from $f(x)=a(x-\alpha)(x-\beta)$ and coefficient comparison.

**Basic new equation from roots $u,v$:**

```math
\boxed{t^2-(u+v)t+uv=0}.
```

This is the **monic** version. Any nonzero multiple has the same roots; $a$ matters when describing the original *function*, but not the zero set of the equation.

**High-yield transformed-root table:**

| New roots | Sum | Product | Condition |
|---|---|---|---|
| $\alpha^2,\ \beta^2$ | $S^2-2P$ | $P^2$ | any |
| $\alpha+k,\ \beta+k$ | $S+2k$ | $P+kS+k^2$ | any |
| $k\alpha,\ k\beta$ | $kS$ | $k^2P$ | any |
| $1/\alpha,\ 1/\beta$ | $S/P$ | $1/P$ | **$P\ne0$** |
| $\alpha+1/\beta,\ \beta+1/\alpha$ | $S(P+1)/P$ | $(P+1)^2/P$ | **$P\ne0$** |

**Teacher Q9(e) specialized:**

```math
\boxed{P t^2-S(P+1)t+(P+1)^2=0}\quad(P\ne0).
```

For $x^2-6x+3=0$, $S=6,P=3$, so new roots $\alpha+1/\beta,\ \beta+1/\alpha$ satisfy $3t^2-24t+16=0$.

**Other useful Vieta identities:**

```math
\alpha^2+\beta^2=S^2-2P
```

```math
(\alpha-\beta)^2=S^2-4P=\frac{\Delta}{a^2}
```

```math
|\alpha-\beta|=\sqrt{S^2-4P}\quad\text{for real roots}
```

```math
\alpha^3+\beta^3=S^3-3PS
```

```math
\frac1\alpha+\frac1\beta=\frac S P\quad(P\ne0).
```

**Teacher parameter example:** $f(x)=3px^2+(3p-4)x+(p-2)$ has
$\Delta=16-3p^2$. Two distinct real roots require $\Delta>0$ AND $p\ne0$; source additionally restricts $p\in\mathbb Q$. Hence

```math
p\in\mathbb Q,\quad -\frac4{\sqrt3}<p<\frac4{\sqrt3},\quad p\ne0.
```

---

## 7 — Graphs, intercepts, transformations and geometry

**Graph language:**
- Domain = allowable input $x$ values.
- Range = attainable output $y$ values (verify open/closed boundaries).
- $x$-intercept: set $y=0$.
- $y$-intercept: set $x=0$, **if $x=0$ is in the domain**.
- Horizontal asymptote: $y=k$ approached as $x\to\pm\infty$.
- Vertical asymptote: $x=h$ approached as x approaches the restricted boundary.
- A quadratic's vertex **belongs to graph**, but a nonzero shifted exponential **never meets its horizontal asymptote**.

**Transformation dictionary, $f$ any function:**

```math
\begin{aligned}
f(x)+k &: \text{up }k\\
f(x-h)&: \text{right }h\\
f(x+h)&: \text{left }h\\
-f(x)&: \text{reflect across x-axis}\\
f(-x)&: \text{reflect across y-axis}\\
A f(x)&: \text{vertical scale by }|A|,\ \text{reflect in x-axis if }A<0\\
f(Bx)&: \text{horizontal scale }1/|B|,\ \text{reflect in y-axis if }B<0.
\end{aligned}
```

For combined transformations, pay attention to operation **order**. For translation by vector $(p,q)$:

```math
\boxed{g(x)=f(x-p)+q}.
```

A point $(x_0,y_0)$ maps to $(x_0+p,y_0+q)$. E.g. $(-1,3)$ means $g(x)=f(x+1)+3$.

**Straight-line formulas (SPtLDV worksheet):**

```math
\boxed{m=\frac{y_2-y_1}{x_2-x_1}}\quad(x_1\ne x_2),
```

```math
\boxed{y-y_1=m(x-x_1)},\qquad \boxed{y=mx+c}.
```

Vertical line $x=k$ has **undefined slope**.
If intercepts are $(p,0)$ and $(0,q)$ with $p,q\ne0$:

```math
\boxed{\frac xp+\frac yq=1}\quad\Longleftrightarrow\quad qx+py=pq.
```

Parallel non-vertical lines have equal slopes; perpendicular non-vertical lines satisfy $m_1m_2=-1$. Handle vertical/horizontal special cases.

---

## 8 — SPtLDV inequalities and linear programming (IN SCOPE)

**Standard model** (two variables, not SPLTV):

```math
\boxed{\text{Objective }Z=px+qy}
```

subject to constraints such as

```math
ax+by\le c,\qquad dx+ey\ge f,\qquad x,y\ge0.
```

**Workflow (memorise):**
1. Define decision variables $x,y$ and units.
2. Translate every resource/requirement into an inequality; do not reverse **at most** and **at least**.
3. Replace each inequality by an equality to draw its boundary line. Plot intercepts, or pick two points.
4. For $\le,\ge$: solid boundary; for $<,>$: dashed boundary.
5. Test a point not on the line (usually $(0,0)$) and shade the correct side.
6. Intersect ALL shaded half-planes: the **feasible region**.
7. Find **all feasible corner points**, including line intersections and axis intersections.
8. Evaluate $Z=px+qy$ at each corner; select max/min as required and interpret units.
9. Check feasibility and whether optimum is genuinely attained; unbounded/integer/strict cases need extra care.

**Sourced SPtLDV example:** $2x+y\le10$, $x+2y\le8$, $x,y\ge0$ has corner points

```math
(0,0),\ (5,0),\ (4,2),\ (0,4).
```

If $Z=3x+2y$, the respective values are $0,15,16,8$, so the max is $\boxed{16\text{ at }(4,2)}$.

**Useful translation words:**
- at most / maximum permitted / no more than $\to\le$.
- at least / minimum required / no less than $\to\ge$.
- nonnegative quantity $\to x\ge0$.
- limited supply $\to$ resource usage $\le$ supply.
- required nutrients/demand $\to$ total contribution $\ge$ requirement.

**Corner theorem caveat:** For a bounded feasible polygon with inclusive inequalities, linear objective extrema occur at vertices (possibly shared by an entire edge). For an unbounded feasible region, a finite minimum may exist but a maximum may not; check direction and feasibility. Strict constraints can make a supremum unattained.

---

## 9 — Real-world quadratic models (teacher paper)

**Lifeguard three-side rope/fence length $L$:**
Two perpendicular sides $x$, remaining side $L-2x$:

```math
\boxed{A=x(L-2x)= -2x^2+Lx}.
```

Physical domain $0<x<L/2$. Completing square:

```math
\boxed{A=-2\left(x-\frac L4\right)^2+\frac{L^2}{8}}
```

so maximizing rectangle uses $x=L/4$, third side $L/2$, max area $L^2/8$. For $L=80$: $x=20$, other side $40$, max area $800\text{ m}^2$.

**Projectile example from teacher paper:** $h(t)=-5t^2+30t+35=-5(t-3)^2+80$, $t\ge0$.
- Initial height $h(0)=35$ metres.
- Max height $80$ metres at $t=3$s.
- Sea-level hit: solve $h(t)=0$, discard negative-time root.
- Above threshold $H$: solve $h(t)>H$ and express an interval/duration.

**Recognition map:**

| Question language | Start with |
|---|---|
| Simplify exact powers/surds | Index laws, factor perfect squares, conjugates |
| Solve equal exponentials | Same base, or logarithm |
| $a^{2x}$ and $a^x$ together | $u=a^x>0$ substitution |
| Product/quotient of logarithms | Log laws; check domain |
| Long log chain | Change of base and telescope |
| Quadratic roots | Factor / slide-divide / quadratic formula |
| New quadratic with changed roots | Vieta sum+product |
| Two distinct / equal / no real roots | Discriminant $>,=,<$ zero |
| Tangent line to parabola | Set line=curve; discriminant zero |
| Maximum/minimum | Vertex/completing square / $-b/(2a)$ |
| At least / at most a quadratic value | Solve quadratic inequality and sign chart |
| Shift/reflection of graph | $g(x)=Af(B(x-h))+k$ and special rules |
| Many linear constraints | Feasible region and corner-point optimization |
| "Hence" | Use previous part as a tool |
| "Show that" | Derive the GIVEN result, don't just quote it |
| "Explain / justify" | Show WHY; include domain, signs, graph logic and units |

---

## 10 — Last-minute memory priorities and full-credit checklist

**Tier 1 — must recall without notes:**
- Index laws incl. negatives and fractions; exact surds/conjugates.
- Log inverse definition, 3 laws, change-of-base, positivity restriction.
- Quadratic formula, discriminant, completing square and vertex formula.
- Three quadratic forms; Vieta sum/product; roots-to-new-equation; $S^2-2P$.
- Slide-and-divide AC factorisation correctly restoring original $a$.
- Domain/range/asymptotes for exponential/log/quadratic.
- $y-y_1=m(x-x_1)$; feasible region and corner optimization.

**Tier 2 — teacher IB Prep multi-part / higher reasoning:**
- $S^2-4P$, $\alpha^3+\beta^3$, transformed reciprocal and squared roots.
- Telescoping log products.
- Exponential substitutions and variable-base inequalities.
- Parameter restrictions $a\ne0$ and $p\in\mathbb Q$ when stated.
- Tangency, root geometry and model/context restrictions.
- Graph translations by a vector, inequalities and temporal durations.

**IB-style final check:** write variables, exact restrictions and units $\to$ select a method and show meaningful steps $\to$ use preceding results for “hence” $\to$ avoid early rounding $\to$ discard invalid candidates $\to$ state final value, interval, range or point in correct format. A correct result with no working may lose method/reasoning marks.

### Source links
- [School/teacher/regular/IB Mathematics full source map](MATHEMATICS_SOURCE_MAP.md)
- [Authentic IB Mathematics AA alignment](IB_MATHEMATICS_ALIGNMENT.md)
- [Teacher practice/regular crosswalk](MATH_05_PAPER_CROSSWALK.md)
- [Original exponents and surds lesson](MATH_01_EXPONENTS_SURDS.md)
- [Original logarithms lesson](MATH_02_LOGARITHMS.md)
- [Original quadratics and Vieta lesson](MATH_03_QUADRATICS.md)
- [Original linear inequalities and LP lesson](MATH_04_LINEAR_PROGRAMMING.md)

**No mini-quiz here.** The learner requested teach-all first and testing only on explicit opt-in.
