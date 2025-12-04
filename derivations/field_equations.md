# Field Equations in WIDE  
*Scalar-Field Dark Energy Within General Relativity*

This document derives the fundamental equations used in the WIDE (Wake-Inferred Dark Energy) framework. The goal is to present a transparent, step-by-step formulation of dark energy as a canonical, minimally coupled scalar field evolving within standard General Relativity (GR).

Explicit mathematical expressions are referenced as equation numbers (E1, E2, …).  
Their LaTeX forms will appear in `/equations/equations.md`.

---

# 1. Framework Assumptions

WIDE derives all field equations from the following assumptions:

1. **General Relativity is exact** on cosmological scales.  
2. **Dark energy is a single scalar field** φ with:  
   - canonical kinetic term,  
   - minimal coupling,  
   - smooth potential V(φ).  
3. **Thawing dynamics**: φ is initially frozen at w ≈ –1 and begins rolling at late times.  
4. **Non-phantom energy**: w > –1, ensuring positive kinetic energy.  
5. **Homogeneous background cosmology** in a Friedmann–Lemaître–Robertson–Walker (FLRW) metric.

---

# 2. The Action

WIDE begins from the standard Einstein–Hilbert action with a canonical scalar field:

(E1) — Total Action  
```
S = ∫ d^4x √(-g) [ (1/2κ) R - 1/2 g^μν ∂_μ φ ∂_ν φ - V(φ) ] + S_m
```

where:
- R is the Ricci scalar,
- κ = 8πG,
- S_m is the matter action (cold matter + radiation),
- V(φ) is the dark-energy potential.

---

# 3. Energy–Momentum Tensor of the Scalar Field

Varying the action with respect to the metric yields the scalar-field stress-energy tensor:

(E2) — Energy–Momentum Tensor  
```
T^φ_μν = ∂_μ φ ∂_ν φ - g_μν [ 1/2 (∂φ)^2 + V(φ) ]
```

For a spatially homogeneous scalar field φ(t), this reduces to perfect-fluid form.

---

# 4. Energy Density and Pressure of the Field

(E3) — Energy Density  
```
ρ_φ = 1/2 φ̇^2 + V(φ)
```

(E4) — Pressure  
```
p_φ = 1/2 φ̇^2 - V(φ)
```

(E5) — Equation of State  
```
w = p_φ / ρ_φ
```

These relations imply:

(E6) — Non-Phantom Condition  
```
φ̇^2 ≥ 0  →  w > –1
```

which is built into WIDE as a physical requirement.

---

# 5. Friedmann Equations

For a flat FLRW spacetime with scale factor a(t):

(E7) — First Friedmann Equation  
```
H^2 = (κ/3) (ρ_m + ρ_r + ρ_φ)
```

(E8) — Second Friedmann Equation  
```
Ḣ = - (κ/2) (ρ_m + ρ_r + ρ_φ + p_φ)
```

Where:
- ρ_m is matter density,
- ρ_r is radiation density,
- ρ_φ and p_φ come from the scalar field.

---

# 6. Conservation and Continuity

Because the scalar field is minimally coupled, its energy–momentum tensor is separately conserved:

(E9) — Conservation Equation  
```
ρ̇_φ + 3H(ρ_φ + p_φ) = 0
```

Substituting E3 and E4 yields the equation of motion for φ.

---

# 7. Klein–Gordon Equation in Cosmology

The scalar field evolves under the Klein–Gordon equation in an expanding background:

(E10) — Scalar Field Equation  
```
φ̈ + 3H φ̇ + dV/dφ = 0
```

This equation governs the thawing dynamics.

---

# 8. Expressing the Field in Terms of w(a)

Using the relations for ρ_φ and p_φ:

(E11) — Kinetic Energy  
```
(1/2) φ̇^2 = (1/2) ρ_φ (1 + w)
```

(E12) — Potential Energy  
```
V(φ) = (1/2) ρ_φ (1 - w)
```

These connect w(a) directly to φ̇ and V(φ).

---

# 9. Scalar Field Derivative with Respect to ln(a)

Define the dimensionless derivative:

(E13) — φ′(a)  
```
φ′ ≡ dφ / d ln(a) = φ̇ / H
```

Substituting E11:

(E14) — φ′² Relation  
```
φ′² = 3 Ω_φ(a) (1 + w(a)) M_pl^2
```

This is the bridge from equation-of-state space to field space.

---

# 10. Mapping to the Potential

Once ρ_φ(a) is known from w(a):

(E15) — Potential as a Function of Scale Factor  
```
V(a) = (1/2) ρ_φ(a) [1 - w(a)]
```

And using φ(a):

(E16) — Potential in Field Space  
```
V(φ) = V(a(φ))
```

This is the core of WIDE’s reconstruction method.

---

# 11. Summary

This document establishes the basic scalar-field and GR equations used throughout WIDE:

- The action for a canonical scalar field,
- Energy density and pressure relations,
- Friedmann equations,
- Scalar-field evolution,
- Conversion from w(a) to φ(a),
- Reconstruction of V(φ).

These equations are expanded upon in:

- `thawing_conditions.md` — conditions for thawing evolution  
- `potential_reconstruction.md` — full mapping to V(φ)  
- `gr_consistency.md` — growth/expansion consistency tests

All explicit equation forms will appear in `/equations/equations.md`.
