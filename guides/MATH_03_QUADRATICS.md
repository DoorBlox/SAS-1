# Mathematics Study Guide 03 — Quadratics, Vieta, Graphs and Tangency

**Original self-contained Pre-IB revision.** Referenced to user's school SAS, 15-question/92-mark teacher formative and markscheme, teacher IB-prep practice Q9–15/Q19–20; official IB AA **SL2.6/2.7 and AHL2.12**; actual Oxford IB Prepared **§2.3 p.49+** and **§2.4 p.60+**; Pearson AA HL **Ch.2 Functions** (chapter mapped, complete text not verified).


> **Standing learner preference (22 Nov 2026): TEACH ALL RELEVANT MATERIAL FIRST, THEN TEST ONLY WITH EXPLICIT OPT-IN.** Work through every major syllabus chapter and original notes in a cohesive teaching phase, from zero to Pre-IB depth. The learner may interrupt with questions at any point. Do not insert mini-quizzes, diagnostics, transfer problems or questions for the student to answer while the teaching phase is ongoing. Worked examples are permitted; label exercises in archived guides as *for later*. After all chapters have been explained, ask whether they want clarification or to switch to practice, but do not auto-start assessment.

## 1. Why does a quadratic curve appear?
If a square has side length $x$, its area is $x^2$. Changing $x$ doesn't change the area at a constant rate: raising 2 to 3 changes area from 4 to 9, while raising 3 to 4 changes from 9 to 16. This *changing rate of change* creates the curved shape of $y=x^2$, a **parabola**.

A **quadratic function** has the form $f(x)=ax^2+bx+c$, where $a\ne0$. For $a>0$ the graph is a U and has a **minimum**; for $a<0$ it is an upside-down U and has a **maximum**. The line dividing the parabola into mirror halves is its **axis of symmetry**.

## 2. Three forms = three ways to see the SAME function
**Standard form:** $f(x)=ax^2+bx+c$. It immediately gives the y-intercept $(0,c)$.
**Factored form:** $f(x)=a(x-r_1)(x-r_2)$. If real roots exist, the x-intercepts are $(r_1,0)$, $(r_2,0)$.
**Vertex form:** $f(x)=a(x-h)^2+k$. The vertex is $(h,k)$, and the axis is $x=h$. For $a>0$, range is $[k,\infty)$; for $a<0$, it is $(-\infty,k]$. Unlike exponentials, a parabola actually REACHES its vertex, so the endpoint is INCLUDED.

Learn to move between forms, because the IB guide explicitly assesses the equivalence of representations.

## 3. Derive vertex form (completing the square) — do not memorise blindly
Start with $f(x)=ax^2+bx+c$ and $a\ne0$:
$$
f(x)=a\left[x^2+\frac ba x\right]+c
=a\left[\left(x+\frac b{2a}\right)^2-\left(\frac b{2a}\right)^2\right]+c.
$$
Thus
$$
\boxed{f(x)=a\left(x+\frac b{2a}\right)^2+\left(c-\frac{b^2}{4a}\right)}.
$$
Therefore the vertex x-coordinate is $\boxed{-b/(2a)}$, and the vertex height is $c-b^2/(4a)$. You have proved where the vertex formula comes from.

**Demonstration:** $f(x)=3x^2+12x+5=3(x^2+4x)+5=3[(x+2)^2-4]+5=3(x+2)^2-7$.
The minimum is $-7$ at $x=-2$; axis $x=-2$ and range $[-7,\infty)$.

## 4. Roots: the discriminant counts real intersections
Set $ax^2+bx+c=0$. Completing the square leads to the quadratic formula:
$$\boxed{x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}}\qquad (a\ne0).
$$
Let $\Delta=b^2-4ac$:
- $\Delta>0$: TWO distinct real x-intercepts.
- $\Delta=0$: ONE repeated real root; the parabola *touches* the x-axis.
- $\Delta<0$: NO real roots; the graph does not cross the x-axis.

**Parameters:** if $a$ depends on a parameter, separately check $a\ne0$. Otherwise the function is NOT quadratic. This is commonly missed.

### Crucial teacher-formative flaw: Q1
The supplied formative asks for ordered real roots of $x^2-2x+5=0$.
$$\Delta=(-2)^2-4(1)(5)=4-20=-16.$$
It has **no real roots**, so $x_1\le x_2$ in the real numbers has no meaning. Its complex solutions would be $x=1\pm2i$, but complex numbers have no standard order by $\le$. The accompanying teacher markscheme flags this problem: you should explain it rather than fabricate a real pair.

## 5. Why Vieta's formulas work — roots without calculating roots
Suppose a quadratic's roots are $\alpha,\beta$. Then
$$a(x-\alpha)(x-\beta)=a[x^2-(\alpha+\beta)x+\alpha\beta].$$
Compare coefficients with $ax^2+bx+c$:
$$\boxed{\alpha+\beta=-\frac ba},\qquad \boxed{\alpha\beta=\frac ca}.$$
This is **Vieta**. It is useful when questions ask for relationships, new equations or expressions in roots instead of roots individually.

Derived identities to remember *by expanding*:
$$\alpha^2+\beta^2=(\alpha+\beta)^2-2\alpha\beta,$$
$$(\alpha-\beta)^2=(\alpha+\beta)^2-4\alpha\beta,$$
$$\frac1\alpha+\frac1\beta=\frac{\alpha+\beta}{\alpha\beta}\quad(\alpha\beta\ne0).$$
For a NEW equation with roots $u,v$: $x^2-(u+v)x+uv=0$, or any nonzero multiple of it.

### Teacher-style multi-part worked example: Pre-IB Q9
Original quadratic: $x^2-6x+3=0$, roots $\alpha,\beta$. **No need to compute them.**
- Sum $\alpha+\beta=6$ and product $\alpha\beta=3$ [A marks].
- $\alpha^2+\beta^2=6^2-2(3)=30$ [M for using identity, A for answer].
- Squared roots $u=\alpha^2,v=\beta^2$ have sum $30$ and product $(\alpha\beta)^2=9$, so the new quadratic is $\boxed{x^2-30x+9=0}$ [M/A].
- $|\alpha-\beta|=\sqrt{(\alpha+\beta)^2-4\alpha\beta}=\sqrt{36-12}=2\sqrt6$.
These method and accuracy tags are illustrative of IB marking structure, not a claim of exact teacher Q9 allocation.

## 6. Tangency = exactly one real meeting point
When a line meets a parabola at just one point, their equation of intersection has a **repeated** solution, so $\Delta=0$.

Example: line $y=2x+1$ tangent to parabola $y=mx^2+(m-5)x+10$.
Equate: $mx^2+(m-7)x+9=0$. For tangency AND a true parabola, $m\ne0$ and
$$\Delta=(m-7)^2-36m=m^2-50m+49=(m-1)(m-49)=0.$$
Thus $\boxed{m=1\text{ or }49}$, and the line really meets the graph at one point for both values. **Never skip the preliminary coefficient check** when varying parameters.

## 7. Modelling and graph transformations: link algebra to interpretation
A physical object thrown upwards might follow $h(t)=-5t^2+30t+35$, $t\ge0$.
Complete the square: $h(t)=-5(t-3)^2+80$.
Thus the **maximum height is 80 metres at 3 seconds**. The quantity 3 is time, not height. At the sea, $h=0$, so $-5t^2+30t+35=0$ or $(t-7)(t+1)=0$, and only $t=7$ is physically valid. This is the central IB habit: contextual domain and units matter.

A graph with vertex $(3,-2)$ and point $(1,6)$ has $f(x)=a(x-3)^2-2$.
Substitute $(1,6)$: $6=4a-2$, hence $a=2$ and $f(x)=2(x-3)^2-2=2(x-2)(x-4)$.
Translate by vector $\binom{-1}{3}$: **left 1, up 3**,
$$g(x)=f(x+1)+3=2(x-2)^2+1=2x^2-8x+9.$$
As $2(x-2)^2+1\ge1>0$, $g(x)=0$ has no real roots. This style mirrors the teacher's multipart Q20.

### Teacher-formative flaws worth remembering
- Q7: if two *real* numbers differ by 10, write $u=v+10$, then product $uv=v^2+10v=(v+5)^2-25$. The product has **minimum $-25$**, **no maximum** as $|v|\to\infty$. The source asks for a maximum, but its own markscheme says it intended a minimum. Don't pretend it has a largest value.
- Q9: the diagram's coordinate axes are swapped/mislabeled; interpret its curve using actual horizontal and vertical directions.

## Memory anchors — high-yield exam revision
Say: **STANDARD -> y-intercept; FACTORED -> roots; VERTEX -> maximum/minimum.**
**Discriminant:** "positive two, zero touches, negative none" (real roots).
**Vieta:** "sum is minus middle over first; product is last over first."
**Full-mark habit:** graph shape -> axis/vertex -> root signs/restrictions -> units -> check.
On a blank page, reconstruct three forms, derive the axis by completing square, and build a new quadratic using only new roots' sum and product. Practise one explanation aloud.

## One optional original transfer problem — ONLY after studying the chapter
A quadratic $f(x)=x^2-4x+c$ has a minimum value of $-3$. Find $c$, vertex, and both roots, justifying every step and the range. The final question is not the first thing a tutor should give you; learn the above first.

**Next:** [SPLTV and linear programming](MATH_04_LINEAR_PROGRAMMING.md).


## Slide-and-divide / AC factorisation — a preferred learner technique

**The student recalled this method and explicitly preferred it over treating division by the leading coefficient as awkward.** It is a systematic way to factor non-monic quadratics using integer factor pairs.

For $ax^2+bx+c$ with $a\ne0$, temporarily factor the *monic auxiliary expression*
$$x^2+bx+ac=(x+m)(x+n),\quad m+n=b,\quad mn=ac.$$
**This auxiliary expression is NOT generally equal to the original polynomial.** Correctly restore $a$ by dividing the constants in the two factors by $a$ and multiplying the resulting factors by $a$:
$$\boxed{ax^2+bx+c=a\left(x+\frac ma\right)\left(x+\frac na\right).}$$
Simplify to obtain integer-coefficient factors if possible.

**Full worked example:** $6x^2+11x+3$ has $ac=18$, so use $x^2+11x+18=(x+9)(x+2)$. Restore correctly:
$$6(x+9/6)(x+2/6)=6(x+3/2)(x+1/3)=(2x+3)(3x+1).$$

**Alternative equivalent slide-and-divide presentation:**
$$ax^2+bx+c=\frac{(ax+m)(ax+n)}{a}.$$
The right side expands to $ax^2+(m+n)x+mn/a=ax^2+bx+c$. For the same example,
$$(6x+9)(6x+2)/6=(2x+3)(3x+1).$$

**Crucial caveat:** never simply drop $a$ and claim $ax^2+bx+c=(x+m)(x+n)$; the intermediate quadratic $x^2+bx+ac$ is only a factor-pair tool. If solving $ax^2+bx+c=0$, dividing the entire original equation by any nonzero constant preserves its roots, but if giving the original polynomial's factorisation, retain the correct overall coefficient.

**Method recognition:** For a quadratic with integer coefficients and a non-unit $a$, try the AC/slide-and-divide trick when $ac$ has a convenient factor pair; if not, completing the square or the quadratic formula still works. No questions to the student until they opt into practice.
