# Chapter 6 --- Curvature Instability and Identity Drift

## 6.1 Coherence Functional

Define the coherence functional

    𝓗
      = (α_Ψ / 2) (∇_μ Ψ)(∇^μ Ψ)
      + (α_Φ / 4) F_{μν} F^{μν}
      + (κ_Φ / 2) (D_s Φ_μ)(D_s Φ^μ)
      + α_Λ Λ_{μν} Λ^{μν}
      − 𝓡

where

    F_{μν} = ∇_μ Φ_ν − ∇_ν Φ_μ.

------------------------------------------------------------------------

## 6.2 Critical Points

Coherence-critical configurations satisfy

    ∇_μ 𝓗 = 0.

------------------------------------------------------------------------

## 6.3 Flow and Stability

Under gradient flow dynamics,

    D_s 𝓗 = − || ∇ 𝓗 ||² − η_Φ (D_s Φ_μ)(D_s Φ^μ),

This Lyapunov statement holds along the s-flow defined by the ecological field equations under the analytic assumptions stated in Section 5.7.

The norm \|\| ∇ 𝓗 \|\|² is taken with respect to the canonical L² inner
product on field variations:

    ⟨δX, δX⟩ = ∫_M dV (
        δΨ²
        + g^{μν} δΦ_μ δΦ_ν
        + g^{μρ} g^{νσ} δΛ_{μν} δΛ_{ρσ}
    ),

the gradient-flow statement represents a Lyapunov inequality for
ecological evolution in s.

    D_s 𝓗 ≤ 0.

Thus coherence decreases monotonically along stable trajectories in
ecological evolution time s. The monotonicity statement refers to the
s-flow defined by the coupled ecological field equations and does not
assume coincidence with any coordinate time on M.

------------------------------------------------------------------------

## 6.4 Stability Tensor

Define the stability tensor

    𝓢_{μν} = ∇_μ ∇_ν 𝓗.

At a critical point:

-   Positive-definite 𝓢\_{μν} → stable basin.
-   Mixed signature → saddle.
-   Unbounded negative mode → instability.

------------------------------------------------------------------------

## 6.5 Curvature Instability

Instability occurs when

    min(λ_i(𝓢)) → −∞.

------------------------------------------------------------------------

## 6.6 Basin Structure

Level sets:

    Σ_c = { x ∈ M | 𝓗(x) = c }.

Critical set:

    𝓒 = { ∇𝓗 = 0 }.

Partition:

    𝓑⁺ = stable basins,
    𝓑⁰ = metastable saddles,
    𝓑⁻ = instability wells.

------------------------------------------------------------------------

## 6.7 Identity Drift

Identity drift denotes exit from a stable coherence basin under
curvature instability in the coupled Φ--Ψ--Λ dynamics.

The coherence functional therefore defines the geometric stability
landscape of EFT--HCI.
