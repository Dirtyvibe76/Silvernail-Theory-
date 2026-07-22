# SRSM V0.77 — Nonlinear Gauge-Closure Audit

## Candidate tested

The direct nonlinear continuation of V0.76 was defined by the lattice Lie derivative

δ_ξ g_ij = ξ^a D_a g_ij + g_aj D_iξ^a + g_ia D_jξ^a,

using a local central-difference derivative D.

Exact closure would require

[δ_ξ,δ_η]g = δ_[ξ,η]g

at every finite lattice spacing.

## Results

At N=128, the relative gauge-algebra closure residual was

1.562371876410e-03.

The residual converged toward zero with estimated order

p = 1.991552,

showing that the continuum algebra is recovered asymptotically but is not exact microscopically.

The independently measured discrete Leibniz-rule residual was

2.487178627366e-03,

with convergence order

p = 2.007172.

Thus the finite-difference derivative does not satisfy the product rule exactly. Since nonlinear diffeomorphism closure uses that rule, finite-spacing remainder terms survive.

## Verdict

The naive local finite-difference completion is rejected as an exact nonlinear microscopic realization.

This does not invalidate V0.76. Its quadratic identity K·G=0 contains no nonlinear products and remains valid as the infrared linearized gauge structure.

## Consequences

Not yet established:

- exact nonlinear Bianchi identities;
- closure of Hamiltonian and momentum constraints;
- nonlinear absence of an extra scalar;
- universal nonlinear matter coupling;
- numerical matching of M0², C0, C1, G_eff, or Λ_eff.

## Selected V0.78 candidates

1. Regge/simplicial relational geometry using edge lengths, simplex volumes, and deficit angles.
2. Group-valued relational links using a discrete connection and holonomy curvature.

Both must be constructed and compared before selecting the nonlinear microscopic substrate.
