# Framework Overview of WIDE  
*A Quick Conceptual Summary*

WIDE (Wake-Inferred Dark Energy) is a cosmological framework designed to reconstruct the microphysical nature of dark energy directly from observational data. Instead of assuming a functional form for the dark-energy potential, WIDE uses the *observational wake* left by dark energy to constrain and reconstruct the underlying scalar-field dynamics within General Relativity (GR).

This overview provides a concise, intuitive guide to the structure and goals of WIDE.

---

# 1. What WIDE Is

WIDE is:

### ✔ A theoretical framework  
Built on GR + a minimally coupled, canonical scalar field.

### ✔ A reconstruction approach  
Dark-energy behavior is inferred from observational consequences, not assumed.

### ✔ A data-shaped model space  
WIDE produces *families* of allowed potentials \( V(\phi) \), not a single guess.

### ✔ A falsifiable theory  
WIDE breaks if:
- w(a) < –1 (phantom behavior),  
- GR consistency between expansion and growth fails,  
- or data require freezing-type evolution.

---

# 2. Why "Wake-Inferred"?

Dark energy leaves a pattern of signatures across multiple observational probes:
- expansion history H(z),
- distance-redshift relations,
- structure growth (fσ₈),
- weak-lensing shear,
- CMB constraints,
- and the interplay of these under GR.

These signatures collectively form the **wake** — the cosmological imprint of dark energy.

WIDE reconstructs:
```
wake → w(a) → φ(a) → V(φ)
```

This is the opposite of "assume a potential" models.

---

# 3. Physical Foundations of WIDE

WIDE is built on four principles:

### **1. General Relativity holds.**
No modified gravity or exotic field couplings.

### **2. Dark energy is a canonical scalar field.**
Minimal kinetic term, smooth potential.

### **3. Dynamics are thawing.**
The field was frozen early and is slowly rolling now.

### **4. No phantom behavior.**
WIDE enforces w > –1 at all times.

These assumptions ensure physical stability, observational consistency, and smooth behavior.

---

# 4. The Core Pipeline

WIDE’s reconstruction method consists of four steps:

## **Step 1 — Extract H(z), D(z), and fσ₈(z)**  
From observations such as:
- BAO,
- SNe Ia,
- Weak lensing,
- DESI and Euclid surveys,
- CMB distance priors.

## **Step 2 — Infer w(a)**  
Using standard GR equations and energy conservation.

## **Step 3 — Reconstruct φ(a)**  
The equation of state gives the scalar-field kinetic fraction and displacement.

## **Step 4 — Reconstruct V(φ)**  
Energy density and φ(a) are combined to produce the potential.

This produces a *data-shaped* region in φ–V space representing all allowed microphysical models.

---

# 5. The Growth–Expansion Consistency Test

A special strength of WIDE is its ability to test GR rigorously.

If GR is true:
- the expansion rate H(z),
- matter density evolution,
- and structure growth fσ₈(z)

must satisfy a specific differential relation.

WIDE places this test at the center of its inference.  
If growth significantly deviates from what GR predicts given H(z), WIDE cannot explain the data within its assumptions.

This gives WIDE strong **falsifiability**.

---

# 6. Comparison to ΛCDM and Other Approaches

### **ΛCDM**
- special case of WIDE where φ is constant,
- gives w = –1 exactly,
- corresponds to V(φ) = constant.

### **Phenomenological w(z)**  
- describes expansion but lacks microphysical meaning,
- cannot reconstruct φ or V(φ).

### **Assumed potentials**  
- restrictive,
- may miss true behavior,
- impose theoretical bias.

### **WIDE**
- generalizes ΛCDM,
- provides physical meaning,
- remains flexible without assuming V(φ),
- and is controlled entirely by data.

---

# 7. Future Data and the Growth Focus Window

WIDE is especially sensitive to structure growth measurements in:
- 0.3 < z < 1.2

This is the redshift range where thawing models deviate most noticeably from ΛCDM.  
Improved growth measurements here strongly constrain:
- kinetic fraction,
- potential slope,
- allowed w(a) trajectories.

See `/predictions/growth_focus_window.md`.

---

# 8. What WIDE Will Become

As the framework develops, this repository will include:
- numerical tools to perform reconstruction,
- scripts to load DESI/SNe/lensing/CMB data,
- field-evolution solvers,
- potential-space visualizations,
- and consistency tests.

The goal is a full, modular, open-source **dark-energy inference toolkit**.

---

# 9. Summary

WIDE is a new approach to dark energy based on:
- GR,
- scalar-field microphysics,
- thawing dynamics,
- and observational wake inference.

It reconstructs the potential directly from the Universe’s behavior instead of imposing theoretical assumptions.

WIDE stands as a physically clean, observationally grounded, and scientifically falsifiable framework for understanding cosmic acceleration.
