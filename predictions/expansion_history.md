# Expansion History Predictions in WIDE  
*How Thawing Scalar Fields Modify H(z) and Distance Measures*

The expansion history H(z) is one of the most important observational diagnostics of dark energy.  
WIDE (Wake-Inferred Dark Energy) predicts a specific family of H(z) behaviors arising from thawing scalar-field dynamics inside GR.

This document explains how WIDE constructs the predicted expansion, how it differs from ΛCDM, and which features are most sensitive to observational tests.

Referenced equations (E#) appear in `/equations/equations.md`.

---

# 1. Overview

The expansion rate is given by the Friedmann equation:

(E7) —  
```
H²(a) = (κ/3)[ρ_m(a) + ρ_r(a) + ρ_φ(a)]
```

In WIDE:
- ρ_m(a) and ρ_r(a) evolve normally,
- ρ_φ(a) evolves according to the reconstructed equation of state w(a).

Thus the predicted H(z) is fully determined by:
- the thawing conditions,
- the reconstructed w(a),
- and GR consistency.

---

# 2. Dark-Energy Contribution to H(z)

Given w(a), the scalar-field density evolves as:

(E20) —  
```
ρ_φ(a) = ρ_φ0 * exp[-3 ∫ (1 + w(a)) d ln a]
```

A thawing field has:
- **w(a) > –1**,  
- **slight increase toward the present**,  
- **suppressed kinetic energy**.

This generates a characteristic expansion pattern:
- indistinguishable from ΛCDM at high redshift,
- slightly faster expansion at low redshift (z < 1).

---

# 3. H(z) Features Unique to Thawing Models

Thawing models predict several generic signatures:

### **1. Early-time ΛCDM behavior (z > 2)**
Because w ≈ –1 and ρ_φ ≪ ρ_m:
- the field is frozen,
- H(z) matches ΛCDM to high precision.

### **2. Mild deviation at late times**
As φ begins to roll:
- w increases (e.g., –1 → –0.9),
- ρ_φ(a) evolves slightly faster,
- H(z) becomes marginally larger than in ΛCDM.

### **3. Smooth, monotonic transition**
No oscillations, no sharp features, no turning points.

### **4. No phantom evolution**
Because w > –1, WIDE forbids:
- super-acceleration,
- H(z) curvature associated with phantom energy,
- divergence toward a Big Rip.

---

# 4. Hubble Parameter Form

Using:

- Ω_m(a) ∝ a⁻³  
- Ω_r(a) ∝ a⁻⁴  
- Ω_φ(a) reconstructed from w(a)

the expansion is:

(E47) —  
```
H(a) = H₀ * sqrt[ Ω_m0 a⁻³ + Ω_r0 a⁻⁴ + Ω_φ(a) ]
```

This relation forms the basis of all WIDE predictions for distances and growth.

---

# 5. Distance Predictions

From H(z), WIDE predicts all standard cosmological distances:

## **Comoving distance**
(E48) —  
```
χ(z) = ∫₀ᶻ dz' / H(z')
```

## **Luminosity distance**
(E49) —  
```
D_L(z) = (1+z) χ(z)
```

## **Angular-diameter distance**
(E50) —  
```
D_A(z) = χ(z) / (1+z)
```

These are compared to:
- supernova magnitudes,
- BAO measurements,
- CMB acoustic scales.

---

# 6. Differences Between WIDE and ΛCDM

### **Low-redshift expansion**
WIDE predicts H(z) to be:
- slightly higher at 0 < z < 1,
- consistent with a less-negative w(a).

### **Distance modulations**
The mild increase in H(z) produces:
- slightly smaller luminosity distances,
- subtly modified BAO distances,
- shifts of order ~1–2%.

### **CMB-distance consistency**
Because thawing models deviate only at low z:
- CMB distance priors remain nearly unchanged,
- no violation of early-time physics occurs.

### **Growth–expansion interplay**
Slightly increased H(z) → slightly suppressed growth → testable.

This interplay is key to WIDE’s falsifiability.

---

# 7. Sensitivity Windows

WIDE’s expansion predictions differ most from ΛCDM in:

### **1. Redshift range 0.3 < z < 0.9**
- Where thawing models begin rolling.
- Where H(z) deviations reach measurable levels.

### **2. Redshifts probed by BAO and SNe**
Modern datasets strongly constrain:
- D_A(z),
- H(z),
- D_V(z),
- D_L(z).

### **3. Growth Focus Window**
The same region influences fσ₈(z); consistency requires both H(z) and growth to match GR.

---

# 8. Observable Signatures of Thawing H(z)

Thawing models produce distinctive features:

### **1. Slightly faster recent expansion**
ΔH/H ~ 1–3% at z ~ 0.5.

### **2. Mild deviation in D_L(z)**
Supernova Hubble diagram bends subtly relative to ΛCDM.

### **3. BAO dilation shifts**
The BAO scale is slightly modified, with δD ~ O(1%).

### **4. No dramatic curvature in H(z)**
The evolution is smooth, monotonic, and physically stable.

### **5. Tight correlation with growth**
Expansion changes are modest and coupled to growth suppression.

These signatures collectively form part of the **observational wake**.

---

# 9. Summary

WIDE predicts:
- ΛCDM-like expansion at high redshift,
- mild deviations at late times,
- small positive deviations in H(z),
- correlated changes in distances,
- and growth suppression linked to H(a).

Because WIDE’s predictions are fully determined by:
- GR,
- the reconstructed w(a),
- the thawing constraint,
- and scalar-field energy dynamics,

the expansion history is central to both model inference and falsifiability.
