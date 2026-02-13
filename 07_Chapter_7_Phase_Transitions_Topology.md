
# Chapter 7 — Ecological Information & Invariance Currents

## 7.1 Ecological Information Tensor

Define the ecological information tensor

    𝓘_{μν}
      = ∇_μ Ψ ∇_ν Ψ
      + (1/2) F_{μα} F_{ν}{}^{α}
      + (D_s Φ_μ)(D_s Φ_ν)
      + Λ_{μρ} Λ_{ν}{}^{ρ}.

The associated information scalar is

    𝓘
      = ||∇Ψ||²
      + (1/2)||F||²
      + ||D_s Φ||²
      + ||Λ||².

The information gradient is

    𝓖_μ = ∇^ν 𝓘_{μν}.

At coherence fixed points (𝓗 = 0), the system satisfies

    𝓘 = 𝓡.

---

## 7.2 Information Currents

Define the information current

    J_ν = ∇^μ 𝓘_{μν}.

This decomposes into sector contributions

    J_ν = J_ν^{(Ψ)} + J_ν^{(Φ)} + J_ν^{(Λ)}.

On-shell conservation requires

    ∇^ν J_ν = 0.

The scalar information satisfies

    ∇^μ ∇_μ 𝓘 = 0.

Collapse occurs when

    ||J|| → ∞.

---

## 7.3 Information Asymmetry

Define the asymmetry tensor

    𝓐_{μν} = ∇_μ J_ν − ∇_ν J_μ.

The irreversibility scalar is

    𝓐 = (1/2) 𝓐_{μν} 𝓐^{μν}.

Curvature coupling yields

    𝓐_{μν} = R_{μνα}{}^{β} 𝓘_{β}{}^{α} + …

Collapse corresponds to

    𝓐 → ∞.

---

## 7.4 Invariance & Noether Currents

Identity current:

    𝓙^{(Ψ)}_μ = 𝓘_{μν} ∇^ν Ψ.

Resonance current:

    𝓙^{(Φ)}_μ = F_{μν} Φ^ν.

Constraint current:

    𝓙^{(Λ)}_μ = Λ_{μν} ∇_ρ Λ^{ρν}.

Metric deformation current:

    𝓙^{(g)}_μ.

The total invariance current is

    𝓙_μ = Σ 𝓙^{(*)}_μ,

with conservation condition

    ∇^μ 𝓙_μ = 0.

---

## 7.5 Entanglement & Interference

Define the entanglement tensor

    𝓔_{μν} = (∂𝓘_{μν}/∂𝔈) · δ𝔈.

The interference tensor is

    𝓧_{μν} = 𝓘_{μα} 𝓘_{ν}{}^{α} − (1/n) 𝓘² g_{μν}.

The entanglement scalar is

    𝓔 = 𝓘_{μν} 𝓘^{μν}.

Collapse occurs when

    𝓔 → ∞.

---

## 7.6 Order Measures

Information curvature:

    𝓒 = 𝓡 − 𝓘.

Coherence ratio:

    Ξ = 𝓡 / 𝓘.

Irreversibility index:

    Υ = 𝓐 / 𝓘.

Order parameter:

    𝓞 = 𝓡 / √𝓔.

The ecological information phase space is therefore

    (𝓘, 𝓔, 𝓒, Υ, 𝓞).
