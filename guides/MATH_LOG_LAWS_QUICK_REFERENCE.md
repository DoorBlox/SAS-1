# SAS Pre-IB Mathematics — LOGARITHMS FIRST: Complete Laws & Worked Examples

**23 Nov 2026 · X-6 · Teacher-calibrated · Original notes · No testing unless learner opts in**

This reference complements [the complete logarithms lesson](MATH_02_LOGARITHMS.md) and [the master mathematics cheat sheet](MATH_SAS_MASTER_CHEATSHEET_2026.md). **Why priority?** The actual teacher **IB Prep Q6–8, Q17, Q18(b)** demand exponent/log equation solving, telescoping logs, symbolic representations, and strict domains. Regular CCC SAS logs Q19–26 and the teacher's formative contain more mixed-base and argument-domain examples. **No SPLTV on the actual Math SAS.**

## 1. Absolute foundation

\`\`\`math
\boxed{\log_a b=c\iff a^c=b}
\`\`\`

Valid real logarithm: **base $a>0$, $a\ne1$; argument $b>0$**. The *result* $c$ may be negative, zero, or fractional:
- $\log_2 8=3$; $\log_3(1/9)=-2$; $\log_9 3=1/2$.
- $\log_a 1=0$; $\log_a a=1$.

## 2. All high-priority laws

Unless otherwise stated, **$a>0$, $a\ne1$, $M,N>0$**, and any **other** base such as $b$ must be $>0,\ne1$.

| Law | Equation | Think |
|---|---|---|
| PRODUCT | $\log_a(MN)=\log_aM+\log_aN$ | multiply inside = add outside |
| QUOTIENT | $\log_a(M/N)=\log_aM-\log_aN$ | divide inside = subtract outside |
| POWER | $\log_a(M^r)=r\log_aM$ | bring exponent to front |
| LOG OF ONE | $\log_a1=0$ | $a^0=1$ |
| LOG OF BASE | $\log_a a=1$ | $a^1=a$ |
| CANCEL INVERSES | $\log_a(a^x)=x$ | log undoes exponential |
| CANCEL INVERSES | $a^{\log_aM}=M$ | exponential undoes log |
| CHANGE BASE | $\log_aM=\frac{\log_b M}{\log_b a}=\frac{\ln M}{\ln a}$ | move to common base |
| RECIPROCAL | $\log_a b=\frac1{\log_b a}$ | swap base and argument |
| CHAIN | $\log_a b\log_b c=\log_a c$ | middle bases cancel |
| RECIPROCAL ARGUMENT | $\log_a(1/M)=-\log_a M$ | reciprocal is power $-1$ |
| POWERED BASE | $\log_{a^k}(M^n)=\frac nk\log_aM$ | exponent of base goes to denominator; $k\ne0$ |
| SQUARE WITH SIGN | $\log_a(M^2)=2\log_a\lvert M\rvert$ | when $M\ne0$; use absolute value |

For chain law, **$a,b,c>0$ and $a,b\ne1$**. For the powered-base law, $n$ is real, $k\ne0$, and $M>0$.

### Why the three essential laws work
If $M=a^p$ and $N=a^q$, then $MN=a^{p+q}$, $M/N=a^{p-q}$ and $M^r=a^{pr}$. Taking $\log_a$ yields respectively the **sum, difference and scalar multiple**. Logarithm laws aren't separate arbitrary rules; they *are exponent laws written backwards*.

### Invalid manipulations
**NEVER** assume $\log_a(M+N)=\log_aM+\log_aN$ or $\log_a(M-N)=\log_aM-\log_aN$. Power law requires a valid real RHS; $\log_a(M^2)=2\log_a|M|$ is more general than $2\log_a M$.

## 3. When a new logarithmic equation appears — fixed solution order

1. **State original domain:** every original argument $>0$; variable bases must be $>0$ and $\ne1$.
2. **Identify the pattern:** sums/differences -> product/quotient; coefficients -> power; nested/varied bases -> change base; exponential equalities -> same-base simplification then logarithms if required.
3. **Combine:** $\log_a F(x)=c\iff F(x)=a^c$; equality of same-base logs implies equality of arguments if both positive.
4. **Solve algebraically:** sometimes quadratic.
5. **Reject all roots outside the ORIGINAL domain** and verify remaining candidates.

## 4. Complete original worked examples aligned to actual teacher questions

### Teacher IB Prep Q8 — quotient/product rules
\`\`\`math
\log_3x-\log_34=3+\log_35
\`\`\`
Domain **$x>0$**. Since $3=\log_3 27$, rewrite:
\`\`\`math
\log_3(x/4)=\log_3(27\cdot5)=\log_3 135
\`\`\`
Then $x/4=135\Rightarrow\boxed{x=540}$.

### Teacher IB Prep Q18(b) — log to quadratic, reject extraneous root
\`\`\`math
\log_2x+\log_2(x-2)=3
\`\`\`
Domain **$x>2$**. Combine: $\log_2[x(x-2)]=3$, then
\`\`\`math
x^2-2x-8=0=(x-4)(x+2)
\`\`\`
Candidates $x=4,-2$; reject **$-2$** because $x>2$. **$x=4$** is the only solution.

### Teacher IB Prep Q6 — different exponential bases, express using log 3 and log 5
\`\`\`math
25^{x+3}=15^{2x}
\iff 5^{2x+6}=3^{2x}5^{2x}
\iff 5^6=3^{2x}.
\`\`\`
Take a logarithm:
\`\`\`math
6\log5=2x\log3\quad\Longrightarrow\quad
\boxed{x=\frac{3\log5}{\log3}}.
\`\`\`
**Tip:** simplify shared prime factors *before* taking logs.

### Teacher IB Prep Q17 — express using $p$ and $q$
Given $\log_a2=p$ and $\log_a3=q$ with $a>0,\ a\ne1$:
\`\`\`math
\begin{aligned}
\log_a12&=\log_a(2^2\cdot3)=2p+q,\\
\log_a(27/4)&=\log_a(3^3/2^2)=3q-2p,\\
\log_a\sqrt{18a}&=\tfrac12\log_a(2\cdot3^2\cdot a)=\tfrac12(p+2q+1).
\end{aligned}
\`\`\`

### Teacher IB Prep Q7 — logarithmic telescoping product
\`\`\`math
\log_{63}64\cdot\log_{62}63\cdots\log_2 3
=\frac{\ln64}{\ln63}\frac{\ln63}{\ln62}\cdots\frac{\ln3}{\ln2}
=\frac{\ln64}{\ln2}=\boxed{6}.
\`\`\`

### Teacher formative Q24 — domain excludes negative quadratic root
\`\`\`math
\log_5(x-2)+\log_5(2x+1)=2
\`\`\`
Domain **$x>2$**. Multiply:
\`\`\`math
(x-2)(2x+1)=25
\iff 2x^2-3x-27=0
\iff (2x-9)(x+3)=0.
\`\`\`
Candidates $x=9/2,-3$; discard $-3$. Answer **$x=9/2$**.

## 5. Domain examples — understand before solving

| Expression | Original real domain | Explanation |
|---|---|---|
| $\log_2(x-3)$ | $x>3$ | argument positive |
| $\log_x(x+1)$ | $x>0,\ x\ne1$ | variable base must be positive, unequal 1; argument is positive automatically |
| $\log_3((x-2)(x-3))$ | $x<2$ or $x>3$ | product strictly positive |
| $\log_2((x-1)/(x+2))$ | $x<-2$ or $x>1$ | fraction strictly positive and denominator nonzero |
| $\log_5(x-2)+\log_5(2x+1)$ | $x>2$ | BOTH arguments positive |

**Logarithmic function $y=\log_a x$:** domain $(0,\infty)$, range $\mathbb R$, vertical asymptote $x=0$. Increasing when $a>1$, decreasing for $0<a<1$. For $y=\log_a(x-h)+k$ (positive base $\ne1$), domain $x>h$ and vertical asymptote $x=h$; horizontal shift **does not** change the full real range.

**Log inequalities:**
\`\`\`math
a>1:\ \log_a u>\log_a v \iff u>v,\qquad
0<a<1:\ \log_a u>\log_a v\iff u<v,
\`\`\`
provided $u,v>0$. The inequality reverses for a base between 0 and 1.

## 6. Rapid exam recognition

| What question says / looks like | Method |
|---|---|
| Sum of logs with same base | product law |
| Difference of logs with same base | quotient law |
| $\log_a x=\text{constant}$ | convert to exponential form |
| $\log_a(x-r)+\log_a(x-s)$ | domain -> combine -> quadratic -> reject invalid |
| Exponential bases $25$ and $15$ | factor into primes -> cancel common exponent -> logs |
| $\log_a2=p,\ \log_a3=q$ | factor argument into 2s and 3s, power rules |
| Product of many $\log_{n-1}n$ | change base -> telescoping product |
| $\log_{h(x)}g(x)$ | **both variable-base and argument restrictions** |
| Difference of log expressions in an inequality | simplify, check positivity, and remember base $0<a<1$ reverses comparison |

**Authorised original notes only:** This is our original explanation, with teacher question patterns and a few brief equations used as instructional reference; do not upload original teacher PDFs or copyrighted textbooks to the public study repository.
