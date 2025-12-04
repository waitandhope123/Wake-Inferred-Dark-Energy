# Thawing Conditions in WIDE  
*Requirements for Late-Time Scalar-Field Evolution*

This document presents the complete set of physical and mathematical conditions that define **thawing** scalar-field models within the WIDE (Wake-Inferred Dark Energy) framework. These conditions distinguish thawing models from freezing models and ensure physical stability, GR consistency, and agreement with observations.

Equations referenced as (E#) appear in full in `/equations/equations.md`.

---

# 1. What Is a Thawing Model?

A **thawing** scalar-field model satisfies the following qualitative behavior:

1. The field φ is nearly constant at early times.  
2. Its kinetic energy is heavily suppressed by Hubble friction.  
3. The equation of state begins at w ≈ –1.  
4. Only when H(t) decreases sufficiently does φ slowly begin to roll.  
5. w(a) increases slightly above –1 at late times.

This behavior is consistent with:
- canonical scalar fields,
- minimal coupling,
- smooth potentials,
- and non-phantom dynamics.

---

# 2. The Frozen Initial Condition

A scalar field in an expanding universe obeys:

(E10) — Klein–Gordon Equation  
```
φ̈ + 3H φ̇ + dV/dφ = 0
```

At early times:
- H is large,
- so 3H φ̇ dominates over the slope term dV/dφ.

Thus:

(E23) — Frozen Condition  
```
3H φ̇  >>  dV/dφ  →  φ̇ ≈ 0
```

This leads directly to:

(E24) — Early-Time Equation of State  
```
w ≈ -1
```

This is the defining starting point for thawing behavior.

---

# 3. The Onset of Thawing

As the Universe expands:
- H ∝ a⁻³/² during matter domination,
- so the damping term 3H φ̇ steadily weakens.

Thawing begins when:

(E25) — Thaw Condition  
```
3H φ̇  ~  dV/dφ
```

At this moment, the field begins to move, slowly gaining kinetic energy.

The redshift of thawing, z_thaw, is typically between 0.5 and 2 for viable models.

---

# 4. Conditions on the Potential

To support thawing behavior, the potential V(φ) must satisfy several constraints:

## **Condition 1 — Smoothness**
The potential must have no sharp features:

(E26) — Smoothness Criterion  
```
|V′′ / V|  <<  1
```

## **Condition 2 — Shallow Slope**
The slope must be small enough that kinetic energy remains suppressed:

(E27) — Small Slope  
```
|V′ / V|  <  O(1) / M_pl
```

## **Condition 3 — Gentle Curvature**
To prevent rapid acceleration of φ:

(E28) — Gentle Curvature  
```
|V′′|  <<  H²
```

These are structural requirements for any thawing field in WIDE.

---

# 5. Constraints on w(a)

Because thawing models begin at w = –1 and evolve away from it:

(E29) — Thawing Inequality  
```
d w / d ln(a)  >  0
```

Additionally:

(E30) — Non-Phantom Condition  
```
w(a) > -1
```

WIDE prohibits any crossing of w = –1.

Typical thawing models satisfy:

(E31) — Thawing Range  
```
-1  <  w0  < -0.85
-0.25 < wa < 0
```

These bounds ensure compatibility with data and physical scalar-field behavior.

---

# 6. Small Field Excursion

Thawing models exhibit limited field displacement:

(E22 repeated) — Field Excursion  
```
|Δφ|  ≪  M_pl
```

This emerges because:
- φ̇ is small,
- thawing begins late,
- V′ is shallow.

This limited displacement is crucial for V(φ) reconstruction:  
the potential is probed over a small region of field space.

---

# 7. Kinetic Fraction Constraints

The kinetic fraction is:

(E17) — Kinetic Energy  
```
K = 1/2 ρ_φ (1 + w)
```

For thawing models:

(E32) — Kinetic Suppression  
```
1 + w(a)  <<  1
```

Typically:

(E33) — Observationally Consistent Range  
```
1 + w0  ~  0.05 ± 0.03
```

The limited kinetic fraction is what keeps thawing models close to ΛCDM.

---

# 8. Growth–Expansion Behavior

Thawing fields modify the growth of structure relative to ΛCDM.

Constraints:

1. The growth rate f(z) must be slightly suppressed relative to ΛCDM.  
2. The suppression must *not exceed* what GR allows for the reconstructed w(a).  
3. Growth deviations peak in the **Growth Focus Window** (0.3 < z < 1.2).

Thus WIDE requires:

(E34) — Allowed Growth Deviation  
```
|Δ fσ₈(z)|  <  few percent
```

This interacts strongly with potential reconstruction.

---

# 9. Thawing vs Freezing Models

Freezing models satisfy:

```
dw/d ln(a) < 0
```

and approach w = –1 from above.

Because WIDE is a **thawing-only** framework:

- freezing models are outside its domain,
- they serve as a falsification test,
- if data require freezing behavior, WIDE fails.

This is an explicit design choice.

---

# 10. Summary of Thawing Conditions

A scalar field is considered thawing within WIDE if the following hold:

1. **Early-time freezing:** φ̇ ≈ 0, w ≈ –1  
2. **Late-time thaw:** field begins rolling when H ~ |V′|  
3. **Shallow, smooth potential:** |V′| and |V′′| small  
4. **Non-phantom:** w > –1 at all times  
5. **Monotonic w(a) increase:** dw/d ln(a) > 0  
6. **Small field excursion:** |Δφ| ≪ M_pl  
7. **Kinetic suppression:** 1 + w ≪ 1  
8. **GR-consistent growth:** growth suppression matches expansion history  
9. **No freezing behavior allowed:** dw/d ln(a) must not be < 0  

These conditions sharply define the class of potentials and field dynamics allowed in WIDE.
