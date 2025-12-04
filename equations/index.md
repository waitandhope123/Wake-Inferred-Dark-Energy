# WIDE Equations Index  
*A Quick Navigation Guide to the Mathematical Backbone of WIDE*

This directory contains all equations used throughout the WIDE (Wake-Inferred Dark Energy) framework.  
It serves as a central reference for developers, theorists, and readers who want immediate access to the mathematical structure underlying the theory.

---

# 1. File Overview

### **`equations.md`**  
The **master equation library**.  
Contains every numbered equation (E1–E61), organized by topic:

- FLRW geometry  
- Friedmann equations  
- scalar-field dynamics  
- thawing constraints  
- w(a) reconstruction  
- ρφ(a) evolution  
- φ(a) and V(φ) reconstruction  
- distances  
- growth and fσ₈  
- GR consistency  
- Growth Focus Window  
- future fate  
- forbidden behaviors  

This is the primary file most contributors will use.

---

# 2. Purpose of the Equations Directory

This folder exists to:

- centralize all mathematical expressions,  
- give contributors a stable equation numbering scheme (E1, E2, …),  
- avoid cluttering the main theoretical documents,  
- enable researchers to look up formulas quickly,  
- ensure cross-references remain consistent across the repository.

All derivations and prediction documents refer to equations by their labels (E#).

---

# 3. How the Equations Are Organized

The equations follow a logical order:

1. **Background cosmology**  
2. **Scalar-field microphysics**  
3. **Thawing conditions**  
4. **Dark-energy evolution**  
5. **Potential reconstruction**  
6. **Growth equations**  
7. **GR consistency relations**  
8. **Observational windows**  
9. **Future fate predictions**

This mirrors the workflow:

```
geometry → w(a) → ρφ(a) → φ(a) → V(φ) → H(a) → fσ₈(a)
```

---

# 4. Extending This Directory

Future additions may include:

- numerical-solver formulas,  
- perturbation-equation expansions,  
- alternative reconstruction parameterizations,  
- stability conditions for extended potentials,  
- or optional appendices for contributors.

All new equation sets should follow the established numbering scheme and reference style.

---

# 5. Summary

The `/equations/` folder is:

- the backbone of the WIDE mathematical framework,  
- the central cross-reference point for the entire repository,  
- and the location of the authoritative equation list used throughout the theory.

If you are modifying or extending WIDE, start with `equations.md`.
