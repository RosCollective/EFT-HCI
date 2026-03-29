# Appendix C — Action Functional Derivation

## C.1 Geometric Setup

Let (M, g) be an n-dimensional (pseudo-)Riemannian manifold with
Levi–Civita connection ∇ and volume form

    dV = √|g| dⁿx.

Let s denote the evolution parameter. The action functional is

    S_E[g, Λ, Φ, Ψ] = ∫ ds ∫_M dV 𝓛_E,

with boundary terms assumed negligible.

The parameter s denotes ecological evolution time: a real,
non-equilibrium process parameter governing the dynamical evolution of
field configurations on M. It is not assumed to coincide with any
coordinate time induced by the metric g_{μν}. Diffeomorphism invariance
applies on M for fixed s, while dissipation and stability evolution
occur along the s-flow.

Fields:

    Ψ        scalar field
    Φ_μ      physical (non-gauge) covector field
    Λ_{μν}   rank-2 constraint tensor

------------------------------------------------------------------------

## C.2 Vortex Structure of Φ

Define the antisymmetric field strength

    𝒦_{μν} = ∇_μ Φ_ν − ∇_ν Φ_μ.

Propagation in s is encoded by

    D_s Φ_μ = ∂_s Φ_μ.

Ecological evolution derivative.

In the present classical formulation we take

    D_s ≡ ∂_s

acting on component fields.

    D_s² ≡ ∂_s²

All covariant derivatives ∇_μ act on M at fixed s. More general extensions
with additional connection structure in s may be introduced in operator
or gauge formulations.

------------------------------------------------------------------------

## C.3 Lagrangian Density

The ecological Lagrangian density is

    𝓛_E
      = 𝓡
      − (α_Φ / 4) 𝒦_{μν} 𝒦^{μν}
      + (κ_Φ / 2) (D_s Φ_μ)(D_s Φ^μ)
      + (α_Ψ / 2) (∇_μ Ψ)(∇^μ Ψ)
      + α_Λ Λ_{μν} Λ^{μν}
      + β Φ_μ ∇^μ Ψ
      + γ Λ_{μν} Φ^μ Φ^ν
      + Υ
      + χ_ν (∇_μ Λ^{μν} − Φ^ν Ψ)

where:

    Υ denotes ecological irreversibility contributions as defined in Chapter 7.

------------------------------------------------------------------------

## C.4 Dissipation

Introduce the Rayleigh dissipation functional (Rayleigh dissipation, distinct from curvature 𝓡
𝓡)

    𝓡_d = (η_Φ / 2) (D_s Φ_μ)(D_s Φ^μ),

with η_Φ > 0.

The field equation follows from the Lagrange–d'Alembert principle:

    δS_E / δΦ_μ + ∂𝓡_d / ∂(D_s Φ_μ) = 0.

Thus dissipation contributes the friction term +η_Φ D_s Φ^μ to the Φ
equation.

------------------------------------------------------------------------

## C.5 Euler–Lagrange Equations

### (i) Metric Variation

Define the matter Lagrangian

    𝓛_m = 𝓛_E − 𝓡.

Then

    G_{μν} = 𝓡_{μν} − (1/2) g_{μν} 𝓡 = T_{μν},

with

    T_{μν} = − (2 / √|g|) δ(√|g| 𝓛_m) / δg^{μν}.

------------------------------------------------------------------------

### (ii) Λ Variation

    2 α_Λ Λ^{μν}
    + γ Φ^μ Φ^ν
    + ∂Υ / ∂Λ_{μν}
    − ∇^{(μ} χ^{ν)}
    = 0.

Constraint equation:

    ∇_μ Λ^{μν} = Φ^ν Ψ.

The constraint determines Λ_{μν} up to addition of any divergence-free
tensor K^{μν} satisfying

    ∇_μ K^{μν} = 0.

Consistency under ecological evolution requires that the source J^ν =
Φ^ν Ψ evolve compatibly with the coupled Euler–Lagrange system.

------------------------------------------------------------------------

### (iii) Φ Variation

    α_Φ ∇_ν 𝒦^{νμ}
    + κ_Φ D_s² Φ^μ
    + η_Φ D_s Φ^μ
    + 2γ Λ^{μν} Φ_ν
    + β ∇^μ Ψ
    − χ^μ Ψ
    + ∂Υ / ∂Φ_μ
    = 0.

------------------------------------------------------------------------

### (iv) Ψ Variation

    α_Ψ ∇_μ ∇^μ Ψ
    − β ∇_μ Φ^μ
    − χ_μ Φ^μ
    + ∂Υ / ∂Ψ
    = 0.

------------------------------------------------------------------------

## C.6 Conservation Statement

On-shell, diffeomorphism invariance implies

    ∇_μ T^{μν} = 0.

In the presence of dissipation, this relation defines a balance law for
ecological stress–energy under the coupled dynamics.

------------------------------------------------------------------------

## C.7 Interpretation — Action, Dynamics, and Interaction (Informal)

The action functional and its associated Euler–Lagrange equations admit
an interpretation at the level of interactional dynamics under conditions
of constrained linguistic coherence.

In this context:

- The action functional represents the total structural cost or coherence
  of interaction across both spatial configuration and ecological
  evolution.

- The Lagrangian density encodes contributions from curvature
  (structure), resonance (dynamic coupling), identity (scalar coherence),
  and constraint (structural enforcement), along with irreversibility and
  dissipation.

- The evolution parameter s corresponds to progression through
  interaction, rather than physical time, capturing the non-equilibrium
  unfolding of structure.

- The Euler–Lagrange equations correspond to the conditions under which
  interaction evolves while maintaining structural consistency across all
  coupled components.

- Dissipation corresponds to loss of structural coherence over
  interaction, requiring compensation through constraint or resonance to
  maintain stability.

Under this interpretation, the action formalism provides a unified
representation of how structure is generated, propagated, and constrained
within the ecological field.

These correspondences do not imply that underlying systems explicitly
optimize an action functional. Rather, they indicate that the action
formalism provides a consistent representation of the balance between
structure, coupling, and constraint observed in interaction.
