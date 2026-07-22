# SRSM V0.78 — Nonlinear Substrate Comparison

## Candidates tested

Two minimal nonlinear branches selected by V0.77 were constructed and audited:

1. a simplicial/Regge geometric model;
2. a pure group-valued lattice connection.

## Candidate A — Simplicial/Regge geometry

A periodic triangulated two-dimensional torus was constructed from edge lengths. The Regge Einstein term is the sum of vertex deficits,

S_R ∝ Σ_v ε_v.

For a torus, the Euler characteristic is zero, so Gauss–Bonnet requires

Σ_v ε_v = 0.

The largest numerical residual across the tested lattices and nonlinear coordinate perturbations was

1.509903313490e-14.

This verifies that the simplicial construction is genuinely nonlinear and geometrically consistent in the toy model.

However, two-dimensional Einstein gravity is topological. Its Hessian cannot test a propagating four-dimensional graviton. Therefore this result does not prove that a 4D Regge realization has exactly two spin-2 modes or an exact finite-spacing diffeomorphism algebra.

**Verdict: HOLD. Geometrically viable, but the minimal test is insufficient for gravitational mode closure.**

## Candidate B — Pure group-valued connection

An SU(2) link field with Wilson plaquette action was constructed. Under

U_xy → G_x U_xy G_y⁻¹,

the action remained invariant.

Maximum relative action-change residual:

3.754745430638e-16.

This establishes exact finite-spacing nonlinear gauge invariance to machine precision.

But the linearized 3+1-dimensional pure SU(2) connection contains

3 gauge generators × 2 transverse polarizations = 6

massless spin-1 modes.

It does not contain a unique two-polarization spin-2 graviton, and it has no metric without an additional soldering field.

**Verdict: REJECT AS A STANDALONE GRAVITY MODEL.**

## Architecture selected

Neither minimal pure branch closes SRSM gravity.

The selected architecture is a hybrid:

- independent relational tetrad/frame variables;
- group-valued Lorentz-type connection links;
- discrete curvature from holonomies;
- torsion constraints;
- simplicity constraints reducing bivector data to metric/tetrad data;
- saturation field χ coupled to the tetrad and relational links.

This is the minimal candidate that can simultaneously supply:

1. nonlinear metric geometry;
2. exact finite-spacing internal gauge symmetry;
3. a path to two spin-2 polarizations;
4. local matter coupling through the tetrad;
5. curvature through connection holonomy.

## Scientific status

V0.78 does not yet prove that the hybrid succeeds. It eliminates the pure connection branch and shows why the Regge toy alone cannot settle the physical spectrum.

The architecture decision is now:

**Use a discrete tetrad–connection model with simplicity and torsion constraints.**

## V0.79 target

Construct the minimal hybrid action, for example schematically,

S = Σ_f Tr[B_f U_f] + constraints(B,e) + S_χ + S_matter,

or its Einstein–Cartan/Holst equivalent.

Then:

- derive exact local Lorentz transformations;
- identify lapse/shift or discrete analogues;
- construct the full constrained Hessian;
- count first- and second-class constraints;
- verify two physical tensor polarizations;
- test for torsion and scalar ghosts;
- derive the continuum Einstein–Hilbert coefficient;
- begin matching M0², C0, and C1.
