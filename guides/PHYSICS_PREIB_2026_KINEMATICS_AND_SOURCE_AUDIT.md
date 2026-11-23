# Fisika SAS Pre-IB — Kinematika dan Audit Sumber (23 Nov 2026)

**Metode belajar: TEACH ALL before testing.** The student's Pre-IB formative screenshots in a 1.70 MB ZIP are intended as the most important guide for question style/difficulty, but the ZIP's interior images have **NOT YET been inspected**: the extraction/code runner failed. Do not claim this guide is ZIP-verified. When images become available, inspect every one, map every question/diagram and refine priority. Materials for NON-IB students supplement basic competency, never replace the Pre-IB formative priority.

## Actual sources verified
1. Uploaded 4-page physics portion of **KISI-KISI SAS 20262027_KELAS 10.pdf**: 25 MCQs for physics, including vernier/micrometer readings with uncertainty, significant figures, sci notation, vector components, dimensions, GLB/GLBB, vertical up/down/free fall and projectile motion.
2. Uploaded **fisika projectile.mhtml**: AssessPrep page title **Projectile Motion — Summative Test**, 19 numbered groups Q1.1–Q1.19 with some multi-item groups. **Actually parsed** quoted-printable saved HTML and question stems: concepts, graph of vertical velocity, horizontal launch off table/cliff/plane, reconstruct launch, angled football and launch, complementary angles, max range, scaling with speed.
3. **Fikih**: KOMPAS original HTML is a separate authentic learner resource, fully inspected 6 chapters, 20 worked MCQ examples. Fikih 50 MCQs; separate study notes are advisable.

## Actual AssessPrep MHTML question matrix

| Questions | Exact prompt skill |
|---|---|
| Q1.1–1.5 | horizontal velocity constant, vertical velocity changes, apex vertical velocity zero but gravity down, simultaneous drop vs horizontal launch, independent components |
| Q1.6–1.8 | complementary 30°/60° ranges, 45° maximum ideal level-ground range, straight descending $v_y$-time graph |
| Q1.9 | marble horizontally off a 1.25m table at 2.0m/s: time and range |
| Q1.10 | stone horizontally from 80m cliff at 30m/s: horizontal range and magnitude of impact velocity |
| Q1.11 | plane at 100m/s, 500m altitude: release distance ahead of ground target |
| Q1.12 | horizontal launch lands 20m away after 2s: retrieve initial speed and launch height |
| Q1.13 | horizontal launch speeds v and 2v from same height: ranges 1:2 |
| Q1.14 | level-ground football 20m/s at 37°: vector components, time to top, maximum height, horizontal range |
| Q1.15 | level-ground projectile 50m/s at 53°: (x,y) at 2s; time to top and speed at top |
| Q1.16 | v=30m/s optimum launch angle and maximal range |
| Q1.17 | 30° vs 60° launch max heights ratio 1:3 |
| Q1.18 | idealized long jump speed 9m/s at 30°: same-level range |
| Q1.19 | double launch speed same angle: range quadruples |

**Do not mistake 19 group headings for exactly 19 independent subquestions:** several contain 2 or 4 prompts.

## I. Pengukuran dan Vektor — basic topics from official kisi-kisi
- Scalars have size only (distance, speed); vectors have size and direction (displacement, velocity, acceleration).
- Base dimensions: $[L]$, $[M]$, $[T]$. Speed $[LT^{-1}]$, acceleration $[LT^{-2}]$, force $[MLT^{-2}]$.
- Vernier: main scale before vernier zero + coincidence mark × vernier least count, correct any instrument zero error. Screw micrometer: sleeve reading + thimble mark × least count, correct zero error. In analog instruments ±half a scale division is a common **school convention**, but follow teacher's exact uncertainty rule if specified.
- Significant figures: multiplication/division by fewest significant figures, addition/subtraction by fewest decimal places; carry extra digits through intermediate steps.
- Vector components, angle above horizontal: $V_x=V\cos\theta$; $V_y=V\sin\theta$; vector magnitude $V=\sqrt{V_x^2+V_y^2}$.
- Dimensional consistency: every added term must carry the same physical dimensions, e.g. $ut$ and $at^2$ are both length.

## II. GLB, GLBB, graphs
- Displacement vs distance, velocity vs speed: negative velocity is possible; negative speed is not.
- GLB has $a=0$: $x=x_0+vt$.
- Constant-acceleration GLBB: $v=u+at$, $\Delta x=ut+\tfrac12at^2$, $v^2=u^2+2a\Delta x$, $\Delta x=(u+v)t/2$.
- Graphs: x–t slope velocity; v–t slope acceleration; **signed area** under v–t graph displacement; area under speed–t graph distance. Reverse signs carefully on braking/motion down.

**Derivation of displacement formula:** a constant-acceleration v–t graph is a trapezoid. Area = rectangle $ut$ + triangle $\tfrac12(v-u)t$. As $v-u=at$, area is $ut+\tfrac12at^2$.

## III. Vertical motion
Take upward positive and $g>0$ as the magnitude of gravity. Then $a_y=-g$:
- $v_y=u_y-gt$, $\Delta y=u_yt-\tfrac12gt^2$, $v_y^2=u_y^2-2g\Delta y$.
- At highest point $v_y=0$ but acceleration is still **$-g$**, not zero.
- $t_{\rm top}=u_y/g$ and $H_{\rm rise}=u_y^2/(2g)$.
- Free fall from rest through height $h$: $t=\sqrt{2h/g}$.
- If landing elevation differs, use actual $\Delta y$ and solve the resulting time equation; reject negative time.

## IV. Projectile motion: TWO axes, ONE clock
Neglect drag; take horizontal positive x, upward positive y. Launch with speed $v_0$ at angle $\theta$ above horizontal.
- $u_x=v_0\cos\theta$; $u_y=v_0\sin\theta$.
- $x(t)=x_0+u_xt$; $y(t)=y_0+u_yt-\tfrac12gt^2$.
- $v_x=u_x$; $v_y=u_y-gt$.
- Speed $v=\sqrt{v_x^2+v_y^2}$; angle from horizontal $\tan^{-1}(v_y/v_x)$ with quadrant attention.
- At apex $v_y=0$; horizontal velocity generally nonzero and gravitational acceleration still downward.
- Vertical velocity vs time is a straight line with slope $-g$, crossing $v_y=0$ at apex.
- **ONLY for launch and landing at equal elevations:** $T=2v_0\sin\theta/g$, $H=v_0^2\sin^2\theta/(2g)$, $R=v_0^2\sin2\theta/g$.
- Complementary angles (30°, 60°) give the SAME ideal level-ground range, but 60° yields higher flight and longer flight time.
- At constant speed max range at 45° (same-level), $R_{\max}=v_0^2/g$.
- With launch speed doubled at fixed angle, ideal same-level range multiplied by 4; height multiplied by 4.
- **Horizontal launch:** initial vertical speed zero, same fall time as dropped object; $t=\sqrt{2h/g}$, $R=u_xt$, impact vertical speed $-gt$.

## V. Teacher MHTML numerical worked examples
Use classroom $g=10\,\mathrm{m/s^2}$ **for illustrative calculation only**. If a question prescribes 9.8, use 9.8. If angle values are approximate, state that.

- Q1.9: table $h=1.25$m, $u_x=2.0$m/s. $t=\sqrt{2(1.25)/10}=0.5$s; range $2(0.5)=1.0$m.
- Q1.10: cliff $h=80$m, $u_x=30$m/s. $t=\sqrt{160/10}=4$s; range $120$m; $v_y=-40$m/s, impact speed $\sqrt{30^2+40^2}=50$m/s.
- Q1.11: plane $h=500$m, $u_x=100$m/s. $t=10$s, release $1000$m before target.
- Q1.12: $x=20$m in $t=2$s implies $u_x=10$m/s; $h=\tfrac12(10)(2)^2=20$m.
- Q1.13: ratio 1:2 because $R\propto u_x$ for same vertical fall time.
- Q1.14: football 20m/s at 37°; use $\sin37^\circ\approx0.6$, $\cos37^\circ\approx0.8$. Thus $u_x=16$m/s, $u_y=12$m/s. Apex $1.2$s, max height $7.2$m, total flight $2.4$s, range $38.4$m.
- Q1.15: 50m/s at 53°: $u_x\approx30$m/s, $u_y\approx40$m/s. At 2s: $x=60$m, $y=40(2)-5(2)^2=60$m. Apex at 4s with speed **30m/s**.
- Q1.16: speed 30m/s -> max range 90m at 45°.
- Q1.17: height ratio $\sin^230^\circ/\sin^260^\circ=(1/4)/(3/4)=1:3$.
- Q1.18: idealized long jump 9m/s, 30° -> range $81\sin60^\circ/10\approx7.0$m.
- Q1.19: doubling speed multiplies ideal same-level range by 4.

## VI. IB-style reasoning habits
State **given/unknown**, coordinate axes, sign conventions; distinguish scalar *speed* from vector *velocity*; document model assumptions (no drag, constant g, launch/landing elevations); use independent x-y equations linked by one time $t$; reject impossible time roots; interpret answers with units, appropriate significant figures and limitations. Do not just pick a formula from a memorized grid.

**Later plan**: extract every image in the primary Pre-IB ZIP (currently blocked), compare actual question type/frequency and graphical evidence, then adjust the guide. Practice and testing only when explicitly requested by the student.
