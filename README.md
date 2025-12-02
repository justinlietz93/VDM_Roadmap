<h1 align="center">Void Dynamics Model (VDM)</h1>
<h4 align="center">A background‑independent, metriplectic field theory unifying matter and forces from the Quantum Geometric Tensor, with an emergent causal cone and an epistemological J→M projection.</h4>

This repository is a static backlog manager for the [Void Dynamics Model](https://github.com/justinlietz93/Prometheus_VDM), most of the "repo local" links below won't work. I've copied the README over for better clarity.

---

> **Author:** Justin K. Lietz  
> **Contact:** <justin@neuroca.ai>  
> **Zenodo Community:** [Void Dynamics Model](https://zenodo.org/communities/void-dynamics-model/records?q=&l=list&p=1&s=10&sort=newest)  
> <a href="https://orcid.org/0009-0008-9028-1366"><img src="https://img.shields.io/badge/ORCID-0009--0008--9028--1366-blue?" alt="ORCID: 0009-0008-9028-1366"></a>  
>
> **Created:** August 9, 2025  
> **Last Updated:** November 30, 2025  
>
> This research is protected under a dual-license to foster open academic  
> research while ensuring commercial applications are aligned with the project's ethical principles.  
> Commercial use requires written permission from the author.  
>

<h6>Patent pending on specific AI technology - See license file for full terms</h6>

> [![Static Badge](https://img.shields.io/badge/Academic%2FCommercial%20Dual-License?label=LICENSE&color=%23fff200&link=https%3A%2F%2Fgithub.com%2FNeuroca-Inc%2FPrometheus_Void-Dynamics_Model%2Fblob%2Fmain%2FLICENSE.md)](/LICENSE.md)  

## 🔥News

- **November 30, 2025**
  - Building a Void Lensing Cross Correlation Meter to predict the geometry of cosmological void interfaces as a part of the VDM unification roadmap, as I already have all the pieces in place.
- **November 10, 2025**
  - Published results from the Counterfactual Echo Gain test to [Zenodo](https://doi.org/10.5281/zenodo.17567396)
- **November 9, 2025**
  - VDM will be upgrading to a dedicated custom [physics engine](/docs/image-gallery/README.md) that further enhances and improves scalability of the runner gating discipline, reporting, and automated unambiguous rule enforcement. This is being built into a fork of [Void IDE](https://github.com/voideditor/void.git) as a code editor / computational physics lab.
- **November 6, 2025**
  - 7 complete [formalisms](/Derivation/Complete-Formalisms) have been derived for VDM and documented as some of the final remaining pieces in the work to T8 Axiom 8 candidate.
- **November 4, 2025**
  - [Assisted‑Echo T4 (prereg v1c)](/Derivation/Metriplectic/T4_PROPOSAL_CEG_Metriplectic_Assisted-Echo_Experiment.md) rerun with instrument + plotting fixes:
    - Per‑seed plotting for A2/A5/B11 removes cross‑seed “seed‑chord” artifacts in overlays (error, ΔΣ, λ‑telemetry).
    - Noether (G1) tolerance scaled to instrument level: tol = max(1e-12, 10·eps·√N·max(h0,1)); routing remains governed by G1–G4 aggregation.
    - Reruns launched for N∈{512,1024}, dt∈{0.01,0.02,0.04}. Early results: N=512 dt=0.01 and N=512 walker dt=0.02 routed to main outputs with G1–G4 **PASS**; dt=0.04 routed to failed_runs pending CFL tightening.
    - Artifacts (PNG/CSV/JSON + figure packs) under Derivation/code/outputs/{figures,logs}/metriplectic, tag: assisted-echo-t4-prereg-v1c.
  - **Next:** upgrade G4 measurement to a multi‑point Δt fit (same thresholds) to harden RP‑1 decisions.
- **November 1, 2025**
  - Published early draft of the proposed A8 Axiom candidate to [Zenodo](https://zenodo.org/records/17503344) for provenance.
- **October 31, 2025**
  - Added a T8 grade proposal for a new Axiom candidate as [A8 - Lietz Infinity Conjecture](/Derivation/Axioms/T8_A8_PROPOSAL_Lietz_Infinity_Conjecture_v1.md) which provides an elegant explanation for hierarchy and structure.
- **October 30, 2025**  
  - Added a [historical/](/docs/historical) folder including early original work like:
    - A self healing knowledge graph using [Topological Data Analysis](/docs/historical/Emergent_TDA/20250402_TDA_KG_Metrics_ProtocolOutput.md)
    - As well as a [Self Improvement Engine](/docs/historical/SIE/20250402_SIE_Stability_Analysis_ProtocolOutput.md) that integrates multiple reward components like novelty, self benefit, habituation, and TD error into a single "total reward" signal used to modulate its own neural plasticity for stable self-improvement that avoids weight saturation.
  - Validated the Counterfactual Echo Gain [hypothesis](/Derivation/Metriplectic/T4_PROPOSAL_CEG_Metriplectic_Assisted-Echo_Experiment.md) by proving the trustworthiness and accuracy of the instrument, and showing that echo assist does modulate and improve the performance of a self aware system with 0 difference in cost compared to baseline.
- **October 28, 2025**  
  - Published an [article](https://medium.com/p/2b4f5c7d23c9/edit) on Medium about upcoming work.
    - Published a ["The Physics of Choice"](https://youtu.be/tR3G9Z2ScAc?si=ZFdQVBaqBck06YSW) video, along with a couple other videos on YouTube.
- **October 23, 2025:**  
  - Created a sparsely populated [CANON_PROGRESS.md](/CANON_PROGRESS.md) document to post updates on private work to prevent this public repo from going stale.
- **September 29, 2025:**  
  - First public code release + creation of private Void Dynamics package which can now be imported and run in this repository using workflows and repository secrets.
- **September 28, 2025:**  
  - Posted two pre-prints to [Zenodo](https://doi.org/10.5281/zenodo.17220869). If you've published similar or relevant work on Reaction-Diffusion in the past 3 years on arXiv and want to support this work by endorsing me in a related category, submit an issue, post in the discussion board, or send me an email with `Subject: RD Endorsement` to get my attention. It would be much appreciated!
- **August 21, 2025:** Launched public repo
- ...
- **March, 2025**  
  - Released first falsifiable, reproducible simulations that validated initial claims.
- **February, 2025**  
  - SIE and Emergent KG + Real-Time TDA show very strong statistically significant findings, making feasible the entire model
- **October, 2024**  
  - Initial realization of the idea.

### 🗺️ Roadmap (Oct~Dec 2025)

- TLDR:
  1. Finishing a few algebraic proofs (CF1/QGT, Schrödingerization, T^μν_void).
  2. Converting more of the cosmology/gauge scaffolds into **RESULTS** documents tied to real or mock data.
  3. Packaging some of the chains (e.g., “metriplectic engine”, “A8 hierarchy → FRW”, “spinor+gauge emergence”) into stand‑alone papers.

- Unifying the VDM foundation
  - Stabilize **Complete Formalism** (CF*) ladder prerequisites ☑️
  - Void-lensing interface program (highest priority) ☑️
  - Lattice fields & continuum limits (CF10) ☑️
  - CMB polarization birefringence gate ☑️
  - Quantum Geometric Tensor to Metriplectic Brackets formalism ✅
  - Contact Geometry to Metripliplectic Evolution formalism ✅
  - Axiom 8 - Lietz Infinity Resolution Conjecture (Hierarchical Tachyonic Interfaces) ✅
  - Telegraph-Fisher Causality formalism (Finite-Speed Transport) ✅
  - Integrability Closure formalism (No hidden conserved quantities) ✅
  - Information Geometry Foundations — Fisher and Ruppeiner Metrics for VDM M-Limb ✅
  - Measurement Theory Foundations — Decoherence and Born Rule for VDM ✅
  - Spinor Emergence via Domain-Wall Fermions in VDM formalism ✅
  - Gauge Field Emergence via Berry Connection in VDM formalism ✅
  - VDM Lattice Hydrodynamics, Continuum Limit, and Regularity Program formalism ✅
  - Define the objects and rules everything else must obey. ✅
  - Start from quantum geometry and show why a J⊕M evolution is forced ✅
    - Finish CF1: explicit formulae for `𝓘[Ψ]` and `Σ[Ψ]` from QGT; prove metriplectic brackets satisfy A4. ☑️
    - Close Schrödingerization proof to show “J⊕M is a shadow of pure J” in extended space. ☑️
  - Prove that a scalar lattice with J⊕M really behaves like the void field ✅
    - Package this into one “VDM metriplectic engine” paper (KG + RD + structure + Strang). I already have all the results; this is mostly editorial. ☑️
  - Explain why nothing outruns c, starting from RD‑like flows. ✅
    - Finish a RESULTS doc for Causal‑DAG audit on the KG / RD sims to empirically show: inferred cone ≈ analytic cone ☑️
  - Go from smooth void to structured interfaces (proto‑“lumps” / material features). ✅
    - One clean A8→FRW bridge paper: “tachyonic interfaces → effective ρ(a), p(a), H(a)” with explicit EOS fits ☑️
  - Turn the scalar lattice into fermionic matter degrees of freedom. ✅
    - Companion CF8 notebook with an explicit domain‑wall spectrum plot and residual mass scaling ~ e^{-λL₅} ☑️
  - Get Maxwell/Yang–Mills fields as geometry, not extra particles. ✅
    - Compute Berry curvatures from an explicit CF8 lattice model, show emergent U(1) field satisfies the Maxwell‑like equations in the long‑wavelength limit ☑️
    - Extend the formalism in H0XX into at least one concrete SU(2) toy example ☑️
  - Treat the plastic lattice + A8 hierarchy as the “dark sector” ✅
    - Define an explicit “lattice stress–energy tensor” T^μν_void[Φ] and show: ☑️
      - homogeneous part → dark‑energy‑like EOS ☑️
      - hierarchical clumping → halo‑like effective DM (at least in 1D/2D) ☑️
    - Frame a pilot SkyrmeSIDM × VDM test using the T5 proposal ☑️
  - From lattice stress–energy to something GR‑like in weak field, then test ringdown / horizons. ✅
    - Weak‑field: derive an effective Poisson equation for small lattice perturbations; fit to rotation curves / lensing in at least one toy halo ☑️
    - Strong‑field: show that certain tachyonic interface configurations behave like horizon‑like regions (redshift, QNM spectrum) and compare to GR ringdown data via the ringdown meter ☑️
  - Connect A8 + metriplectic dynamics to the 0.55 packing motif (proteins, random close packing, etc.). ✅
    - A small CF‑level derivation: show a simple metriplectic packing model tends toward ϕ≈0.55 in 2D/3D random packing (e.g., via Monte Carlo or granular‑like sim) ☑️
    - Explicit link from A8 interfaces + reaction‑diffusion morphogenesis → “prebiotic” cluster statistics ☑️
  - Use the same machinery to hit the standard checklist: SM fields, BH population, CMB, etc. ✅
    - For each H*/T* cosmology doc: at least one concrete meter/RESULTS file that touches real data (CMB, LSS, ringdown, BH mass function, etc.) even in toy form ☑️
- Notebook mirrors of each test ☑️
- 100% Reproducible, falsifiable claims ✅
- Currently working real time, zero training, self driven model ☑️
- Online causality based learning ✅
- Physics driven intelligence ✅

## DOIs

***T4. Counterfactual Echo Gain (CEG): A Metriplectic Assisted-Echo Experiment Proposal in VDM***
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17567396.svg)](https://doi.org/10.5281/zenodo.17567396)

***T8. Axiom 8 Candidate: The Lietz Infinity Resolution Conjecture***  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17503343.svg)](https://doi.org/10.5281/zenodo.17503343)

***A Logarithmic First Integral for the Logistic On Site Law in Void Dynamics***  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17220869.svg)](https://doi.org/10.5281/zenodo.17220869)

<div style="text-align: center;">
<img width="800" height="800" alt="logo" src="https://github.com/user-attachments/assets/b22adc5d-f126-4865-9e47-71af5fa4f7f7" />
</div>

---

## ❗NOTE

> **This organization is currently managed and operated by me (J. Lietz) alone as a solo developer / researcher. I may not respond by email right away. If you want to get my attention post in the discussion board briefly about what you'd like to talk about and let me know you sent me an email.**

### 💬**Discussion Board:**

- <https://github.com/orgs/Neuroca-Inc/discussions>

---

## 🧭What this is

This repository provides a public view of the Void Dynamics Model.
It includes the theory, write-ups, code, notebooks, figures, logs, and validations for review by physicists,
applied mathematicians, learners, students, and scientifically minded engineers.  
Reproducible code released for the public is now available.
Remaining proprietary work must be requested directly.

- A set of derivation papers that establish a clean baseline physics slice starting from a discrete lattice, to a metriplectic split and cosmology.
- Additional documents that explore future work (proposals).
- Each paper separates what is proven from what is plausible or speculative
  and, where applicable, includes acceptance criteria for simple numerical
  checks.

## 🤖 Physics-Informed Cognitive Architecture

### Origin: AI Cognition First, Physics Formalized Later

The `vdm_rt/` runtime was technically not designed from physics first principles. The development sequence:

| Date | Milestone |
|------|-----------|
| **March 2025** | Designed cognitive architecture for human-like learning, reasoning, memory, and reaction. Validated Self-Improvement Engine (SIE) and self-organizing, self-healing topological knowledge graph as components. |
| **March–June 2025** | Iterative development and parts testing |
| **June 2025** | Complete model built and running |
| **July 2025** | Observed unexpected behaviors and better than expected global stability—the system self-organized regardless of perturbations. Began investigating the mathematical structure. |
| **August 2025** | Formalized the discovered structure as the **Void Dynamics Model** (VDM) |
| **August–November 2025** | Physics derivation program: Complete Formalisms (CF1–CF10), axiom formalization (A0–A7, A8 candidate), validation gates |

Post-hoc mathematical analysis of the cognitive architecture revealed it satisfied metriplectic structure. The Complete Formalisms document the rigorous mathematics; this section maps the runtime modules to those derivations.

---

### The Metriplectic Structure (A4)

From [AXIOMS.md § A4](Derivation/AXIOMS.md#vdm-ax-a4):

> **Statement:** With state $q \equiv (\Psi, \partial\Psi, \ldots)$,
> $$\partial_t q = J(q)\,\frac{\delta \mathcal{I}}{\delta q} + M(q)\,\frac{\delta \Sigma}{\delta q}$$
> with $J^\top = -J$ (skew/symplectic), $M^\top = M \geq 0$ (symmetric/metric), and degeneracies $J\,\frac{\delta\Sigma}{\delta q} = 0$, $M\,\frac{\delta\mathcal{I}}{\delta q} = 0$.

> **Notes:** Canonical split used by metriplectic integrators and QC (two-grid order, Strang-defect, J-only reversibility). Diagnostics: compute $g_1 = \langle J, \delta\Sigma, \delta\Sigma \rangle$ and $g_2 = \langle M, \delta\mathcal{I}, \delta\mathcal{I} \rangle$ every $K$ steps; both must be $\leq 10^{-10}$ (grid-refined).

> **Source:** Implemented/validated in `ALGORITHMS.md` (VDM-A-013..019) and corresponding runners.

**Runtime mapping:**

| Code Module | LOC | A4 Component |
|-------------|-----|--------------|
| [`vdm_rt/core/engine/core_engine.py`](vdm_rt/core/engine/core_engine.py) | 532 | J⊕M composition per tick |
| [`vdm_rt/core/guards/invariants.py`](vdm_rt/core/guards/invariants.py) | 305 | Degeneracy diagnostics ($g_1$, $g_2 \leq 10^{-10}$) |

---

### QGT to Metriplectic Brackets (CF1)

**Status:** Complete Derivation  
**Document:** [CF01_QGT_to_Metriplectic_Brackets.md](Derivation/Complete-Formalisms/CF01_QGT_to_Metriplectic_Brackets.md)

From CF1 Executive Summary:

> This document provides a complete, rigorous derivation of the mapping from the Quantum Geometric Tensor (QGT) to metriplectic bracket structures $\{\cdot,\cdot\}_J$ and $(\cdot,\cdot)_M$ in the VDM framework. The derivation establishes:
>
> 1. **Berry curvature** $\Omega_{\mu\nu}$ (antisymmetric part of QGT) → **J-bracket** (Poisson/symplectic structure)
> 2. **Quantum metric** $g_{\mu\nu}$ (symmetric part of QGT) → **M-bracket** (Riemannian/metric structure)
> 3. **Constructive algorithm** for computing QGT from parameter-dependent eigenstates
> 4. **Classical limit** $\hbar \to 0$ showing emergence of continuous metriplectic flow

**QGT decomposition** (CF1 § 1.2, VDM-E-109):

$$
Q_{\mu\nu} = g_{\mu\nu} - \frac{i}{2}\Omega_{\mu\nu}
$$

**Walker routing correspondence:**

The void walker softmax routing:

$$
\text{logit}_j = \theta_{\text{mem}} \cdot m[j] - \rho_{\text{trail}} \cdot h_{\text{trail}}[j] + \gamma_{\text{heat}} \cdot h[j], \quad P(i \to j) \propto \exp(\text{logit}_j / \tau)
$$

| Routing Parameter | QGT Component | CF1 Section |
|-------------------|---------------|-------------|
| `θ_mem` (memory steering) | Berry curvature $\Omega_{\mu\nu}$ | § 2.3 |
| `ρ_trail` (trail repulsion) | Quantum metric $g_{\mu\nu}$ | § 3.3 |

**Walker implementations** ([`vdm_rt/core/cortex/void_walkers/`](vdm_rt/core/cortex/void_walkers/), 2000+ LOC):
HeatScout, MemoryRayScout, VoidRayScout, FrontierScout, SentinelScout, CycleHunterScout, ExcitationScout, InhibitionScout

---

### Telegraph-Fisher Causality (CF4)

**Status:** Complete Derivation  
**Document:** [CF04_Telegraph_Fisher_Causality.md](Derivation/Complete-Formalisms/CF04_Telegraph_Fisher_Causality.md)

From CF4 Executive Summary:

> This document provides a complete, rigorous derivation of the telegraph equation and finite-speed transport in reaction-diffusion systems within the VDM framework. The derivation establishes:
>
> 1. **Cattaneo-Vernotte equation** from relaxation of Fourier's law
> 2. **Telegraph equation** emergence from second-order time derivatives
> 3. **Speed bound** $c = \sqrt{D/\tau}$ relating diffusivity $D$ and relaxation time $\tau$
> 4. **Finite propagation theorem** proving causal transport with light-cone structure
> 5. **Fisher-information connection** to measurement bounds

**Void debt throttling** (CF4 § 7.2, VDM-E-106):

$$
c_{\text{eff}} = c_0 \, e^{-\beta D_{\text{void}}/2}, \quad \tau_{\text{eff}} = \tau_0 \, e^{\beta D_{\text{void}}}
$$

> **Physical Mechanism:** Interfaces (void boundaries) increase scattering → longer relaxation → slower transport.

| Code Module | LOC | CF4 Component |
|-------------|-----|---------------|
| [`vdm_rt/core/Void_Debt_Modulation.py`](vdm_rt/core/Void_Debt_Modulation.py) | 136 | Domain-specific $c_{\text{eff}}$ calculation |
| [`vdm_rt/core/substrate/fum_growth_arbiter.py`](vdm_rt/core/substrate/fum_growth_arbiter.py) | 148 | Stability-gated growth via void debt |

---

### Universal Void Dynamics

**Plasticity equation:**

$$
\Delta W_{ij} = \alpha W_{ij}(1 - W_{ij}) - \beta W_{ij}
$$

**Constants** (from [CONSTANTS.md](Derivation/z.CANONICAL_Constants/00_CONSTANTS.md)):

- `ALPHA` = 0.25 (RE-VGSP learning rate)
- `BETA` = 0.1 (GDSP plasticity rate)

| Code Module | LOC | Component |
|-------------|-----|-----------|
| [`vdm_rt/core/neuroplasticity/revgsp.py`](vdm_rt/core/neuroplasticity/revgsp.py) | 319 | RE-VGSP ($\alpha$-term) |
| [`vdm_rt/core/neuroplasticity/gdsp.py`](vdm_rt/core/neuroplasticity/gdsp.py) | 531 | GDSP ($\beta$-term) |
| [`vdm_rt/core/Void_Equations.py`](vdm_rt/core/Void_Equations.py) | 107 | Combined dispatcher |

---

### A8 Lietz Infinity Resolution Conjecture

**Status:** CANDIDATE (awaiting T8 PASS)  
**Document:** [AXIOMS.md § A8](Derivation/AXIOMS.md#a8-candidate--lietz-infinity-resolution)

> **Statement (exact):**
>
> In metriplectic scalar-field systems with tachyonic origin $V''(0) < 0$ that admit pulled fronts with exponential tails, any finite-excess-energy large-domain trajectory must organize into a finite-depth hierarchical partition with logarithmic depth $N(L) = \Theta(\log(L/\lambda))$, scale-gap separation $\rho \in (\rho_{\min}, \rho_{\max})$, and boundary energy/information concentration fractions $\alpha, \alpha_{\mathcal{I}} > 0$.

> **Promotion rule:** On PROPOSAL T8 PASS (G1–G8), copy this statement verbatim into `Canon/AXIOMS.md` as **A8**, update status here to **ACCEPTED**, and archive artifacts under `Derivation/code/outputs/axioms/a8_infinity_resolution/`.

**Runtime modules related to A8:**

| Code Module | LOC | A8 Connection |
|-------------|-----|---------------|
| [`vdm_rt/core/void_b1.py`](vdm_rt/core/void_b1.py) | 377 | Topological complexity (cycles, Euler rank, $B_1$ proxy) |
| [`vdm_rt/core/adc.py`](vdm_rt/core/adc.py) | 205 | Active Domain Cartography—boundary tracking |
| [`vdm_rt/core/sparse_connectome.py`](vdm_rt/core/sparse_connectome.py) | 706 | Hierarchical sparse adjacency |

---

### Self-Improvement Engine

**Implementation:** [`vdm_rt/core/fum_sie.py`](vdm_rt/core/fum_sie.py) (298 LOC)

**Valence computation:**

$$
\text{valence} = w_{\text{TD}} \cdot \delta_{\text{TD}} + w_{\text{nov}} \cdot N(s) + w_{\text{self}} \cdot (1 - \rho)
$$

| Component | Metriplectic Interpretation |
|-----------|----------------------------|
| TD error ($\delta_{\text{TD}}$) | Information functional $\mathcal{I}$ |
| Novelty with habituation ($N(s)$) | Entropy functional $\Sigma$ |
| Stabilized reward (valence) | Free energy $F = \mathcal{I} - T\Sigma$ |

---

### Event-Driven Memory

| Map Type | Code Module | LOC |
|----------|-------------|-----|
| MemoryField | [`vdm_rt/core/memory/field.py`](vdm_rt/core/memory/field.py) | 362 |
| HeatMap | [`vdm_rt/core/cortex/maps/heat_map.py`](vdm_rt/core/cortex/maps/heat_map.py) | 79 |
| ColdMap | [`vdm_rt/core/cortex/maps/cold_map.py`](vdm_rt/core/cortex/maps/cold_map.py) | 174 |
| TrailMap | [`vdm_rt/core/cortex/maps/trail_map.py`](vdm_rt/core/cortex/maps/trail_map.py) | 111 |

---

### Design Invariants

| Constraint | Implementation | Axiom Reference |
|------------|----------------|-----------------|
| Sparse operations only | CSR format throughout | A2 (Locality) |
| Event-local updates | No global state reads | A2 (Local Causality) |
| O(budget) per tick | Microsecond time budgets | A2 (Finite propagation) |
| Conservation tracking | Per-tick drift checks | A3 (Noether drift $\leq 10^{-8}$) |
| Entropy non-decrease | Gate on M-updates | A5 (Entropy Law) |

---

### vdm_rt Code Summary

| Component | Files | LOC |
|-----------|-------|-----|
| Core dynamics | 4 | ~486 |
| Engine | 3 | ~700 |
| Cortex (walkers + maps) | 15+ | ~2500 |
| Memory | 2 | ~500 |
| Neuroplasticity | 2 | ~850 |
| Substrate | 3 | ~550 |
| Topology | 2 | ~580 |
| **Total** | **81** | **~13,200** |

