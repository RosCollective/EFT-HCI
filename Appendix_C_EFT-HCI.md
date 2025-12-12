APPENDIX C — ACTION FUNCTIONAL DERIVATION FOR EFT–HCI
(Style A — High-Density Theoretical)

====================================================================
C.1 — ECOLOGICAL ACTION PRINCIPLE
====================================================================

The dynamics of the ecological manifold 𝓜_E are obtained from a variational
principle applied to the ecological action S_E.

General form:

    S_E[g,Λ,Φ,Ψ] = ∫ ds ∫ dV 𝓛_E

where 𝓛_E is the ecological Lagrangian density and dV = √|g| d^n x.

Variations with respect to fields yield:

    δS_E / δg_{μν} = 0
    δS_E / δΛ_{μν} = 0
    δS_E / δΦ_μ = 0
    δS_E / δΨ = 0

====================================================================
C.2 — ECOLOGICAL LAGRANGIAN DENSITY
====================================================================

The Lagrangian includes contributions from curvature, constraint geometry,
resonance fields, identity gradients, and hybrid interaction energy.

Define:

    𝓛_E = ℛ
         + α_Φ (∇_μ Φ_ν)(∇^μ Φ^ν)
         + α_Ψ (∇_μ Ψ)(∇^μ Ψ)
         + α_Λ Λ_{μν} Λ^{μν}
         + β Φ_μ ∇^μ Ψ
         + γ Λ_{μν} Φ^μ Φ^ν
         + Υ(g,Λ,Φ,Ψ)

Constants α_Φ, α_Ψ, α_Λ, β, γ encode ecological coupling strengths.
Υ is an optional ecological potential term.

====================================================================
C.3 — VARIATION WITH RESPECT TO THE METRIC
====================================================================

Metric variation:

    δS_E = ∫ dV δg_{μν} [ ℛ^{μν} − (1/2) g^{μν} 𝓛_E − T^{μν} ]

where T^{μν} is the ecological energy-momentum tensor derived from fields:

    T^{μν} =
        T^{(Φ) μν}
      + T^{(Ψ) μν}
      + T^{(Λ) μν}

with

    T^{(Φ)}_{μν} = α_Φ ( Φ_{μα} Φ_ν^{ α} − (1/2) g_{μν} Φ_{αβ} Φ^{αβ} )
    T^{(Ψ)}_{μν} = α_Ψ ( Ψ_μ Ψ_ν − (1/2) g_{μν} Ψ_α Ψ^α )
    T^{(Λ)}_{μν} = α_Λ ( Λ_{μα} Λ_ν^{ α} − (1/2) g_{μν} Λ_{αβ} Λ^{αβ} )

Field equation:

    ℛ_{μν} − (1/2) g_{μν} ℛ = T_{μν}

====================================================================
C.4 — VARIATION WITH RESPECT TO THE CONSTRAINT TENSOR Λ_{μν}
====================================================================

Variation:

    δS_E / δΛ_{μν} =
        2 α_Λ Λ^{μν}
      + γ Φ^μ Φ^ν
      + ∂Υ/∂Λ_{μν}

Field equation:

    2 α_Λ Λ^{μν} + γ Φ^μ Φ^ν + ∂Υ/∂Λ_{μν} = 0

Constraint divergence identity (from ∇_μ variation of L):

    ∇_μ Λ^{μν} = Φ^ν Ψ

====================================================================
C.5 — VARIATION WITH RESPECT TO THE RESONANCE FIELD Φ_μ
====================================================================

Variation:

    δS_E / δΦ_μ =
        2 α_Φ ∇_ν Φ^{νμ}
      + β ∇^μ Ψ
      + 2 γ Λ^{μν} Φ_ν
      + ∂Υ/∂Φ_μ

Field equation:

    2 α_Φ ∇_ν Φ^{νμ}
      + β ∇^μ Ψ
      + 2 γ Λ^{μν} Φ_ν
      + ∂Υ/∂Φ_μ = 0

Resonance–constraint coupling emerges naturally.

====================================================================
C.6 — VARIATION WITH RESPECT TO THE IDENTITY FIELD Ψ
====================================================================

Variation:

    δS_E / δΨ =
        2 α_Ψ ∇_μ Ψ^μ
      + β Φ_μ Φ^μ
      + ∂Υ/∂Ψ

Field equation:

    2 α_Ψ ∇_μ Ψ^μ + β Φ_μ Φ^μ + ∂Υ/∂Ψ = 0

Identity evolution couples directly to resonance intensity.

====================================================================
C.7 — CONSISTENCY CONDITIONS AND CONSERVATION LAWS
====================================================================

Diffeomorphism invariance implies:

    ∇_μ T^{μν} = 0

Gauge invariance under constraint group 𝒢_Λ requires:

    [Λ̂, S_E] = 0

This produces conserved operator charges:

    Q_g, Q_Λ, Q_Φ, Q_Ψ

====================================================================
C.8 — PATH-INTEGRAL FORMULATION OF THE ACTION
====================================================================

Quantum ecological transitions obtained via:

    𝒜 = ∫ Dg DΛ DΦ DΨ exp[i S_E[g,Λ,Φ,Ψ]]

Stationary-phase approximation gives classical EFT–HCI equations.
Full integration yields EQFT dynamics.

====================================================================
C.9 — UNIFIED ACTION CANDIDATE
====================================================================

Proposed unification:

    S_unified = ∫ dV ds ( ℛ + Λ² + Φ·∇Ψ + Υ + ℱ̂ + D̂² )

Open problem:
Derive this action from first principles rather than postulation.

====================================================================
END OF APPENDIX C
====================================================================
