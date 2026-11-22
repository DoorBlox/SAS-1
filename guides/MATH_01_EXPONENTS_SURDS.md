# Mathematics Study Guide 01 | Exponents, Surds, and Exponential Thinking

**From zero to Pre-IB multi-part work.** Original explanatory notes tied to the school SAS scope, teacher practice Q1–6, Q16, Q18(a), and CCC regular practice Q1–18. Read once for understanding, revisit the memory summary before the exam.


> **Standing learner preference (22 Nov 2026): TEACH ALL RELEVANT MATERIAL FIRST, THEN TEST ONLY WITH EXPLICIT OPT-IN.** Work through every major syllabus chapter and original notes in a cohesive teaching phase, from zero to Pre-IB depth. The learner may interrupt with questions at any point. Do not insert mini-quizzes, diagnostics, transfer problems or questions for the student to answer while the teaching phase is ongoing. Worked examples are permitted; label exercises in archived guides as *for later*. After all chapters have been explained, ask whether they want clarification or to switch to practice, but do not auto-start assessment.

## 1. The idea: a power records repeated multiplication
$2^3=2\times2\times2=8$. Here **2** is the base and **3** tells how many copies of 2 are multiplied. Every increase in the exponent by one multiplies the result by another 2:

| Exponent | $2^0$ | $2^1$ | $2^2$ | $2^3$ | $2^4$ |
|---|---:|---:|---:|---:|---:|
| Value | 1 | 2 | 4 | 8 | 16 |

Keep in mind that a *power* is an operation, not a number with a decorative superscript.

### Why the laws are inevitable
$2^3\cdot2^2=(2\cdot2\cdot2)(2\cdot2)=2^5$. We counted factors: the exponents **add** because the same base is multiplied.

$\dfrac{2^5}{2^3}=\dfrac{2\cdot2\cdot2\cdot2\cdot2}{2\cdot2\cdot2}=2^2$. Cancelling factors means the exponents **subtract**.

$(2^3)^2=2^3\cdot2^3=2^6$. Two complete groups of three factors give **multiplication** of exponents.

For appropriate real values (in particular a positive base for arbitrary real exponents):

- Product with same base: $a^m a^n=a^{m+n}$.
- Quotient with same nonzero base: $a^m/a^n=a^{m-n}$.
- Power of a power: $(a^m)^n=a^{mn}$.
- Power of a product: $(ab)^n=a^n b^n$ when both sides are defined.
- Power of a quotient: $(a/b)^n=a^n/b^n$ when defined and $b\ne0$.

**Important contrast:** $a^m+a^n$ cannot generally be combined into one power. Also $(a+b)^2=a^2+2ab+b^2$, **not** $a^2+b^2$.

## 2. Zero, negative and fractional exponents: learn WHY

### Zero
Divide by the base each time the exponent drops one: $2^3=8$, $2^2=4$, $2^1=2$, $2^0=1$. Hence $a^0=1$ for $a\ne0$.

### Negative
Keep dividing: $2^{-1}=1/2$, $2^{-2}=1/4$. Therefore $a^{-n}=1/a^n$ (nonzero base). **Negative exponent = reciprocal, not negative result.**

### Fractional
The number $a^{1/2}$ should square to $a$: $(a^{1/2})^2=a$. Thus $a^{1/2}=\sqrt a$ for $a\ge0$. More generally, for $a>0$,
$$a^{m/n}=(\sqrt[n]{a})^m=\sqrt[n]{a^m}.$$
For real square roots the radicand must be nonnegative; if a denominator appears it must be nonzero. Even roots and arbitrary negative bases require special care.

**Worked A (like teacher Q1a):**
$$125^{2/3}=(5^3)^{2/3}=5^{2}=25.$$

**Worked B (like teacher Q1b):**
$$\left(\frac{27}{8}\right)^{-2/3}
=\left[\left(\frac32\right)^3\right]^{-2/3}
=\left(\frac32\right)^{-2}
=\left(\frac23\right)^2=\frac49.$$

**Memory sentence:** *Multiply same bases = add; divide = subtract; raise a power = multiply; negative = flip; fraction = root.*

## 3. Surds (radicals): exact numbers, not a scary new operation

A **surd** is an exact irrational root written in radical form. $\sqrt{2}$ is exact; 1.414... is an approximation.

Factor out the largest perfect square:
$$\sqrt{72}=\sqrt{36\cdot2}=6\sqrt2,\quad
\sqrt{75}=5\sqrt3,\quad
\sqrt{48}=4\sqrt3.$$

Only like radical terms can combine:
$$\sqrt{75}+\sqrt{48}-\sqrt{27}
=5\sqrt3+4\sqrt3-3\sqrt3=6\sqrt3.$$

Rationalise a denominator with its **conjugate**. Since $(a+b)(a-b)=a^2-b^2$:
$$\frac{4}{2+\sqrt3}
=\frac{4(2-\sqrt3)}{(2+\sqrt3)(2-\sqrt3)}
=4(2-\sqrt3)=8-4\sqrt3.$$

**Teacher Q16a worked:** 
$$\frac{12}{3-\sqrt5}
=\frac{12(3+\sqrt5)}{9-5}
=9+3\sqrt5.$$

For teacher Q3, $\ell=4+\sqrt3$ and $w=4-\sqrt3$ demonstrate:
- area: $(4+\sqrt3)(4-\sqrt3)=16-3=13$ square centimetres;
- perimeter: $2(\ell+w)=16$ centimetres;
- diagonal: $d=\sqrt{\ell^2+w^2}=\sqrt{38}$ centimetres, because $\ell^2+w^2=2(16+3)=38$.
Write exact roots unless told to round.

## 4. Exponential equations: rewrite to ONE BASE

If $a>0$ and $a\ne1$, then $a^u=a^v$ implies $u=v$ because $a^x$ is one-to-one.

**Teacher Q2b style:**
$$9^{x+4}=27^{2x-1}.$$
Replace $9=3^2$ and $27=3^3$:
$$(3^2)^{x+4}=(3^3)^{2x-1}$$
$$3^{2x+8}=3^{6x-3}.$$
Thus $2x+8=6x-3$, so $11=4x$ and
$$\boxed{x=\frac{11}{4}}.$$

**When this works:** both sides can be written using the same base.
**When it doesn't:** introduce logarithms later; don't pretend unlike bases have equal exponents.

### Hidden quadratics: substitute the repeating power
$$4^x-5(2^x)+4=0.$$
Since $4^x=(2^x)^2$, set $u=2^x$ (**$u>0$**):
$$u^2-5u+4=(u-1)(u-4)=0.$$
Therefore $u=1$ or $4$. Returning to $2^x=u$ yields $x=0$ or $x=2$. Both check in the original. **These are the learner's successfully demonstrated steps in Diagnostic 1**; the domain and explicit checking must be remembered.

For a different model, teacher Q18a has $2^{2x}-6(2^x)+8=0$. Same substitution $u=2^x$ gives $(u-2)(u-4)=0$, so $x=1,2$.

## 5. The exponential graph: multiplication creates curves

For $f(x)=a^x$ with $a>0$, $a\ne1$:
- **Domain:** all real numbers, because any real exponent is allowed.
- **Range:** $(0,\infty)$, because a positive base to a real power is always positive.
- **Intercept:** $(0,1)$ because $a^0=1$.
- **Horizontal asymptote:** $y=0$. The curve approaches it without reaching it.
- $a>1$ gives **growth**; $0<a<1$ gives **decay**.

For $f(x)=a^{x-h}+k$ the graph moves **right by $h$** and **up by $k$** (negative $h,k$ reverse directions). The horizontal asymptote is $y=k$. With positive coefficient multiplying the exponential, the range is $(k,\infty)$.

Example: $f(x)=3^{x-2}-4$ shifts right 2, down 4. Asymptote $y=-4$, domain $\mathbb{R}$ and range $(-4,\infty)$. **The boundary is excluded** because $3^{x-2}>0$ even when extremely small. The learner previously gave $y=-5$ and included $-5$; this was diagnosed, not yet independently retested.

**Deeper Pre-IB nuance:** $g(x)=16-(1/2)^{x-3}$ has coefficient $-1$ on a positive exponential. Its graph stays **below** $16$, so its range is $(-\infty,16)$, not $(16,\infty)$. It increases as $x$ increases because $(1/2)^{x-3}$ decreases and is then subtracted.

For the generalized $A a^{x-h}+k$, $A>0$ means range $(k,\infty)$, $A<0$ means $(-\infty,k)$, provided $A\ne0$.

## 6. Exponential inequalities: why the base matters
For $a>1$, $a^x$ increases: $a^u>a^v$ iff $u>v$.
For $0<a<1$, $a^x$ decreases: $a^u>a^v$ iff $u<v$.

Example: $(1/2)^{x-1}> (1/2)^3$ implies $x-1<3$, hence $x<4$. The sign **reverses** because the base is between 0 and 1, not as a memorised arbitrary exception.

## 7. Growth and decay in real life
A common model is $P(t)=P_0(1+r)^{t/T}$: $P_0$ initial amount, $r$ fractional change every interval $T$.

CCC's regular practice uses population and depreciation problems. Interpret $P_0$ by putting $t=0$; for a 50% increase per four units, the multiplier is $1.5$ at each four-unit interval. A factor of $0.8$ is a 20% decline every specified interval, **not a drop of 0.8 units**. A positive exponentially decaying model approaches zero but never equals zero at finite time.

This pattern transfers to finance, biology, half-life and population.

## 8. How to memorise the chapter without cramming
1. **Retrieval, not rereading:** close this file and explain why exponents add when multiplying powers.
2. Say: “negative -> reciprocal; fraction -> root; same base -> compare exponents; addition of two unlike powers -> look for substitution.”
3. **Five-minute blank-page routine:** write the 5 main laws from memory, solve one exact-value radical, sketch one exponential with an asymptote.
4. **Error triggers:** before concluding an answer, ask (i) is my base allowed? (ii) did I confuse plus with multiplication? (iii) does the result respect range/domain? (iv) is the endpoint included?

## 9. Model answer format: get marks for your reasoning
For a typical teacher-style multi-part question:
- Identify an algebraic structure or a common base.
- Show each law substitution explicitly, especially exponent multiplication and negative signs.
- For graphs, state domain/range/asymptote and explain why the bound is excluded.
- Prefer exact fractions and surds rather than rounding.
- Check your final answer when possible.

## 10. Your own practice — only AFTER learning the lesson
These are original problems, NOT copied from your teacher or CCC.

**Foundation:** Evaluate $81^{3/4}$ exactly and explain the fourth root before cubing.

**Application:** Solve $16^{x-1}=8^{2x+1}$, showing the common base and both exponent expressions.

**Transfer:** $h(x)=9-2(1/3)^{x+2}$. Explain its horizontal shift, vertical shift, asymptote, domain, **range**, and whether it increases or decreases. Explain why $y=9$ is not attained.

Answer ONE at a time in the chat. A tutor must teach the underlying material first and only then ask for learner work.

### Next
[Logarithms: the inverse of exponentiation](MATH_02_LOGARITHMS.md). Do not confuse the symbol $\log$ with multiplication. Learn it from the inverse relationship.
