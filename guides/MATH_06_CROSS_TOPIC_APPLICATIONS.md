# Pre-IB SAS Mathematics — cross-topic connections and IB-style solution methods

**Grade X-6, teach-first study notes, 22 November 2026.** Keep for independent revision. Do not cold-test the learner; the user explicitly wants to hear the entire syllabus first and only practise when they opt in.

## Exponential modelling: proportional changes
Repeated percentage growth is multiplication, not repeated addition. For an initial population 800 growing 25% per **two-year** interval, $P(t)=800(1.25)^{t/2}$. The exponent counts time **intervals**. To calculate time for a target population $T$, solve $T/800=1.25^{t/2}$, so $t=2\ln(T/800)/\ln(1.25)$. Interpret the domain $t\ge0$ where appropriate.

## Teacher multi-part quadratic: discriminant with a parameter
For $f(x)=3px^2+(3p-4)x+p-2$, the discriminant is
$$\Delta=(3p-4)^2-4(3p)(p-2)=16-3p^2.$$
Two distinct real roots require $\Delta>0$, hence $-4/\sqrt3<p<4/\sqrt3$. Additionally, **$p\ne0$** to remain a genuine quadratic; if the question states $p\in\mathbb Q$ (as the teacher's paper does), intersect this range with $\mathbb Q$.

## Teacher graph transformation: a geometrical explanation
Given $f(x)=2(x-3)^2-2$, translation by vector $(-1,3)$ moves left 1 and up 3:
$$g(x)=f(x+1)+3=2(x-2)^2+1=2x^2-8x+9.$$
The vertex is $(2,1)$ and $g(x)\ge1$, so $g(x)=0$ has **no real roots**. This conclusion comes from graph geometry and a square's nonnegativity, not a guess.

## Applied quadratic: a thrown stone (teacher paper)
$h(t)=-5t^2+30t+35=-5(t-3)^2+80$, $t\ge0$. Maximum height is **80 m at $t=3$s**. For sea level, $h(t)=0\Rightarrow(t-7)(t+1)=0$, so $t=7$s (discard $-1$s on contextual grounds). For heights greater than 60m, $-5(t-1)(t-5)>0\Rightarrow1<t<5$, lasting **4 seconds**.

## Precision: interpreting IB-style command terms
- **State / write down:** short correct answer; minimal or no working if explicitly permitted.
- **Find / calculate / determine / solve:** use a sound method and show relevant steps.
- **Show that:** the result is already supplied; establish it from given facts, never simply copy it. This is often marked **AG** (answer given) when quoting the target result.
- **Hence:** use the previous result; explain the link to receive reasoning credit.
- **Explain / justify:** articulate WHY a method or conclusion is valid, including restrictions, units and graph properties.
- **Sketch:** labelled shape, roots, vertex or asymptote as appropriate; a sketch is not an arbitrary squiggle.
- **Verify:** substitute into original conditions and confirm.

Oxford *IB Prepared Mathematics AA* 2021 introduction pp. iv–vii and exam section p. 197 discuss M method, A achievement/accuracy and R reasoning; teacher's uploaded formative and 92-mark key also support multi-part method-based marking. These do not certify an official SAS grading scheme. Calculator restrictions on the user-supplied teacher practice paper apply to its listed questions only; school SAS calculator policy needs school confirmation if necessary.

## A compact decision tree for identifying the right method
| What you see | First thing to think |
| --- | --- |
| Same base, powers multiplied | Add exponents |
| Same base both sides of an exponential equation | Equate the exponent expressions |
| Repeated $a^x$ and $a^{2x}$ | Substitute $u=a^x>0$ |
| Unknown exponent with incompatible bases | Take logs/change base |
| Logarithm equation | **Argument > 0** first; combine/convert; check candidates |
| Quadratic in standard form | Need root, vertex, intercept, inequality or number of roots? Choose best form |
| Asked for a new quadratic from old roots | Vieta sum/product, transform sums/products |
| Line tangent to parabola | Equate and require $\Delta=0$ |
| 3 linear equations | Eliminate a variable from two distinct pairs, back-substitute |
| Several linear inequalities | Graph common feasible region, identify feasible corners |
| Linear objective to maximise | Evaluate objective at feasible corners and justify existence |

## Source boundaries
School Pre-IB Mathematics SAS scope: exponents, log, quadratics, SPLTV and linear programming; teacher IB Prep 20 questions/160 marks, teacher quadratic 15 questions/92-mark scheme; full source map in MATHEMATICS_SOURCE_MAP.md. These notes are newly written and do not reproduce copyrighted textbook pages or full uploaded papers.

**No practice/quiz is part of this chapter**. Student may request explanations freely and opt into testing only after feeling ready.
