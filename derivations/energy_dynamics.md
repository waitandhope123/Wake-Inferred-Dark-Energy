# Energy Dynamics of Dark Energy in WIDE  
*Evolution of the Scalar-Field Energy Density and Equation of State*

This document explains how the energy density, pressure, and equation of state of a canonical scalar-field dark energy evolve over time within the WIDE (Wake-Inferred Dark Energy) framework.

Where appropriate, equations are referenced by their internal IDs (E#).  
Their full LaTeX expressions will be collected in `/equations/equations.md`.

---

# 1. Overview

Dark energy in WIDE is modeled as a canonical scalar field φ with potential V(φ). Its energy content is composed of:

- a **kinetic** component, and  
- a **potential** component.

The balance between these determines:
- the equation of state w(a),
- the expansion rate H(a),
- the field evolution φ(a),
- and the dark-energy contribution to structure growth.

Energy dynamics are central to WIDE’s reconstruction pipeline.

---

# 2. Energy Density and Pressure

From the field equations:

(E3) — Energy Density  
```
ρ_φ = 1/2 φ̇² + V(φ)
```

(E4) — Pressure  
```
p_φ = 1/2 φ̇² - V(φ)
```

These combine to define the equation of state:

(E5) — Equation of State  
```
w = p_φ / ρ_φ
```

### Interpretation:
- **w → –1** when φ̇² ≪ V(φ) (potential dominated; cosmological constant–like).  
- **w > –1** whenever φ̇² > 0 (canonical scalar field).  
- **w increases** as the kinetic fraction grows.

WIDE enforces w > –1 at all times.

---

# 3. Kinetic and Potential Decomposition

Rewrite E3 and E4:

(E17) — Kinetic Energy  
```
K ≡ 1/2 φ̇² = 1/2 ρ_φ (1 + w)
```

(E18) — Potential Energy  
```
V ≡ V(φ) = 1/2 ρ_φ (1 - w)
```

These relationships will be used repeatedly in reconstruction.

---

# 4. Evolution of ρ₍φ₎(a)

Because the scalar field is minimally coupled:

(E9) — Conservation Equation  
```
ρ̇_φ + 3H (ρ_φ + p_φ) = 0
```

Using w = p/ρ, this becomes:

(E19) — Density Evolution  
```
d ln ρ_φ / d ln a = -3 (1 + w(a))
```

Integrating:

(E20) — General Solution  
```
ρ_φ(a) = ρ_φ0 * exp[ -3 ∫ (1 + w(a)) d ln a ]
```

This equation is central to reconstructing:
- φ(a),
- V(a),
- and ultimately V(φ).

---

# 5. Evolution of the Hubble Parameter H(a)

The first Friedmann equation:

(E7) — Friedmann Constraint  
```
H²(a) = (κ/3) [ρ_m(a) + ρ_r(a) + ρ_φ(a)]
```

with:
- ρ_m(a) ∝ a⁻³  
- ρ_r(a) ∝ a⁻⁴  
- ρ_φ(a) given by (E20)

Thus, the expansion is directly linked to w(a).

---

# 6. Thawing Dynamics and Kinetic Suppression

In thawing models:
- Early times have large H,
- Leading to large damping term 3H φ̇ in the Klein–Gordon equation.

This suppresses kinetic energy:

(E21) — Frozen State Condition  
```
φ̇ ≈ 0  →  w ≈ -1
```

As H falls:
- the damping term weakens,
- the field begins to roll,
- kinetic energy increases slightly,
- w rises toward values like –0.9 or –0.85.

This transition defines thawing behavior and is essential to WIDE.

---

# 7. Small Field Displacement

In thawing models, the field displacement from early times to today satisfies:

(E22) — Small-Displacement Criterion  
```
|Δφ| < O(1) * M_pl
```

Typically much smaller.

This limits:
- the slope of the potential,
- how far φ can roll,
- and how much w(a) can evolve.

It also stabilizes reconstruction by avoiding large-field degeneracies.

---

# 8. Linking Energy Dynamics to Observables

Because ρ₍φ₎(a) determines H(a), which feeds into:

- distances D(z),
- BAO scales,
- supernova magnitudes,
- structure growth fσ₈(z),

the energy dynamics of φ directly shape the observational wake.

### Example dependencies:

- Higher kinetic fraction → slightly faster late-time expansion → larger D(z).
- Lower potential curvature → more gradual thawing → slower evolution of w(a).
- Strong deviation in ρ₍φ₎(a) → inconsistent fσ₈(z).  
- Too much kinetic energy → growth suppression inconsistent with data.

These sensitivity patterns are formalized in the predictions files.

---

# 9. Summary of Energy Dynamics

WIDE’s energy-dynamics framework rests on:

- Canonical kinetic + smooth potential energy form.  
- Non-phantom condition ensures w > –1.  
- Density evolution is controlled by w(a).  
- Thawing models start from w = –1 and gently evolve upward.  
- ρ₍φ₎(a) determines H(a), which determines the observable wake.  
- All reconstructions of V(φ) begin by determining ρ₍φ₎(a) from data.

Energy dynamics are the bridge between:
- the scalar-field microphysics, and  
- the expansion and growth signatures we observe.
