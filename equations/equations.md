# WIDE Master Equation Library  
*All Equations Used Across the Wake-Inferred Dark Energy Framework*

This file provides a complete, centralized reference for every equation used throughout the WIDE framework. They are grouped by category for clarity.

All equations are written in GitHub-compatible math blocks.

---

# 1. Geometry and Background Cosmology

## (E1) FLRW Metric
```math
ds^2 = -dt^2 + a^2(t)\left[ \frac{dr^2}{1-k r^2} + r^2 d\Omega^2 \right]
```

## (E2) Hubble Parameter
```math
H(t) = \frac{\dot{a}}{a}
```

## (E3) Energy–Momentum Tensor of a Perfect Fluid
```math
T_{\mu\nu} = (\rho + p)u_\mu u_\nu + p g_{\mu\nu}
```

## (E4) Equation-of-State Parameter
```math
w \equiv \frac{p}{\rho}
```

---

# 2. Friedmann Equations

## (E5) First Friedmann Equation
```math
H^2 = \frac{\kappa}{3}\rho - \frac{k}{a^2}
```

In WIDE we assume a flat universe:
```math
k = 0
```

Thus:

## (E7) Flat-Universe Friedmann Equation
```math
H^2(a) = \frac{\kappa}{3}\left[ \rho_m(a) + \rho_r(a) + \rho_\phi(a) \right]
```

---

# 3. Scalar-Field Dynamics

A canonical scalar field has Lagrangian:

## (E8) Scalar-Field Lagrangian
```math
\mathcal{L}_\phi = -\frac{1}{2}\partial_\mu\phi \, \partial^\mu\phi - V(\phi)
```

From this:

## (E9) Energy Density
```math
\rho_\phi = \frac{1}{2}\dot{\phi}^2 + V(\phi)
```

## (E10) Pressure
```math
p_\phi = \frac{1}{2}\dot{\phi}^2 - V(\phi)
```

## (E11) Kinetic Energy
```math
K \equiv \frac{1}{2}\dot{\phi}^2
```

## (E12) Equation of State
```math
w_\phi = \frac{K - V}{K + V}
```

## (E10) Klein–Gordon Equation
```math
\ddot{\phi} + 3H\dot{\phi} + \frac{dV}{d\phi} = 0
```

---

# 4. Field Derivative with Respect to Scale Factor

Define the derivative with respect to ln(a):

## (E13)
```math
\phi' \equiv \frac{d\phi}{d\ln a} = \frac{\dot{\phi}}{H}
```

Using (E11):

## (E14)
```math
\phi'^2 = 3 M_{\rm pl}^2 \, \Omega_\phi(a) \, (1 + w(a))
```

---

# 5. Potential and Kinetic Decomposition

## (E15) Potential from w and ρ
```math
V(a) = \frac{1}{2}\rho_\phi(a)\,[1 - w(a)]
```

## (E16) Parametric Reconstruction
```math
V(\phi) = V(a(\phi))
```

---

# 6. Field Excursion

## (E22) Field Excursion
```math
\Delta\phi = \left| \int \phi'(a)\, d\ln a \right|
```

In thawing models:
```math
\Delta\phi \ll M_{\rm pl}
```

---

# 7. Thawing Conditions

## (E23) Frozen Condition (Early Times)
```math
3H\dot{\phi} \gg V'(\phi)
\quad \Rightarrow \quad
\dot{\phi} \approx 0
```

## (E24) Early-Time Equation of State
```math
w \approx -1
```

## (E25) Thaw Condition
```math
3H\dot{\phi} \sim V'(\phi)
```

## (E26) Smoothness Criterion
```math
\left|\frac{V''}{V}\right| \ll 1
```

## (E27) Small Slope
```math
\left|\frac{V'}{V}\right| < \mathcal{O}(1)/M_{\rm pl}
```

## (E28) Gentle Curvature
```math
|V''| \ll H^2
```

## (E29) Thawing Evolution
```math
\frac{dw}{d\ln a} > 0
```

## (E30) Non-Phantom Condition
```math
w(a) > -1
```

---

# 8. Dark-Energy Evolution

## (E19) Continuity Equation
```math
\frac{d\ln \rho_\phi}{d\ln a} = -3(1 + w(a))
```

## (E20) Dark-Energy Density Evolution
```math
\rho_\phi(a) = \rho_{\phi0}\exp\left[-3\int (1 + w(a)) d\ln a\right]
```

## (E35) Solve for w(a) from ρ
```math
1 + w(a) = -\frac{1}{3}\frac{d\ln \rho_\phi}{d\ln a}
```

## (E36)
```math
\rho_\phi(a) = \frac{3}{\kappa}H^2(a) - \rho_m(a) - \rho_r(a)
```

---

# 9. Distances

## (E48) Comoving Distance
```math
\chi(z) = \int_0^z \frac{dz'}{H(z')}
```

## (E49) Luminosity Distance
```math
D_L(z) = (1+z)\chi(z)
```

## (E50) Angular-Diameter Distance
```math
D_A(z) = \frac{\chi(z)}{1+z}
```

---

# 10. Growth of Structure

## (E39) Growth Equation
```math
\delta'' + \left[ 2 + \frac{\dot{H}}{H^2} \right]\delta' - \frac{3}{2}\Omega_m(a)\delta = 0
```

## (E40) Growth Rate
```math
f(a) = \frac{d\ln\delta}{d\ln a}
```

## (E41) Observable Combination
```math
f\sigma_8(a) = f(a)\,\sigma_8(a)
```

---

# 11. Growth–Expansion Consistency

Convert growth equation to f form:

## (E42)
```math
f' + f^2 + \left[ 2 + \frac{\dot H}{H^2} \right] f = \frac{3}{2}\Omega_m(a)
```

Define the consistency function:

## (E43)
```math
G_{\rm GR}(a)
\equiv
f' + f^2 + \left[ 2 + \frac{\dot H}{H^2} \right] f - \frac{3}{2}\Omega_m(a)
```

In GR:

## (E44)
```math
G_{\rm GR}(a) = 0
```

---

# 12. Growth Focus Window Equations

## (E52) Growth Focus Window
```math
0.3 < z < 1.2
```

## (E53) Sensitivity Function
```math
S(z) \equiv \frac{\partial f\sigma_8(z)}{\partial w(z)}
```

## (E54) Sensitivity Peak
```math
S(z) \text{ peaks within the GFW}
```

## (E55) Typical Suppression
```math
\Delta f\sigma_8(z) \approx -2\% \text{ to } -6\%
```

## (E56) Peak Location
```math
z_{\rm peak} \approx 0.6 - 0.8
```

---

# 13. Future Fate

## (E57) Asymptotic de Sitter Behavior
```math
\dot{\phi} \to 0, 
\quad w(a)\to -1,
\quad V(\phi)\to \text{constant}
```

## (E58) Slow-Roll Asymptote
```math
w(a) \to w_\infty > -1
```

## (E59) Power-Law Potential
```math
V(\phi) \sim \phi^{-n}
```

## (E60) Power-Law Expansion
```math
a(t) \sim t^p , \quad p > 1
```

## (E61) Phantom Big Rip (Forbidden)
```math
a(t) \to \infty \text{ in finite time}
```

---

# 14. Summary

This document contains the full set of equations used by the WIDE framework, including:

- scalar-field dynamics  
- Friedmann relations  
- w(a) reconstruction  
- potential reconstruction  
- growth equations  
- GR consistency conditions  
- distance relations  
- thawing constraints  
- future evolution formulas  

It serves as the master reference for all theory, predictions, and derivations in the WIDE repository.
