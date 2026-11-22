# Mathematics Study Guide 02 — Logarithms, from zero to Pre-IB
> **Standing learner preference (22 Nov 2026): TEACH ALL RELEVANT MATERIAL FIRST, THEN TEST ONLY WITH EXPLICIT OPT-IN.** Work through every major syllabus chapter and original notes in a cohesive teaching phase, from zero to Pre-IB depth. The learner may interrupt with questions at any point. Do not insert mini-quizzes, diagnostics, transfer problems or questions for the student to answer while the teaching phase is ongoing. Worked examples are permitted; label exercises in archived guides as *for later*. After all chapters have been explained, ask whether they want clarification or to switch to practice, but do not auto-start assessment.


**Original, reusable chapter. Grade X-6 SAS 23 November 2026.** School Pre-IB logarithm objectives; official IB Mathematics AA **SL1.5, SL1.7, SL2.9**; actual Oxford IB Prepared §1.3 pp. 13–16; Pearson AA HL Ch.4 contents confirmed. Teacher practice paper Q6–8, Q17–18(b); new exponent/log formative and practice banks. No teacher questions or copyrighted book text reproduced as a bulk worksheet.

## First: what IS a logarithm, and WHY was it invented?
You know that $2^3=8$: three powers of 2 produce 8. Now reverse the question: **How many powers of 2 give 8?** The answer is 3. Mathematicians needed a compact way to ask that question. That is a logarithm:

$$\boxed{2^3=8\quad\Longleftrightarrow\quad\log_2 8=3}.$$

Think of two inverse operations: "base to power" and "what power?" Addition undoes subtraction; multiplication undoes division; **logarithms undo exponentiation**.

If $y=a^x$ with $a>0$ and $a\ne1$, then $x=\log_a y$ for **$y>0$**. Notation: $a$ is the base; $y$ the *argument*; the log's output is the exponent.

Examples without a calculator:
- $\log_2 16=4$, because $2^4=16$.
- $\log_5 1=0$, because $5^0=1$.
- $\log_3(1/9)=-2$, because $3^{-2}=1/9$.
- $\log_9 3=1/2$, because $9^{1/2}=3$.

**Critical condition:** the base must be positive and not equal to 1, and a real logarithm's **argument must be strictly positive**. Its **answer/output may be negative**. Oxford's annotated sample student makes exactly this mistake: confusing a negative log *value* with a forbidden nonpositive *argument*.

## Derive the three log laws rather than guessing them
Let $x=\log_a M$, $y=\log_a N$ where $M,N>0$, $a>0$, $a\ne1$. By definition $a^x=M$, $a^y=N$.

**Product:** $MN=a^xa^y=a^{x+y}$, so
$$\boxed{\log_a(MN)=\log_a M+\log_a N}.$$

**Quotient:** $M/N=a^{x-y}$, so
$$\boxed{\log_a(M/N)=\log_a M-\log_a N}.$$

**Power:** $M^k=(a^x)^k=a^{kx}$, so
$$\boxed{\log_a(M^k)=k\log_a M}.$$

Two identity pairs:
$$\boxed{\log_a a=1,\quad \log_a 1=0}; \qquad
\log_a(a^x)=x,\quad a^{\log_a x}=x\quad (x>0).$$

**A trap:** $\log_a(M+N)\ne \log_a M+\log_a N$ generally. Counterexample: $\log_{10}(1+9)=1$, but $\log_{10}1+\log_{10}9=0+\log_{10}9\ne1$. Log laws operate on multiplication/division/powers, not direct addition/subtraction **inside** an argument.

## Change of base, explained
Let $y=\log_a x$, so $a^y=x$. Take a logarithm of both sides in any valid base $b$:
$y\log_b a=\log_b x$. Therefore
$$\boxed{\log_a x=\frac{\log_b x}{\log_b a}}.$$
For a calculator, $b=10$ (log) or $b=e$ (ln). The formula does NOT change the mathematical answer; it merely expresses the same question using a different base.

Example: $\log_4 8=\frac{\log_2 8}{\log_2 4}=\frac32$. A numerical calculator is unnecessary because both arguments are powers of 2.

## Example A — a full Pre-IB solution [illustrative 5-mark M/A/R allocation]
Solve
$$\log_2 x+\log_2(x-2)=3.$$
This structure also appears in the user's teacher IB-prep paper Q18(b). We show *complete* working:

**[R1 restriction]** Both arguments are positive: $x>0$ and $x-2>0$, hence $\boxed{x>2}$.

**[M1 combine using product law]**
$$\log_2[x(x-2)]=3.$$

**[M1 convert logarithm to power]** Since $\log_2 A=3$ means $A=2^3$,
$$x(x-2)=8,\quad x^2-2x-8=0.$$

**[A1 algebra]**
$$(x-4)(x+2)=0\quad\Rightarrow\quad x=4\text{ or }x=-2.$$

**[R/A1 final validity]** The candidate $-2$ violates $x>2$; it would make the logs undefined in the reals. Hence
$$\boxed{x=4}.$$
Check: $\log_2 4+\log_2 2=2+1=3$.

This M/A/R breakdown is *our illustration*, not a verbatim official teacher allocation.

## Example B — teacher Q8 method, not memorising its final value
Solve $\log_3 x-\log_3 4=3+\log_3 5$.
Restriction: $x>0$.
LHS $=\log_3(x/4)$. RHS $=\log_3(3^3)+\log_3 5=\log_3(27\cdot5)=\log_3 135$.
Since the exponential is one-to-one, $x/4=135$, so $\boxed{x=540}$. This satisfies $x>0$. The reasoning is more important than the number.

## Example C — no simple common power, use logarithms
Suppose $5^x=7$. Taking logs on both sides:
$x\ln5=\ln7$, so
$$\boxed{x=\frac{\ln7}{\ln5}}.$$
A real-log solution is exact unless the question specifically requests an approximation. Avoid rounding before the final step.

## Example D — telescope using change of base
For any $n>2$:
$$\log_{n-1}n\cdot\log_{n-2}(n-1)=
\frac{\ln n}{\ln(n-1)}\cdot\frac{\ln(n-1)}{\ln(n-2)}
=\frac{\ln n}{\ln(n-2)}.$$
The middle factors **cancel**. In a long chain, this is a telescope. The user's teacher practice paper Q7 has this exact *structure*, so practise recognising cancellation before multiplying anything numerically.

## Graph: why logs have a vertical asymptote
Reflect $y=2^x$ across the line $y=x$ to obtain its inverse $y=\log_2x$.

| Graph | Domain | Range | Asymptote | Reference point |
| --- | --- | --- | --- | --- |
| $y=2^x$ | $\mathbb R$ | $(0,\infty)$ | $y=0$ horizontal | $(0,1)$ |
| $y=\log_2x$ | $(0,\infty)$ | $\mathbb R$ | $x=0$ vertical | $(1,0)$ |

The log's domain is positive because it *receives* outputs of the exponential. Its value may be arbitrarily negative because its corresponding positive input approaches $0$ from the right.

## Five mistakes that cost marks
1. Combining $\log(x+2)$ as $\log x+\log2$: **false**.
2. Starting algebra before writing argument restrictions, then keeping an extraneous root.
3. Rejecting $\log_2(1/4)=-2$ as "negative": **false** (the argument is positive).
4. Confusing $\log_a x$ with $a\log x$ or $\log x/\log a$ without stating the latter is a change-of-base expression.
5. Using the quadratic formula successfully but ignoring that the resulting roots must satisfy the *original* log restrictions.

## Memorise by *reconstruction*
- Say aloud: **“A log asks: what exponent?”** $a^b=c \leftrightarrow \log_a c=b$.
- Rebuild product/quotient/power rules in 20 seconds from $a^ua^v=a^{u+v}$.
- Put **ARGUMENT > 0** at top of every log-equation solution before manipulating it.
- Close your notes: explain why a logarithm can be negative but cannot have a negative real argument.
- **Retrieval next morning:** derive change-of-base; sketch log with x=0 boundary; solve one log equation and reject invalid candidates.

## Now—and only after the reading—optional original practice
Solve $\log_3(x-1)+\log_3(x+1)=1$. Begin with the valid domain; don't trust both quadratic candidates automatically. If confused, first explain the meaning of $\log_3 9=2$.

**Next:** [Quadratics](MATH_03_QUADRATICS.md) and [SPLTV + linear programming](MATH_04_LINEAR_PROGRAMMING.md).
