# WIDE Usage Guide  
*How to Navigate, Understand, and Extend the Wake-Inferred Dark Energy Framework*

This guide explains how to use the WIDE repository, how to navigate its structure, and how to interact with the theoretical and future numerical components of the framework.

WIDE is designed to be modular, transparent, and extensible. Whether you are a theorist, cosmologist, or computational scientist, this guide will help you understand where each component lives and how the reconstruction pipeline operates.

---

# 1. Repository Structure

WIDE is organized into clearly defined folders:

```
docs/          — High-level conceptual materials
derivations/   — Full mathematical derivations
predictions/   — Observable consequences
equations/     — Central equation library + renders
figures/       — Diagrams, conceptual plots
code/          — Future numerical tools and data loaders
```

Each section is independent and easy to expand.

---

# 2. How to Read the Documentation

### **Start here:**  
- `README.md` → broad overview  
- `docs/framework_overview.md` → quick conceptual summary  
- `docs/WIDE_theory.md` → full theoretical description  
- `docs/motivation.md` → why this approach is necessary  
- `docs/glossary.md` → definitions of terms and symbols

### **Then dive deeper:**  
- `derivations/` → mathematical derivation of every major equation  
- `predictions/` → concrete observational consequences of WIDE  
- `equations/equations.md` → full TeX library of equations used throughout the repository

This structure separates conceptual understanding from mathematical machinery, keeping everything readable and organized.

---

# 3. The WIDE Reconstruction Workflow

Even before numerical tools are added, WIDE specifies a clear reconstruction path:

```
1. Observational data → H(z), D(z), fσ₈(z)
2. Use continuity equation → reconstruct w(a)
3. Use scalar-field relations → compute φ’(a)
4. Integrate → obtain φ(a)
5. Compute dark-energy density → derive V(a)
6. Map V(a) to V(φ) → reconstruct potential
7. Apply thawing + GR constraints → remove unphysical models
```

Each step has a corresponding document in:
- `/derivations/`
- `/predictions/`
- `/equations/`

This ensures the entire process is transparent and replicable.

---

# 4. How the Future Numerical Pipeline Will Work

Although not yet implemented, the numerical tools will eventually live in:

```
code/reconstruction/
```

and may include:

### **4.1 Field reconstruction modules**
- `w_of_a_model.py` — w(a) parameterizations and reconstructions  
- `phi_of_a_solver.py` — scalar-field evolution integrator  
- `potential_reconstruction.py` — V(φ) reconstruction routines  

### **4.2 Data loaders**
Located under:

```
code/data_interface/
```

for datasets such as:
- DESI BAO/RSD  
- Pantheon+ supernovae  
- Planck/ACT CMB distance priors  
- Weak-lensing shear measurements  

### **4.3 Consistency tests**
Tools to verify:
- no phantom behavior,
- GR-consistent growth,
- thawing priors,
- smooth potentials.

### **4.4 Visualization tools**
Potential-space diagrams, growth curves, H(z) overlays, and field-trajectory plots.

When ready, this guide will be updated with full instructions.

---

# 5. How to Extend WIDE

WIDE is designed for modular extension.

### **5.1 Add alternative w(a) forms**  
You can introduce new representations of the dark-energy equation of state as long as they:
- respect w > –1,
- maintain thawing initial conditions,
- remain smooth functions.

### **5.2 Add new datasets**  
Growth, lensing, or BAO data can be integrated through additional loaders.

### **5.3 Add new potential-space visualizations**  
Plots can be placed under `/figures/`.

### **5.4 Explore modified assumptions**  
For scientific exploration, one could test:
- relaxing thawing conditions,
- allowing small curvature in GR,
- exploring minimal couplings.

These are strictly outside WIDE’s core definition, but can be studied as “WIDE extensions.”

---

# 6. How to Test or Falsify WIDE

A major goal of WIDE is clarity and scientific honesty.  
The theory is easy to falsify:

- **If w(a) < –1** → WIDE breaks (phantom forbidden).  
- **If GR expansion–growth consistency fails** → WIDE breaks.  
- **If growth measurements demand freezing behavior (wₐ > 0)** → WIDE breaks.  
- **If observational wake requires non-minimal coupling** → WIDE fails as defined.  

These failure modes are documented in:  
`predictions/falsifiability.md`.

---

# 7. Citation and Attribution

If referencing this framework in academic or public work, cite:

**WIDE — Wake-Inferred Dark Energy**  
Developed by Sam DeRenzis, with iterative analytical assistance from AI-based tools.

As the repo stabilizes, a formal BibTeX citation may be added.

---

# 8. Summary

This usage guide explains how to:
- navigate the WIDE repository,
- understand the theoretical structure,
- follow the reconstruction path,
- and prepare for numerical implementation.

WIDE is built to grow into a complete, modular, open-source dark-energy inference toolkit—powered by data, guided by physics, and constrained by the Universe’s observational wake.
