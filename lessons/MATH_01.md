# Lesson M1 — Exponents, logarithms, quadratic reasoning and the essay method

**School evidence:** Master school Pre-IB Mathematics entry, pp. 2–3, for **15 essay questions**. This is an original tutor lesson and not a verbatim Pearson or IB passage.

## Objectives
By the end you should be able to: (1) manipulate exponential expressions while stating conditions; (2) explain increasing/decreasing exponent graphs; (3) solve logarithm equations without accepting invalid domains; (4) connect roots and coefficients using Vieta; (5) optimize a linear objective over a feasible region, justifying the optimum. Each objective maps to the school topics.

## 1. Exponents: rules have conditions

For a nonzero real base `a`: `a^m*a^n = a^(m+n)`, `a^m/a^n = a^(m-n)`, `(a^m)^n = a^(mn)`, `a^(-n)=1/a^n`. Fractional exponents, when working over real numbers, require additional domain checks (for example even roots need nonnegative radicand).

**Common trap:** `(a+b)^2` is **not** `a^2+b^2`; expand to `a^2+2ab+b^2`.

**Worked example.** Solve `3^(2x)-10*3^x+9=0`. Let `t=3^x>0`. Then `t^2-10t+9=0=(t-1)(t-9)`, so `t=1` or `9`; thus `x=0` or `x=2`. Check both in the original equation. Emphasize that substitution has a **positive** domain.

## 2. The exponent graph
`y=a^x` for `a>0, a!=1`: domain all real numbers; range positive; y-intercept 1; horizontal asymptote `y=0`; increasing if `a>1`, decreasing if `0<a<1`. For `y=2^(x-1)+3`, asymptote is `y=3`, and `(1,4)` lies on the graph.

Visual check: https://www.desmos.com/calculator — enter `y=2^(x-1)+3` and `y=3`. **Explain** the transformation before checking.

## 3. Logs are inverse exponents, with domain restrictions
`log_b(a)=c` iff `b^c=a` for `a>0, b>0, b!=1`. `log_b(xy)=log_b(x)+log_b(y)` when both inputs positive; `log_b(x/y)=log_b(x)-log_b(y)`; `log_b(x^k)=k log_b(x)` under valid real-number conditions.

**Worked example.** Solve `log_2(x-1)+log_2(x-3)=3`. Domain: `x>3`. Combine to `(x-1)(x-3)=8`, hence `x^2-4x-5=0=(x-5)(x+1)`. Candidates `5,-1`; only `x=5` meets `x>3`. The answer is `{5}`, not `{5,-1}`.

## 4. Quadratic Vieta and transformations
For `ax^2+bx+c=0` (a nonzero), roots `r,s` satisfy `r+s=-b/a` and `rs=c/a`. The monic polynomial with roots `r+k,s+k` is `x^2-(r+s+2k)x+(rs+k(r+s)+k^2)`.

**Worked example.** The roots of `2x^2-5x+2=0` are `r,s`. Determine a quadratic whose roots are `r+2,s+2`. Old sum `5/2`, product `1`. New sum `13/2`, new product `1+2(5/2)+4=10`. New quadratic `x^2-(13/2)x+10=0`, or `2x^2-13x+20=0`. Verify by plugging transformed roots.

## 5. Linear programming — maximize a function on a feasible region
Suppose `x>=0,y>=0,x+y<=8,2x+y<=10`, maximize `P=3x+2y`. The vertices are `(0,0),(5,0),(2,6),(0,8)`. Their P values are 0,15,18,16. Hence max `P=18` at `(2,6)`. Explain why each vertex is feasible and how the intersection `(2,6)` was obtained. This vertex method applies to a bounded polygonal feasible region for a linear objective.

Plot in Desmos: https://www.desmos.com/calculator with `x>=0`, `y>=0`, `x+y<=8`, `2x+y<=10` (syntax may be adjusted for restrictions).

## 6. How a 15-essay answer earns credit
- State what is required, define variables.
- Record domain/constraints before algebra.
- Use a logically complete sequence of transformations.
- Explain why candidates are valid (especially logarithms, inequalities and intersections).
- Give a final sentence with units or context, and verify when feasible.

## Now YOU try (do not read an answer yet)
A. Solve `4^x-5*2^x+4=0`. Explain the substitution domain.
B. Solve `log_3(x-2)+log_3(x+2)=2`. Show the logarithm domain and reject invalid values.
C. Let `r,s` be roots of `x^2-4x+1=0`. Write a quadratic whose roots are `r+3,s+3` using Vieta (without calculating r and s individually).
D. Find the maximum `Z=4x+3y` subject to `x,y>=0,x+y<=7,2x+y<=10`. Explain all vertices.

Send your worked solution to A first. Tutor: mark it interactively before revealing the next full answer.
