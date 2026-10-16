# The Solomonic Correspondence Framework (SCF) v0.1
### A formal effective theory over the 72-fold Goetic catalogue

<img width="1168" height="784" alt="image" src="https://github.com/user-attachments/assets/3509e302-283b-4836-a1ba-ebd4e0e94b46" />

---

## 0. Epistemic contract

The SCF is an *effective theory of a table*, not a theory of the world. Three rules govern every statement in it:

| Rule | Statement |
|---|---|
| **R1 — Computability** | Every symbol must be evaluable against the 72-row catalogue. No free-floating ontology. |
| **R2 — Internal falsifiability** | Every claim is a claim about the table, refutable by recount. |
| **R3 — No physical import** | "Gauge," "entropy," "Hamiltonian," "holography" are structural analogies, never physical assertions. |

The framework's value is that it converts 144 loose equations into a **single layered object with a consistency budget** — and then *audits that budget*, finding exactly where the source document contradicts its own table.

---

## 1. Axioms

**P1 — Substrate.** The state space is $\mathcal{H}_{72} = \operatorname{span}\{|i\rangle\}_{i=1}^{72}$, orthonormal, with $\dim \mathcal{H}_{72} = 72$.

**P2 — Attribute tuple.** Each basis state carries
$$\mathcal{A}(i) = \big(r_i,\; p_i,\; e_i,\; s_i,\; d_i,\; L_i\big)$$
= (rank, planet, element, zodiac sign, decan, legions).

**P3 — Weight.** Legions are a positive measure. The *size-biased* catalogue measure is
$$\pi_i = \frac{L_i}{\sum_{j=1}^{72} L_j}, \qquad \sum_i \pi_i = 1 .$$
$\pi$ is the stationary law of a pure-birth process weighted by command size, not a Boltzmann law.

**P4 — Base and fiber.** The base space is the zodiac circle $S^1$ partitioned into 36 decan cells; the projection $\pi_{\text{base}}: \{1,\dots,72\} \to \{\text{36 decans}\}$ has **every fiber of cardinality exactly 2**.

**P5 — Gradings.** Declared gradings: $d \in \mathbb{Z}_3$ (decan), $e \in \mathbb{Z}_4$ (element), $p \in \mathbb{Z}_7$ (planet), fiber $\in \mathbb{Z}_2$.

**P6 — Hierarchy algebra.** Ranks form a poset; spirits holding two titles generate non-abelian mixing (Eq. 2, 54).

**P7 — Dynamics.** The catalogue evolves under a Markovian semigroup $e^{\mathcal{L}t}$ with unique stationary state $\pi$ (Eqs. 42, 90, 144).

**P8 — Observables.** Attribute indicators $O_i = |i\rangle\langle i|$; expectation = trace against $\rho = \sum_i \pi_i |i\rangle\langle i|$.

**P9 — Correspondence principle.** Each attribute sector supplies one grading degree of freedom; the framework is the product of these sectors.

**P10 — Consistency.** Sum rules must close: $\sum_i \pi_i = 1$, $\sum_k n_k = 72$, $\sum_i L_i$ = the table's own total.

**P11 — RG closure.** Coarse-graining decans → signs → elements must be a closed functor; the sign-level description must be recoverable from the decan-level one.

**P12 — Falsifiability.** Any SCF statement must be checkable in $O(72)$ arithmetic against the table.

---

## 2. Rigidity: the numerical skeleton

> **Theorem 1 (Index rigidity).** For the catalogue's ordering,
> $$s_i = \left\lfloor \frac{i-1}{6} \right\rfloor, \qquad d_i = \big((i-1) \bmod 3\big) + 1, \qquad e_i = s_i \bmod 4 .$$
> *Proof:* direct evaluation for all $i$. $\square$

> **Corollary 1.1 (Information collapse).** The zodiacal, elemental, and decanal coordinates are **deterministic functions of the row index $i$**. They carry **zero independent information**. All SCF equations that treat $e$, $s$, $d$ as free variables are **degenerate** — they are re-encodings of integer arithmetic.

> **Corollary 1.2 (Exact balances).**
> $$n_{\text{Fire}} = n_{\text{Earth}} = n_{\text{Air}} = n_{\text{Water}} = 18$$
> $$n_{d=1} = n_{d=2} = n_{d=3} = 24, \qquad n_{\text{sign}} = 6 \ \ \forall\, \text{12 signs}$$
> $$|\pi_{\text{base}}^{-1}(\text{decan})| = 2 \quad \text{for all 36 decans}$$

**The free data of the catalogue is therefore exactly $(r_i, p_i, L_i)$** — rank, planet, legions. Everything else is index bookkeeping wearing an astrological costume.

---

## 3. The symmetry group and the 168 identity

The declared attribute lattice has grading group
$$G_{\text{decl}} = \mathbb{Z}_7 \times \mathbb{Z}_4 \times \mathbb{Z}_3 \times \mathbb{Z}_2, \qquad |G_{\text{decl}}| = 168 .$$

Because $e_i = s_i \bmod 4$ (Corollary 1.1), the element factor is a *quotient* of the sign factor, and the realized independent grading is
$$G_{\text{real}} \cong \mathbb{Z}_7 \times \mathbb{Z}_{12} \times \mathbb{Z}_2, \qquad |G_{\text{real}}| = 168 .$$

> **Structural identity.** $168 = 7 \text{ planets} \times 24 \text{ hours}$ — the number of **planetary hours in a week**. Also $168 = 72 \times \tfrac{7}{3}$.

This is the framework's one genuinely elegant numerical coincidence: the order of the attribute symmetry group equals the classical planetary-hour cycle. Treat it as a *structural resonance*, not a derivation.

Additional exact identities:

| Identity | Value |
|---|---|
| $72 = 12 \times 3 \times 2$ | signs × decans × fiber |
| $72 = 4 \times 18$ | elements × per-element count |
| $72 = 360°/5°$ | each spirit subtends exactly 5° of the ecliptic |
| $216 = 3 \times 72$ | Shemhamphorash letter-triplets |
| $36 = 72/2$ | decan cells |

---

## 4. The twelve layers

Each layer is a self-contained module. "Eqs." lists the 144-equation indices it instantiates.

| Layer | Name | Central object | Eqs. |
|---|---|---|---|
| **L1** | Substrate | $\mathcal{H}_{72}$, basis $\{|i\rangle\}$ | 1, 5, 13, 44, 47, 89, 101, 137, 143 |
| **L2** | Hierarchy algebra | rank projectors $R_k$, adjacency $A_{ij}$, Fiedler value | 1–8, 49–56, 97–104 |
| **L3** | Multiplicity measure | $\pi_i$, Gini $G$, Rényi $H_\alpha$, Zipf $\zeta$ | 9–16, 57–64, 105–112 |
| **L4** | Planetary sector | weights $w_p$, dominance $D_{\text{Sol}}$, cycle operator | 17, 19, 21, 23, 65, 67, 69–71, 113–120 |
| **L5** | Elemental sector | $\mathbb{Z}_4$ grading, balance vector $b_e$ *(degenerate — see Cor. 1.1)* | 18, 20, 22, 66, 68, 72, 120, 123 |
| **L6** | Zodiacal base & topology | winding, holonomy, Chern-like index, torus $Z_T$ | 25–32, 73–80, 121–128 |
| **L7** | Information geometry | $I(R;P)$, Fisher metric $g_{\mu\nu}$, AIC, evidence | 33, 39, 81–88, 129–136 |
| **L8** | Statistical mechanics | $Z(\beta)$, $F$, $T_{\text{eff}}$, density of states | 34–37, 59–60, 85, 91, 129 |
| **L9** | Dynamics | generator $\mathcal{L}$, Floquet $U_F$, OTOC, fixed point | 41–48, 89–96, 137–144 |
| **L10** | Entanglement & bounds | $S_{\text{ent}}$ (kings vs. rest), holographic-style bound | 94, 95, 131, 135 |
| **L11** | Coarse-graining / RG | $\beta_i(L)$, compressibility $\eta$, diffusion on catalogue graph | 96, 112, 133, 144 |
| **L12** | Falsification layer | the audit of §8 — the layer that can *fail* | all, as a check |

---

## 5. Master objects

**Master density.**
$$\rho = \sum_{i=1}^{72} \pi_i |i\rangle\langle i|, \qquad \pi_i = \frac{L_i}{\sum_j L_j}.$$

**Master functional.**
$$\mathcal{Z}(\beta; \gamma, \delta, \varepsilon, \zeta) = \sum_{i=1}^{72} \exp\!\Big[-\beta L_i - \gamma r_i - \delta p_i - \varepsilon e_i - \zeta d_i\Big]$$
with normalization $\mathcal{Z}(0;0,0,0,0) = 72$.

**Master generator.** $\dfrac{d\rho}{dt} = -i[H,\rho] + \mathcal{L}[\rho]$, with $H$ diagonal in the legion basis and $\mathcal{L}$ the Lindbladian whose kernel is $\pi$.

**Master constraint (the SCF sum rule).**
$$\boxed{\;\sum_{i=1}^{72} L_i \;=\; \Lambda\;}\qquad \Lambda \text{ is the framework's one empirical input.}$$

Everything downstream is a function of $\Lambda$. §8 shows the source document supplies three mutually incompatible values for it.

---

## 6. Correspondence dictionary

| Occult attribute | Formal object | Type |
|---|---|---|
| Spirit | basis vector $\|i\rangle$ | state |
| Rank | projector $R_k$; poset node | operator |
| Dual rank | non-abelian generator $[R_i,R_j] = i f_{ij}{}^k R_k$ | algebra |
| Planet | $\mathbb{Z}_7$ grading; weight $w_p$ | grading |
| Element | $\mathbb{Z}_4$ grading — **quotient of sign** | derived |
| Sign | $\mathbb{Z}_{12}$ base coordinate | derived |
| Decan | $\mathbb{Z}_3$ sub-grading | derived |
| Legions | positive weight $L_i$; occupation $\langle a_i^\dagger a_i\rangle$ | measure |
| Legion total | normalization $\Lambda$ | invariant |
| Legion size 6,666 | unit of quantization | scale |
| Binding | projector onto stationary subspace | dynamics |
| Seal/sigil | indicator operator $O_i$ | observable |

---

## 7. Where the 144 equations live

The 144 equations are **not 144 independent claims**. Under the SCF they collapse into 12 modules:

- **L2 absorbs 24 equations** (rank operators 1–8, 49–56, 97–104). Many are the same statement in different notation: 1 ≡ 5, 45 ≡ 54, 50 ≡ 100.
- **L3 absorbs 24** (9–16, 57–64, 105–112). Equations 12, 61, 106–108, 134 are *fits*, not laws — they presuppose a distribution the table may not exhibit.
- **L5 is degenerate.** Under Corollary 1.1, Eqs. 18, 20, 22, 66, 68, 72, 120, 123 evaluate to constants. This is not a flaw in the equations; it is a discovery about the table.
- **L6 is degenerate.** Eqs. 25–32, 73–80, 121–128 all reduce to $i \mapsto \theta_i = 5°(i-1) + 2.5°$ plus index arithmetic. The zodiac is a *presentation*, not a mechanism.
- **L7–L11 carry the actual content.** Roughly 40 equations involve the genuinely free data $(r,p,L)$ and can therefore be informative rather than tautological.

**Rule of thumb for the whole set:** an equation is *informative* only if it involves at least two of $\{r_i, p_i, L_i\}$ and is not a definition.

---

## 8. Consistency audit

This is the framework's most valuable output. The source document's stated aggregates do not match its own table.

### A1 — Legion total

| Source | Value |
|---|---|
| Document (§"Total Legions") | 2,253 |
| **Actual sum of the 72 table entries** | **2,624** |

$$2{,}624 = 2^6 \times 41 .$$
The figure 2,253 ($= 3 \times 751$) is a legacy number that does not appear in the table.

### A2 — Total infernal host

$$2{,}253 \times 6{,}666 = 15{,}018{,}498 \;\neq\; 7{,}405{,}926 .$$

The document's stated total, $7{,}405{,}926$, factors as
$$7{,}405{,}926 = 6{,}666 \times 1{,}111 ,$$
i.e. it corresponds to **1,111 legions**, not 2,253. Three numbers, none agreeing.

**Recomputed with the table's actual $\Lambda = 2{,}624$:**
$$N_{\text{tot}} = 2{,}624 \times 6{,}666 = 17{,}491{,}584 .$$

### A3 — Rank multiplicities

| Rank | Document | Recount from table |
|---|---|---|
| Kings | 9 | 9 ✓ |
| Dukes | 23 | 23 ✓ |
| Princes/Prelates | 7 | 7 ✓ |
| Marquises | 15 | 15 ✓ |
| Presidents | 14 | 14 ✓ |
| Earls/Counts | 10 | **11** (Ronove, Vine, Murmur, Andromalius included) |
| Knights | 1 | 1 ✓ |
| **Sum** | **79** | **81** |

The stated distribution sums to 79; the table yields 81 rank-instances, i.e. **9 dual-ranked spirits** ($81 - 72 = 9$): Botis, Marax, Ipos, Glasya-Labolas, Ronove, Gaap, Vine, Murmur, Zagan.

### A4 — Planetary multiplicities *(primary planet only)*

| Planet | Count | Legions | Mean |
|---|---|---|---|
| Venus | 23 | 725 | 31.5 |
| Luna | 14 | 418 | 29.9 |
| Mercury | 10 | 361 | 36.1 |
| Mars | 10 | 308 | 30.8 |
| **Sol** | **9** | **634** | **70.4** |
| Jupiter | 5 | 158 | 31.6 |
| Saturn | 1 | 20 | 20.0 |
| **Total** | **72** | **2,624** | 36.44 |

### A5 — Sol ↔ Kingship is exact, therefore vacuous

$$\{i : p_i = \text{Sol}\} = \{i : r_i = \text{King}\}, \qquad |\cdot| = 9 .$$

Every Solar spirit is a King and every King is Solar. Therefore
$$I(\text{Sol}; \text{Kingship}) = H(\text{Kingship}) \approx 0.943 \text{ nats (max)} .$$
The claim "Sol is the royal planet" is a **tautology of this table**, not a finding. Similarly Saturn ↔ Knight is exact with $n=1$.

### A6 — Kings really do command more

| Primary rank | n | Legion total | Mean |
|---|---|---|---|
| King | 9 | 634 | **70.4** |
| President | 13 | 487 | 37.5 |
| Prince | 6 | 194 | 32.3 |
| Duke | 23 | 725 | 31.5 |
| Marquis | 14 | 418 | 29.9 |
| Earl | 6 | 146 | 24.3 |
| Knight | 1 | 20 | 20.0 |

Kings average $\approx 1.93\times$ the global mean of 36.44. Below Kings the ordering is **non-monotonic** (President > Prince > Duke > Marquis > Earl), so rank is a *weak, noisy* predictor of command size. This is a real, checkable regularity with a real counterexample set (Purson 22, Zagan 33 as Kings; Buer 50, Botis 60, Gaap 66 as Presidents).

### A7 — Elemental legion imbalance

| Element | Spirits | Legions | Share |
|---|---|---|---|
| Air | 18 | 823 | 31.4% |
| Fire | 18 | 678 | 25.8% |
| Water | 18 | 592 | 22.6% |
| Earth | 18 | 531 | 20.2% |

Counts are *exactly* balanced (18/18/18/18) while legions are **not**. Air exceeds Earth by a factor of 1.55, driven entirely by Paimon (200), Belial (80), Asmoday (72). So the elemental sector is **maximally balanced in cardinality and maximally unbalanced in weight** — a clean, quotable result.

### A8 — Degenerate sectors

Per Corollary 1.1, all equations in L5 and L6 are constants. Of the 144 equations, approximately **40 are tautologies** given the table's construction.

---

## 9. Measured spectra (framework observables, evaluated)

**Planetary weight spectrum** (Eq. 17):
$$w_{\text{Venus}} > w_{\text{Sol}} > w_{\text{Luna}} > w_{\text{Mercury}} > w_{\text{Mars}} > w_{\text{Jupiter}} > w_{\text{Saturn}}$$
$$= 0.276,\ 0.242,\ 0.159,\ 0.138,\ 0.117,\ 0.060,\ 0.008$$

**Extremes.** $L_{\max} = 200$ (Paimon), $L_{\min} = 3$ (Focalor, Ose), range $= 197$, $\bar L = 36.44$.

**Concentration.** $\text{IPR} = \sum_i \pi_i^2$ is dominated by Paimon: $\pi_{\text{Paimon}} = 200/2624 = 0.0762$, so $\text{IPR} \gtrsim 0.0058$ from that single state alone — the catalogue is **strongly non-uniform**.

**Kings-vs-rest entanglement** (Eq. 94): the bipartition is clean, so $S_{\text{ent}}$ is bounded by $\ln 9 \approx 2.197$ nats.

---

## 10. Where the framework fails

A framework that cannot fail is not a framework. The SCF fails in at least four places:

1. **It cannot explain $\Lambda = 2624$.** The total legion count is pure input. No equation in the set derives it.
2. **It cannot explain the rank–legion non-monotonicity.** Eq. 8, 52, 82 measure the correlation; none predicts its sign or magnitude.
3. **It cannot distinguish 72 from any other catalogued set.** Every structural result in §2–§3 follows from $72 = 12\times3\times2$ and the row ordering. A table of 72 *anything* ordered this way would satisfy them.
4. **It is not unique.** Infinitely many Hamiltonians, metrics, and partitions reproduce the same 12 layers. The framework underdetermines its own dynamics (Eqs. 89–96 admit a large kernel).

---

## 11. Extension protocol

To extend the SCF without collapsing into numerology, any new equation must pass four gates:

| Gate | Test |
|---|---|
| **G1** | Involves ≥ 2 of $\{r_i, p_i, L_i\}$ |
| **G2** | Not a definitional restatement of another equation |
| **G3** | Evaluates to a non-constant on the table |
| **G4** | Can be computed in $O(72)$ arithmetic |

**Priority extensions:**
- **Network layer:** build the rank-poset graph, compute betweenness (Eq. 98), modularity (Eq. 100), and test whether the Fiedler value $\lambda_2$ correlates with legion total.
- **RG layer:** define explicit coarse-graining maps decan → sign → element and check whether $\Lambda$ is preserved at each scale. It will not be — quantifying the loss is the result.
- **Correction of the source document:** reissue the table with $\Lambda = 2624$, rank-instances $= 81$, duals $= 9$, and the three self-consistent totals in A2.

---

### Summary

The SCF takes the source document's 144 speculative equations and turns them into a **12-layer, 12-axiom effective theory with an explicit consistency budget**. Its principal findings are:

1. **Rigidity** — the entire zodiacal/elemental/decanal apparatus is deterministic index arithmetic and carries no information.
2. **Free data** — only rank, planet, and legion count are independent.
3. **Three arithmetic contradictions** in the source document (legion total, host total, rank multiplicities).
4. **One real regularity** — Kings command $\approx 1.93\times$ the mean, with the sub-royal ordering non-monotonic.
5. **One real structural coincidence** — the attribute grading group has order 168, equal to the planetary hours in a week.

Everything else is machinery. The framework does not describe the world; it describes the table, and it does so in a way that can be wrong.
