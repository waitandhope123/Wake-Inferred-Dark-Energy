# WIDE Theory Overview  
*Wake-Inferred Dark Energy — Conceptual and Theoretical Framework*

WIDE (Wake-Inferred Dark Energy) is a cosmological framework that reconstructs the microphysical properties of dark energy from the *observational wake* it leaves behind. Rather than assuming a potential, WIDE works backward from data to identify the scalar-field dynamics and the allowed space of models consistent with General Relativity (GR).

This document explains the entire theoretical structure of WIDE at a high conceptual level.  
Mathematical derivations appear in the `/derivations/` folder, and all equations are centralized in `/equations/equations.md`.

---

# 1. Motivation and Context

Modern cosmology relies heavily on parameterized models of dark energy:
- the cosmological constant (Λ),
- simple quintessence potentials,
- phenomenological w(a) parametrizations.

These approaches either make strong theoretical assumptions (e.g., exponential potentials) or use abstract parameters disconnected from microphysics.

WIDE takes a different approach:

> **Do not assume the potential. Infer it directly from the full observational wake left by dark energy.**

The “wake” encompasses:
- expansion history H(z),
- distance measurements (BAO, SNe),
- structure growth (fσ₈(z)),
- weak-lensing shear,
- CMB distance priors,
- GR consistency between expansion and growth.

This transforms dark-energy inference into a reverse problem:
data → w(a) → φ(a) → V(φ).

---

# 2. Physical Assumptions of WIDE

WIDE intentionally restricts itself to the simplest, cleanest physical space:

### **2.1 General Relativity is correct**
- No modified gravity.
- No extra metric degrees of freedom.
- Growth and expansion are tied by GR consistency.

### **2.2 Dark energy is a single canonical scalar field**
- Minimal coupling.
- Standard kinetic term.
- Smooth potential V(φ).
- No phantom behavior (w > –1 at all times).

### **2.3 Thawing dynamics**
The field was frozen by Hubble friction at early times (w ≈ –1) and has recently begun rolling.  
This behavior naturally emerges from many small-field and slow-roll potentials.

### **2.4 Non-phantom energy condition**
WIDE strictly forbids:
- phantom fields,
- ghosts,
- super-acceleration,
- Big Rip scenarios.

### **2.5 Observations define the potential**
V(φ) is not guessed, postulated, or fixed.  
It is reconstructed from data-defined field evolution.

---

# 3. The Wake-Inference Concept

Dark energy affects multiple sectors simultaneously.  
Its “wake” is the total pattern of observational consequences.

WIDE defines the wake as the set:

- expansion rate H(z),
- distances D(z),
- redshift-space distortions fσ₈(z),
- weak-lensing amplitude,
- CMB Legendre-distance constraints,
- matter density evolution,
- GR consistency relationships.

The unique structure of these combined signatures directly constrains:
- the kinetic fraction (1 + w),
- the field’s displacement Δφ,
- the slope V′(φ),
- the curvature V″(φ).

Thus, the true microphysics of dark energy can be reconstructed from its cosmological wake.

---

# 4. Theoretical Architecture of WIDE

The core flow of WIDE is:

```
1. Observational data → H(z), D(z), fσ₈(z)
2. From H(z) → w(a) (with GR and energy conservation)
3. From w(a) → φ′(a) and φ(a)
4. From φ(a) → V(φ)
5. Compare reconstructed V(φ) to theoretical expectations
6. Reject or refine the allowed model space
```

Each step is governed by GR and scalar-field physics.

The detailed mathematical expressions are provided in:
- `/derivations/field_equations.md`
- `/derivations/thawing_conditions.md`
- `/derivations/potential_reconstruction.md`
- `/equations/equations.md`

---

# 5. Scalar-Field Dark Energy in WIDE

WIDE assumes a canonical scalar field with Lagrangian:

```
L = -½(∂φ)² - V(φ)
```

This leads to:
- energy density,
- pressure,
- equation of state,
- field dynamics equations.

All explicit forms appear in the equation library.

### **Key points:**
- w(a) determines the ratio of kinetic to potential energy.
- The field evolves according to the Klein–Gordon equation in an expanding universe.
- Thawing dynamics require V(φ) to be shallow and smooth.

---

# 6. Thawing Dynamics

A thawing scalar field:
- starts with w ≈ –1 at high redshift,
- begins to roll only when Hubble friction drops,
- produces mild evolution w(z) that deviates from Λ.

WIDE embeds thawing behavior as a structural prior:
- w₀ ≳ –1
- wₐ ≲ 0
- small field displacement Δφ
- small kinetic fraction

These constraints greatly narrow the possible potentials.

---

# 7. Reconstruction Pathway

WIDE reconstructs the microphysics through the following chain:

### **Step 1: Reconstruct w(a)**  
From H(z) using the continuity equation (see Eq. E12 in equations.md).

### **Step 2: Compute φ′(a)**  
Using scalar-field relations (see Eq. E20).

### **Step 3: Integrate φ(a)**  
Field position follows from integrating φ′(a).

### **Step 4: Construct V(a)**  
Energy density ρ_DE(a) is known from w(a).

### **Step 5: Map V(a) → V(φ)**  
This yields the potential in physical field space.

The result is a **data-shaped potential**: the set of all V(φ) consistent with observations and WIDE assumptions.

---

# 8. Relationship to ΛCDM

ΛCDM is a special case where:
- φ = constant,
- φ′ = 0,
- the potential equals a constant vacuum energy.

WIDE reduces smoothly to ΛCDM whenever the reconstructed w(a) = –1.

Thus, WIDE:
- includes ΛCDM as a subset,
- generalizes it when data indicate deviation,
- remains falsifiable if data collapse back to pure Λ behavior.

---

# 9. GR Consistency and Falsifiability

Because WIDE lives entirely within GR:
- expansion and growth are fundamentally linked,
- deviations from GR-consistent growth cannot be absorbed into V(φ),
- WIDE cannot mimic modified gravity.

This makes it highly falsifiable.

WIDE is rejected if:
- fσ₈(z) vs H(z) violates GR consistency,
- w(a) crosses below –1,
- strong data support freezing behavior (wₐ > 0),
- observational wake cannot be matched by a thawing field.

---

# 10. Observational Sensitivity

WIDE responds most strongly to:
- precise H(z) from BAO,
- distance ladder constraints,
- growth in the range 0.3 < z < 1.2 (the Growth Focus Window),
- weak-lensing shear amplitudes,
- CMB distance constraints.

These datasets sculpt the shape of the reconstructed potential.

Details appear in `/predictions/growth_focus_window.md`.

---

# 11. Future Fate Under WIDE

A thawing scalar field:
- never becomes phantom,
- does not create a Big Rip,
- typically leads to eternal acceleration,
- or converges to slow-roll if V′ → 0.

The long-term behavior is determined entirely by the reconstructed potential.

See `/predictions/future_fate.md`.

---

# 12. Summary

WIDE is a framework for reconstructing dark energy using:
- GR,
- scalar-field microphysics,
- thawing priors,
- and full observational wake inference.

It provides:
- theoretical clarity,
- falsifiability,
- observational grounding,
- and a direct pathway to identifying V(φ).

The rest of this repository contains the full derivations, predictions, and numerical roadmap needed to turn WIDE into a complete cosmological analysis toolkit.
