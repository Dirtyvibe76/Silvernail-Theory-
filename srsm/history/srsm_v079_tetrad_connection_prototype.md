# SRSM V0.79 — Constrained Tetrad–Connection Prototype

## Architecture constructed

The V0.78 hybrid was implemented at quadratic order with:

- an independent tetrad/frame;
- an independent Lorentz connection;
- a simplicity reduction;
- an algebraic torsion sector;
- the saturation mode χ;
- canonical Gauss, spatial-diffeomorphism, and Hamiltonian constraints.

This is a first-order gravitational prototype. It is not yet a complete nonlinear finite-lattice theory.

## Canonical degree count

The spatial connection and densitized triad contribute

9 + 9 = 18

phase-space dimensions per spatial point.

There are seven first-class constraints:

- 3 Gauss constraints;
- 3 spatial-diffeomorphism constraints;
- 1 Hamiltonian constraint.

Therefore

N_physical,phase = 18 - 2(7) = 4,

and

N_physical,configuration = 4/2 = 2.

The constrained canonical architecture therefore has the correct graviton degree count.

## Simplicity sector

A generic bivector field has

6 × 6 = 36

components.

A tetrad has 16 components, and the local Lorentz quotient leaves 10 metric components. The simplicity constraints remove the surplus bivector directions and restrict the curvature-coupling variable to the tetrad-generated sector.

This is a dimensional consistency result, not yet a nonlinear proof that every discrete solution is nondegenerate and geometric.

## Torsion elimination

The quadratic first-order Hessian was written in block form,

H =
[[K_hh, K_hω],
 [K_ωh, K_ωω]].

The connection/torsion block was positive and invertible. Its smallest tested eigenvalue was

2.013493178681e+00.

Eliminating the connection gives the Schur complement

K_eff =
K_hh - K_hω K_ωω⁻¹ K_ωh.

The maximum relative difference between this effective metric Hessian and the V0.76 spin-2 kernel was

5.779038089253e-17.

Thus the first-order tetrad–connection prototype reproduces the previously verified quadratic metric gauge sector after torsion is eliminated.

## Reduced physical spectrum

The reduced spectrum contains exactly two massless tensor branches:

- TT_plus;
- TT_cross.

The modeled nonmetric sectors are gapped:

M_torsion = 2.4,
M_simplicity = 2.8,
M_χ = 2.1.

All modeled physical residues are positive.

## Result

V0.79 achieves a conditional quadratic hybrid closure:

1. the tetrad supplies metric geometry;
2. the connection supplies first-order curvature variables;
3. simplicity removes surplus bivector directions;
4. torsion is auxiliary at quadratic order;
5. eliminating torsion reproduces the V0.76 metric kernel;
6. canonical first-class counting leaves two physical gravitational modes;
7. extra modeled sectors are gapped.

## Critical limitation

The following have not been established:

- exact nonlinear constraint closure at finite spacing;
- preservation of all constraints under discrete time evolution;
- nonlinear absence of an additional scalar;
- uniqueness of the simplicity sector;
- a microscopic derivation of the selected mass gaps;
- numerical M0², C0, C1, G_eff, or Λ_eff.

The numerical gaps used here are prototype parameters, not predictions.

## V0.80 target

Construct a nonlinear discrete Einstein–Cartan or Holst cell action with explicit tetrad and group-valued connection variables. Then:

- derive its exact local Lorentz symmetry;
- derive all primary and secondary constraints;
- evolve one discrete time step;
- test constraint preservation;
- calculate the nonlinear constraint-bracket matrix;
- count first- and second-class constraints;
- test for an extra scalar;
- expand about the homogeneous vacuum and recover this V0.79 Hessian.
