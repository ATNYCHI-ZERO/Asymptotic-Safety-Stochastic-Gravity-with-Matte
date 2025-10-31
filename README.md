# Asymptotic-Safety-Stochastic-Gravity-with-MatterFRG + Einstein–Langevin from CTP, Geodesic Tomography for Reconstruction

Abstract

We construct a semiclassical stochastic gravity framework coupled to QCD-like matter and analyze its renormalization using the functional renormalization group (FRG). Starting from a closed-time-path (CTP) influence functional, metric fluctuations 
ℎ
𝜇
𝜈
h
μν
	​

 obey an Einstein–Langevin equation with a covariant Gaussian noise 
𝜉
𝜇
𝜈
ξ
μν
	​

 whose covariance equals the stress-tensor fluctuation kernel. We then define a diffeomorphism-invariant effective average action 
Γ
𝑘
[
𝑔
,
Ψ
,
𝑐
ˉ
,
𝑐
]
Γ
k
	​

[g,Ψ,
c
ˉ
,c] with background-field FRG and regulator 
𝑅
𝑘
R
k
	​

. We study truncations including 
{
Λ
𝑘
,
𝐺
𝑘
,
𝑅
2
,
𝑅
𝜇
𝜈
𝑅
𝜇
𝜈
}
{Λ
k
	​

,G
k
	​

,R
2
,R
μν
	​

R
μν
} and minimally coupled SU(3) Yang–Mills + fermions. UV completeness is identified with a non-Gaussian fixed point and finite relevant directions (asymptotic safety) while preserving Slavnov–Taylor and diffeomorphism Ward–Takahashi/Nielsen identities. Metric reconstruction from correlation data uses the geodesic X-ray transform; linear Radon inversion is justified only in the weak-field limit on simple manifolds. Computability follows from a coupled scheme: (i) stochastic PDE integrator for the Einstein–Langevin dynamics with covariant noise drawn from the CTP kernel, (ii) FRG flow integration for 
Γ
𝑘
Γ
k
	​

 with ghost sector, and (iii) lattice or FRG matter subsector for SU(3). This program yields a falsifiable path to a stochastic, diffeo-consistent, potentially UV-complete semiclassical geometry. Claims of “proof” require: demonstration of a UV fixed point with controlled truncation error, intact identities under flow, and a consistent noise-quantum correspondence.

Core model (precise, minimal)

Fields: 
𝑔
𝜇
𝜈
,
  
𝐴
𝜇
𝑎
,
  
𝜓
,
𝜓
ˉ
,
  
𝑐
,
𝑐
ˉ
g
μν
	​

,A
μ
a
	​

,ψ,
ψ
ˉ
	​

,c,
c
ˉ
.
Bare action:

𝑆
=
∫
𝑑
4
𝑥
−
𝑔
[
1
16
𝜋
𝐺
(
−
𝑅
+
2
Λ
)
+
𝛼
𝑅
2
+
𝛽
𝑅
𝜇
𝜈
𝑅
𝜇
𝜈
+
1
4
𝐹
𝜇
𝜈
𝑎
𝐹
𝑎
 
𝜇
𝜈
+
𝜓
ˉ
(
𝑖
\slashed
𝐷
−
𝑚
)
𝜓
]
+
𝑆
gf
+
𝑆
gh
.
S=∫d
4
x
−g
	​

[
16πG
1
	​

(−R+2Λ)+αR
2
+βR
μν
	​

R
μν
+
4
1
	​

F
μν
a
	​

F
aμν
+
ψ
ˉ
	​

(i\slashedD−m)ψ]+S
gf
	​

+S
gh
	​

.

CTP-induced stochastic dynamics:

𝐺
𝜇
𝜈
[
𝑔
]
=
8
𝜋
𝐺
 
(
⟨
𝑇
𝜇
𝜈
⟩
𝑔
+
𝜉
𝜇
𝜈
)
,
⟨
𝜉
𝜇
𝜈
(
𝑥
)
𝜉
𝜌
𝜎
(
𝑦
)
⟩
=
𝑁
𝜇
𝜈
𝜌
𝜎
[
𝑔
]
(
𝑥
,
𝑦
)
G
μν
	​

[g]=8πG(⟨T
μν
	​

⟩
g
	​

+ξ
μν
	​

),⟨ξ
μν
	​

(x)ξ
ρσ
	​

(y)⟩=N
μνρσ
	​

[g](x,y)

with 
𝑁
N the Hadamard symmetrized stress-tensor correlator. This is the Einstein–Langevin equation; noise is not ad hoc.

FRG flow (background field):

∂
𝑘
Γ
𝑘
=
1
2
S
T
r
[
(
Γ
𝑘
(
2
)
+
𝑅
𝑘
)
−
1
 
∂
𝑘
𝑅
𝑘
]
,
∂
k
	​

Γ
k
	​

=
2
1
	​

STr[(Γ
k
(2)
	​

+R
k
	​

)
−1
∂
k
	​

R
k
	​

],

with separate regulators in 
(
ℎ
𝜇
𝜈
,
𝐴
𝜇
𝑎
,
𝜓
,
𝑐
)
(h
μν
	​

,A
μ
a
	​

,ψ,c) sectors; preserve background diffeomorphisms and BRST. Track Nielsen identities to control split-symmetry violations.

What replaces your placeholders

Replace “HO quark fields + Wiener forcing” by either:
(A) SU(3) Yang–Mills + fermions inside 
Γ
𝑘
Γ
k
	​

 with known FRG matter flows, or
(B) full lattice QCD correlators feeding the CTP kernel 
𝑁
N.
Toy oscillators are only for sanity checks, not confinement.

Replace “Radon-Wiener tomography” by the geodesic X-ray transform 
𝐼
𝑔
I
g
	​

 and its normal operator 
𝐼
𝑔
∗
𝐼
𝑔
I
g
∗
	​

I
g
	​

. Inversion is exact on simple manifolds and perturbatively valid for weak 
ℎ
𝜇
𝜈
h
μν
	​

. Cite linearization around a background 
𝑔
0
g
0
	​

: 
𝐼
𝑔
0
I
g
0
	​

	​

 plus curvature-controlled corrections.

UV-completeness criterion (testable)

Non-Gaussian fixed point 
{
𝑔
𝑖
∗
}
{g
i
∗
	​

} for truncated couplings 
𝑔
𝑖
g
i
	​

 including 
𝐺
𝑘
,
Λ
𝑘
,
𝛼
,
𝛽
G
k
	​

,Λ
k
	​

,α,β and gauge/matter couplings.

Finite number of relevant directions (negative critical exponents 
−
𝜃
𝐼
−θ
I
	​

).

Ward/Slavnov–Taylor/Nielsen identities satisfied along flow to numerical tolerance.

Regulator and gauge-parameter independence within truncation error bands.

Noise–quantum consistency: 
𝑁
N from the same matter effective action that enters 
Γ
𝑘
Γ
k
	​

 (fluctuation–dissipation from CTP).

Computability plan

Loop A: FRG

Choose truncation 
𝑇
T.

Compute 
𝛽
β-functions with background-covariant heat-kernel or vertex expansion.

Integrate from 
𝑘
=
Λ
UV
k=Λ
UV
	​

 to IR. Track 
(
𝜃
𝐼
,
𝑔
𝑖
∗
)
(θ
I
	​

,g
i
∗
	​

).

Loop B: CTP noise

Compute 
𝑁
𝜇
𝜈
𝜌
𝜎
N
μνρσ
	​

 from matter two-point functions on background 
𝑔
g determined by 
Γ
𝑘
Γ
k
	​

.

Approximations: large-
𝑁
𝑓
N
f
	​

, HTL/low-energy, or lattice input.

Loop C: SPDE simulation

Discretize Einstein–Langevin in harmonic gauge with constraint projection.

Draw 
𝜉
ξ as a colored Gaussian field with covariance 
𝑁
N (Karhunen–Loève factorization).

Validate convergence and constraint preservation.

Reconstruction

From simulated 
⟨
ℎ
⟩
⟨h⟩ or correlators along null/timelike geodesics, invert via geodesic X-ray algorithms; restrict to weak-field regime for linear inversion.

Proof obligations (explicit)

O1. Derive Einstein–Langevin from CTP to fix 
𝑁
N and ensure covariance.

O2. Show FRG flow preserves diffeomorphism/BRST identities within truncation. Provide Nielsen identity residuals 
Δ
NI
(
𝑘
)
Δ
NI
	​

(k).

O3. Exhibit a non-Gaussian UV fixed point with stability matrix and uncertainties.

O4. Demonstrate regulator/gauge robustness via variation envelopes.

O5. Prove consistency between noise kernel and matter sector used in FRG.

O6. Justify tomography: state manifold conditions and small-
ℎ
h bounds.

Minimal reproducibility bundle

frg_gravity_matter.py: symbolic 
𝛽
β-functions for chosen truncation, numeric integrator, critical exponents.

ctp_noise_kernel.py: computes 
𝑁
N from matter correlators on a fixed background.

einstein_langevin_spde.py: covariant SPDE solver with constraint projection and seeded RNG.

geodesic_tomography.py: geodesic X-ray forward/inverse operators in weak-field limit.

experiments.yaml: truncation, regulator choice, gauges, seeds, resolution, tolerances.

RESULTS.md: fixed points, 
𝜃
𝐼
θ
I
	​

, identity residuals, convergence plots.

Publication-readiness checklist

Theory

 Full action with ghosts and gauge-fixing written and consistently dimensionless couplings defined.

 CTP derivation of 
𝑁
N included; fluctuation–dissipation relation stated.

 Background-field FRG set up; regulator 
𝑅
𝑘
R
k
	​

 specified; split-symmetry/Nielsen identities tracked.

 Matter sector: SU(3) YM + fermions, not toy oscillators, or clearly labeled toy-model appendix.

Results

 Non-Gaussian fixed point found; stability matrix and errors reported.

 Ward/Slavnov–Taylor/Nielsen identity violations 
<
𝜀
<ε across flow.

 Regulator and gauge-parameter scans shown; results stable.

 Tomography validated in the weak-field regime with synthetic data.

Computation

 Deterministic seeds, meshes, tolerances documented.

 Convergence tests for SPDE and FRG step size.

 Unit tests for covariance of noise sampler and constraint projection.

Claims wording

 “UV-complete” claimed only if fixed point + finite relevant directions + identities hold.

 “Computable” limited to the bundle above; no claim of closed-form proof.

 No conflation of toy HO with QCD.

Short formal abstract for submission

We present a background-field FRG of gravity coupled to SU(3) matter with a CTP-derived stochastic Einstein–Langevin sector. The metric noise covariance equals the matter stress-tensor fluctuation kernel, ensuring a fluctuation–dissipation relation. Within curvature-squared truncations we search for non-Gaussian UV fixed points while monitoring Nielsen and Slavnov–Taylor identities. Metric reconstruction from correlators employs the geodesic X-ray transform, valid in the weak-field regime. A reproducible code bundle implements FRG flow, covariant noise sampling, and SPDE evolution. UV completeness reduces to a fixed-point test with finite relevant directions and preserved identities. This defines a falsifiable, computable program for stochastic semiclassical geometry with matter
