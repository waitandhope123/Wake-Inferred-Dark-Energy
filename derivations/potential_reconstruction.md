# Potential Reconstruction in WIDE  
*From Observational Wake to Scalar-Field Microphysics*

WIDE (Wake-Inferred Dark Energy) is fundamentally a **reconstruction framework**. Its central task is to recover the allowed space of scalar-field potentials V(φ) directly from the observational wake of dark energy: expansion, distances, and growth.

This document provides the complete methodology for reconstructing the potential from data.  
All referenced equations (E#) appear in `/equations/equations.md`.

---

# 1. Overview

The reconstruction pipeline follows the chain:

```
Observational data → H(a), D(a), fσ₈(a)
      ↓
Reconstruct w(a)
      ↓
Compute ρ_φ(a)
      ↓
Compute φ′(a) and integrate φ(a)
      ↓
Construct V(a)
      ↓
Map V(a) → V(φ)
```

Each step is fully determined within GR and canonical scalar-field physics.

---

# 2. Step 1 — Reconstructing w(a) from H(a)

The continuity equation for a general dark-energy component is:

(E19) —  
```
d ln ρ_φ / d ln a = -3 (1 + w(a))
```

Rewriting:

(E35) —  
```
1 + w(a) = - (1/3) d ln ρ_φ / d ln a
```

The total energy density driving H(a) is:

(E7) — Friedmann Equation  
```
H²(a) = (κ/3)[ρ_m(a) + ρ_r(a) + ρ_φ(a)]
```

Rearranging for ρ_φ(a):

(E36) —  
```
ρ_φ(a) = (3/κ) H²(a) - ρ_m(a) - ρ_r(a)
```

Then differentiate ρ_φ(a) with respect to ln(a).  
This yields w(a) directly from the expansion history.

This is the first core inversion in WIDE.

---

# 3. Step 2 — Compute ρ_φ(a) from w(a)

Given w(a), integrate:

(E20) —  
```
ρ_φ(a) = ρ_φ0 * exp[-3 ∫ (1 + w(a)) d ln a]
```

This ensures consistency between H(a), matter density evolution, and dark-energy evolution.

---

# 4. Step 3 — Computing φ′(a)

Use:

(E13) —  
```
φ′ ≡ dφ / d ln a = φ̇ / H
```

And the kinetic-energy relation:

(E11) —  
```
1/2 φ̇² = 1/2 ρ_φ (1 + w)
```

Substituting:

(E14) —  
```
φ′² = 3 Ω_φ(a) (1 + w(a)) M_pl²
```

Thus:

(E37) — Field Derivative  
```
φ′(a) = √[3 Ω_φ(a) (1 + w(a))] * M_pl
```

Since 1 + w is small for thawing models, φ′ is small.

---

# 5. Step 4 — Integrating φ(a)

Integrate:

(E38) —  
```
φ(a) = φ(a_ref) + ∫ φ′(a) d ln a
```

Choice of reference point:
- typically a_ref = 1 (today),
- φ(a_ref) can be set to zero without loss of generality.

Because thawing fields have small displacement:

```
|Δφ| ≪ M_pl
```

WIDE reconstructs V(φ) over a small region of φ-space.

---

# 6. Step 5 — Constructing V(a)

The potential as a function of scale factor is:

(E15) —  
```
V(a) = 1/2 ρ_φ(a) [1 - w(a)]
```

This gives the full time evolution of the potential.

At this stage V(a) is known numerically over the entire redshift range probed by data.

---

# 7. Step 6 — Mapping V(a) to V(φ)

Since φ(a) and V(a) are now known:

(E16) —  
```
V(φ) = V(a(φ))
```

This step produces a *parametric reconstruction*:

```
{ a_i , φ_i , V_i }
```

By interpolating:
- (a → φ),
- (a → V),

one obtains:

```
φ → V(φ)
```

This is the core of microphysical inference in WIDE.

---

# 8. Step 7 — Enforcing Thawing Conditions

The reconstructed V(φ) must satisfy all thawing constraints:

1. **w(a) > –1**  
(E30)

2. **dw/d ln(a) > 0**  
(E29)

3. **Smooth potential**  
(E26)

4. **Small slope**  
(E27)

5. **Small curvature**  
(E28)

6. **Small excursion**  
(E22)

Any reconstructed model violating these criteria is **discarded**.

This ensures WIDE remains within physically allowed thawing space.

---

# 9. Step 8 — Growth–Expansion Consistency Test

GR imposes a specific relation between H(a) and fσ₈(a).  
If data require growth inconsistent with a GR scalar field:

- the reconstructed potential may fit H(a),  
- but φ(a) evolution will predict the wrong growth,  
- and the model is rejected.

This step is detailed in `/derivations/gr_consistency.md`.

If GR fails:
- WIDE cannot fit the data,
- the scalar-field hypothesis is falsified.

---

# 10. Interpretation of Reconstructed Potentials

Reconstructed V(φ) typically appear as:

- shallow,
- monotonic,
- limited curvature,
- slowly varying potentials.

Typical shapes include:
- gently sloped linear segments,
- shallow exponentials,
- broad plateaus.

Because φ moves very little, even different theories may map to similar reconstructed shapes within the allowed φ-range.

WIDE provides:
- the allowed band of potentials,  
- not a single curve.

This is what it means to be **data-shaped**.

---

# 11. Summary of the Reconstruction Method

WIDE reconstructs the scalar potential by:

1. Extracting w(a) from H(a).  
2. Computing ρ_φ(a).  
3. Deriving φ′(a) from w(a).  
4. Integrating φ(a).  
5. Constructing V(a).  
6. Mapping V(a) → V(φ).  
7. Applying thawing and non-phantom constraints.  
8. Applying GR consistency conditions.

The final output is the **allowed potential family** consistent with:
- data,
- GR,
- thawing dynamics,
- and scalar-field microphysics.

This constitutes the core inference engine of WIDE.
