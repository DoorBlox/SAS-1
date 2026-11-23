# PHYSICS PRE-IB — MASTER FORMULA CHEAT SHEET (SAS 2026)

**Based on actual 35-question Kinematics Formative X6 screenshots Q1.1–Q1.35.** Teacher reportedly said SAS Pre-IB is similar. **This is not the separate 25-MCQ REGULAR Physics kisi-kisi.** Materials for regular-class enrichment are explicitly labelled below.

**Primary references:** [Exact 35-question-to-topic index and 8 REGULAR PDF source crosswalk](PHYSICS_00_PREIB_35Q_AND_REGULAR_CROSSWALK.md); the user's 26 photos and separate projectile MHTML. **Use g = 10 m/s²** unless the question specifies another value.

## 0. Symbols

| Symbol | Meaning | Unit |
|---|---|---|
| $u$ | initial velocity | m/s |
| $v$ | final velocity | m/s |
| $a$ | acceleration | m/s² |
| $s, \Delta x$ | displacement (signed) | m |
| $x_0, y_0$ | initial coordinates | m |
| $t$ | elapsed time | s |
| $g$ | magnitude of gravitational acceleration | m/s² |
| $\theta$ | angle | degrees or radians consistently |
| $R$ | horizontal range / resultant magnitude (by context) | m or vector unit |
| $H$ | vertical height gained | m |
| $T$ | total flight time | s |

---

# PART I — FORMULA WALL: ALL FORMULAS CLUMPED TOGETHER

## A. Definitions (speed, velocity, acceleration)


```math
\Delta x=x_f-x_i
```


```math
\text{Average speed}=\frac{\text{total distance}}{\Delta t}
```


```math
\vec v_{\rm avg}=\frac{\Delta\vec r}{\Delta t},\qquad \vec a_{\rm avg}=\frac{\Delta\vec v}{\Delta t}
```


**Distance** = full path length (scalar). **Displacement** = final position minus start (vector). Speed is scalar; velocity and acceleration are vectors.

## B. GLB (constant velocity)


```math
a=0,\qquad s=vt,\qquad x=x_0+vt
```

## C. GLBB / SUVAT (constant acceleration only)


```math
\boxed{v=u+at}
```


```math
\boxed{s=ut+\frac12at^2}
```


```math
\boxed{v^2=u^2+2as}
```


```math
\boxed{s=\frac{u+v}{2}t}
```


```math
u=0\implies v=at,\quad s=\frac12at^2\propto t^2
```

## D. Kinematic graphs

| Graph | Gradient | Area |
|---|---|---|
| Position vs time $x(t)$ | velocity $v$ | not normally used for displacement |
| Velocity vs time $v(t)$ | acceleration $a$ | **signed displacement** |
| Acceleration vs time $a(t)$ | rate of change of acceleration | **change in velocity** |


```math
A_{\rm rectangle}=bh,\quad A_{\rm triangle}=\tfrac12 bh,\quad A_{\rm trapezium}=\tfrac12(a+b)h
```

For velocity graphs, **total distance** is the area under $|v(t)|$; **displacement** is signed area below/above the time axis.

## E. Vectors, relative motion and direction

For an angle **from the horizontal**:


```math
A_x=A\cos\theta,\qquad A_y=A\sin\theta
```

For an angle **from the vertical**, swap sine/cosine:


```math
A_x=A\sin\theta,\qquad A_y=A\cos\theta
```


```math
R_x=\sum A_x,\quad R_y=\sum A_y,\quad |\vec R|=\sqrt{R_x^2+R_y^2}
```


```math
\tan\theta=\frac{R_y}{R_x}\qquad\text{(resolve the correct quadrant)}
```


```math
\boxed{\Delta\vec v=\vec v_2-\vec v_1}
```


```math
\vec v_{\rm boat/ground}=\vec v_{\rm boat/water}+\vec v_{\rm water/ground}
```

## F. Vertical motion — UPWARD positive


```math
a_y=-g,\quad v_y=u_y-gt,\quad y=y_0+u_yt-\tfrac12gt^2
```


```math
v_y^2=u_y^2-2g(y-y_0)
```


```math
\text{At apex: }v_y=0,\quad t_{\rm up}=\frac{u_y}{g},\quad H=\frac{u_y^2}{2g}
```

For return to **same height**, **no drag**, upward initial velocity:


```math
T=\frac{2u_y}{g},\qquad v_{y,\rm landing}=-u_y
```

For horizontal launch or drop with $u_y=0$ from height $h$:


```math
h=\tfrac12gt^2,\quad t=\sqrt{\frac{2h}{g}}
```

## G. Projectile motion — UPWARD positive, angle above HORIZONTAL


```math
u_x=u\cos\theta,\quad u_y=u\sin\theta
```


```math
x=x_0+u_xt,\quad v_x=u_x,\quad a_x=0
```


```math
y=y_0+u_yt-\tfrac12gt^2,\quad v_y=u_y-gt
```


```math
|\vec v|=\sqrt{v_x^2+v_y^2}
```

**ONLY** if launch and landing heights are equal AND no air resistance:


```math
\boxed{T=\frac{2u\sin\theta}{g}}
```


```math
\boxed{H=\frac{u^2\sin^2\theta}{2g}}
```


```math
\boxed{R=\frac{u^2\sin(2\theta)}{g}}
```

For **horizontal launch** from height $h$ with no drag:


```math
t=\sqrt{\frac{2h}{g}},\qquad R=u_x\sqrt{\frac{2h}{g}}
```


```math
v_{\rm impact}=\sqrt{u_x^2+2gh}
```

For a target at horizontal position $x$, and launch from $(x_0,y_0)$ with $u_x\ne0$:


```math
y(x)=y_0+(x-x_0)\tan\theta-\frac{g(x-x_0)^2}{2u^2\cos^2\theta}
```

Useful general **impact speed** for any ideal projectile falling vertically through height $h=y_0-y_{\rm impact}$:


```math
v_{\rm impact}=\sqrt{u^2+2gh}\qquad \text{(no drag, any launch angle)}
```

## H. Proportionalities and identities


```math
R\propto u^2\ (\theta,g\ {\rm fixed}),\quad H\propto u_y^2,\quad x\propto t\ (a_x=0),\quad h\propto t^2\ (u_y=0)
```


```math
\theta_1+\theta_2=90^\circ\Rightarrow R_1=R_2\quad\text{(same-speed, equal-height ideal flight)}
```


```math
R_{\rm max}=\frac{u^2}{g}\quad \text{at }\theta=45^\circ\ \text{(same-height ideal flight)}
```

## I. Circular motion — additional context for Q1.35


```math
\Delta\vec v=\vec v_{\rm final}-\vec v_{\rm initial}
```


```math
|\Delta\vec v|=\sqrt2\,v\quad\text{for perpendicular equal-speed velocities}
```


```math
a_c=\frac{v^2}{r}\quad\text{(extra contextual relationship; not a numerical requirement of Q1.35)}
```


---

# PART II — WHICH FORMULA FOR WHICH QUESTION?

| Look for these words or graph | Use this | Teacher formative |
|---|---|---|
| "Final speed", initial speed, $a$ and $t$ given | $v=u+at$ | Q1.6 |
| "How far from rest after $t$?" | $s=\frac12at^2$ | Q1.11 |
| "Maximum height", $u$ or vertical launch velocity given | $v_y=0$, $H=u_y^2/(2g)$ | Q1.1, Q1.3 |
| "From cliff", "horizontally thrown" | vertical equation for $t$, then $x=u_xt$ | Q1.7, 1.16, 1.25 |
| "Speed just before impact" | $v_y^2=u_y^2+2g h$, then $\sqrt{v_x^2+v_y^2}$ | Q1.34 |
| $v$–$t$ graph and "distance" | add all areas under graph (absolute if negative) | Q1.5, 1.9, 1.10, 1.20 |
| "Acceleration from a table" | $\Delta v/\Delta t$ | Q1.12 |
| "Which acceleration–time graph?" | calculate slopes of $v$–$t$ segments | Q1.23 |
| "Increasing acceleration" | velocity curve with increasing slope | Q1.33 |
| Equal-time snapshots with narrowing gaps | slowing down; velocity-time downward slope | Q1.32 |
| Position-time straight line then flat | constant velocity then stopped | Q1.22 |
| "Average speed" different stages | total distance / total time | Q1.19 |
| Boat current vs ferry direction perpendicular | $\sqrt{v_x^2+v_y^2}$ | Q1.4 |
| "How far east/north?" | component $A\cos\theta$ or $A\sin\theta$, NOT total resultant | Q1.18 |
| Angle is measured **from vertical** | horizontal = $u\sin\theta$ | Q1.27 |
| East/north/west path | sum signed $x$ and $y$; Pythagoras | Q1.28 |
| "Change in velocity" | $\vec v_2-\vec v_1$; compare component signs | Q1.35 |
| Projectile same-height landing, no drag | $R=u^2\sin2\theta/g$ | Q1.8, 1.15, 1.30 |
| Projectile same-height, "time in air" | $T=2u_y/g$ | Q1.17, 1.31 |
| Comparing speed during ideal projectile | $v=\sqrt{v_x^2+v_y^2}$; smallest at apex | Q1.13, 1.21 |
| Horizontal launch, time doubled | $x\propto t$ but fallen $h\propto t^2$ | Q1.29 |
| "Air resistance acts" | Qualitative drag model; **don't assume** $v_x$ stays constant | Q1.14, 1.24 |

## Important domain and validity checklist

- **SUVAT / GLBB** requires **constant acceleration** for the interval being solved. If acceleration changes, split stages or use a more general model. Q1.33 tests increasing acceleration conceptually.
- **Range $R=u^2\sin2\theta/g$**, **total flight time $T=2u\sin\theta/g$**, **45° maximum range**, and **complementary angles** assume **same start/end height**, **constant gravity** and **negligible air resistance**.
- At a projectile's **highest point**, vertical velocity $v_y=0$ BUT total speed need not be zero and acceleration remains downward $-g$.
- **Negative velocity** indicates direction, not automatically slowing down; compare velocity and acceleration signs.
- **Angle from the VERTICAL** swaps the usual horizontal sine/cosine relations.
- **Velocity-time** area gives signed **displacement**, not automatically total distance if direction reverses; **position-time** slope gives velocity.
- **Horizontal launch:** $u_y=0$, not $u=0$.
- When $g$ is treated as positive, choose upward $a_y=-g$ or downward $a_y=+g$ consistently.
- **Average speed** is total distance divided by total time, not the arithmetic mean of speeds unless intervals have appropriate equal weights.
- Vector subtraction: $-\vec v_1$ reverses its direction; Q1.35 bottom-left initial to left-side up gives $\Delta\vec v$ **northeast**, option D.

## Quick check worked examples from verified screenshots

**Q1.5:** Tram acceleration 0→20 m/s in 8 s; cruise 15 s; braking to 0 in 4 s. Total area $=0.5(8)(20)+15(20)+0.5(4)(20)=420$ m.

**Q1.10:** Runner P area $=0.5(4)(10)+6(10)=80$ m; runner Q area $=0.5(10)(16)=80$ m; same distance, despite different final velocities.

**Q1.25:** Package from 80 m with $v_x=50$ m/s: $80=5t^2\Rightarrow t=4$ s, so $x=50(4)=200$ m.

**Q1.26:** Cricket ball $v_{x0}=40,\ v_{y0}=30$ m/s: at $t=4$ s, $v_x=40$ and $v_y=30-10(4)=-10$ m/s.

**Q1.34:** Horizontal launch $u_x=15$ m/s from height $h=20$ m: $v_y=-\sqrt{2(10)(20)}=-20$, resultant impact speed $\sqrt{15^2+20^2}=25$ m/s.

## REGULAR — Additional formulas NOT established as separate PRE-IB SAS topics

These appear in the school's 25-MCQ **regular-class** kisi-kisi and the eight regular Physics PDFs; learn for broader competence, but they are **not confirmed by the X6 35-question formative as separate SAS items**.

| Topic | Formula / rule |
|---|---|
| Scientific notation | $N=a\times10^n$, $1\le |a|<10$ for $N\ne0$ |
| km/h to m/s | divide by 3.6 |
| m/s to km/h | multiply by 3.6 |
| Velocity dimension | $[v]=LT^{-1}$ |
| Acceleration dimension | $[a]=LT^{-2}$ |
| Dimensional check | every added term in a physical equation must have the same dimensions |
| Percentage error vs reference | $\left|\frac{x_{\rm measured}-x_{\rm reference}}{x_{\rm reference}}\right|\times100\%$ (nonzero reference) |
| Significant figures: product/quotient | final measured result ordinarily matches fewest significant figures of measured inputs |
| Significant figures: addition/subtraction | final result matches least precise decimal place of inputs |
| Analogue scale uncertainty | often approximated as half a smallest division for a single reading, **but follow instrument/teacher conventions** |
| Digital scale uncertainty | depends on calibration/specification; sometimes ±1 last displayed digit, not universally |

**Example regular vs Pre-IB distinction:** The REGULAR papers include vernier calipers, micrometers and numbers of significant figures. The 35 photographed **Pre-IB formative questions do not separately test these as visible items**. Do not mistake a regular revision sheet for a confirmed IB SAS blueprint.

---

**Exam memory method:** Start with the question's **model and assumptions** → identify horizontal/vertical/graph/vector → choose a formula containing the known values and target unknown → substitute with correct signs and units → check physical reasonableness.

**Learning protocol:** Teach all materials and worked examples before offering quizzes; user chooses when to start testing.
