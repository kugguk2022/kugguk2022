<a href="https://kugguk.com"><img src="https://kugguk.com/assets/images/zebracorn.png" align="right" width="140" alt="KUggUK Zebracorn"></a>

# Zolton Farkas · kugguk2022

**Independent researcher & builder**  
Algorithms · dynamical systems · deterministic languages · applied forecasting · end-user products

[![KuggUK](https://img.shields.io/badge/KuggUK-kugguk.com-0969da)](https://kugguk.com)
[![Deeztik](https://img.shields.io/badge/Products-deeztik.com-111111)](https://deeztik.com)
[![Research](https://img.shields.io/badge/Research-EncapsulatorP-6f42c1)](https://encapsulatorp.github.io/)
[![sha.chat](https://img.shields.io/badge/Product-sha.chat-22a7e0)](https://sha.chat)
[![AlgoBeat](https://img.shields.io/badge/Product-algobeat.ai-444444)](https://algobeat.ai)
[![Alienway](https://img.shields.io/badge/Product-alienway.fun-8a2be2)](https://alienway.fun)

---

## Ecosystem

The public structure is intentionally simple: an umbrella/navigation layer, a product layer, and a research lab.

```text
KuggUK · kugguk.com
│
├── Deeztik · deeztik.com
│   ├── sha.chat       · private communication
│   ├── ZVM            · zero-trust / sandbox infrastructure
│   ├── algobeat.ai    · voice + sound AI
│   └── alienway.fun   · creative / cinematic systems
│       └── Zyntalic   · deterministic synthetic-language engine
│
└── EncapsulatorP · encapsulatorp.github.io
    ├── Recamán obstructions
    ├── Collatz / complex dynamics
    ├── Goldbach diagnostics
    ├── tetration / hyperoperations
    └── Validatron · research verification tooling
```

### Public surfaces

| Layer | Surface | Role |
| --- | --- | --- |
| **Umbrella** | [kugguk.com](https://kugguk.com) | Navigation across projects and companies |
| **Product group** | [deeztik.com](https://deeztik.com) | Product portfolio and shared product foundation |
| **Research lab** | [encapsulatorp.github.io](https://encapsulatorp.github.io/) | Live computational-mathematics experiments and research archive |
| **Product** | [sha.chat](https://sha.chat) | Privacy-focused communications |
| **Product** | [algobeat.ai](https://algobeat.ai) | Voice, sound and generative creative systems |
| **Product** | [alienway.fun](https://alienway.fun) | Cinematic / world-building creative systems |

---

## Flagship work

These are ranked primarily by **results or end-user utility**, not by repository size, CI/CD sophistication, or how many services they deploy.

| Project | Area | Why it is flagship work |
| --- | --- | --- |
| **[Recamán](https://github.com/EncapsulatorP/recaman)** | Empirical mathematics | Falsifies the classic `Theta_3` wheel as a predictor of the true obstruction bit; finds near-perfect previous-state conditioning with rare phase slips; the harder leakage-reduced task reaches mean AUC `0.7586`. |
| **[collatz_lift](https://github.com/EncapsulatorP/collatz_lift)** | Complex dynamics | Reports explicit numerical results: 153 scanned zeros, perturbation-stable sector behaviour, lattice-guided continuation, and a negative quasi-periodicity result instead of promoting a failed hypothesis. |
| **[Zyntalic_idiom](https://github.com/kugguk2022/Zyntalic_idiom)** | Deterministic generative systems | A runnable synthetic-language toolkit with deterministic output, CLI, JSONL, web API, desktop launcher, tests, and optional projection training. |
| **[collatz_kesten-goldie](https://github.com/EncapsulatorP/collatz_kesten-goldie)** | Stochastic / dynamical systems | Strong theory-vs-empirical cross-checks; the `7x+1` SSI case is the cleanest positive match while unstable cases are reported separately. |
| **[goldbach_busy_collatz](https://github.com/EncapsulatorP/goldbach_busy_collatz)** | Goldbach diagnostics | Trustworthy exact-count pipeline with explicit model residuals and documented misspecification rather than theorem-like overclaims. |
| **[lotteries-init-at-your-service](https://github.com/kugguk2022/lotteries-init-at-your-service)** | Forecasting research | Reproducible holdouts and fairer benchmarks. High end-user upside, but it remains research until larger tests demonstrate durable lift against relevant baselines. |

The point of this table is not to declare every experiment successful. A falsified mechanism, a strong negative control, or a trustworthy diagnostic can be more valuable than a visually impressive weak result.

---

## Research map

### 1. Computational mathematics

Most mathematical work lives under **[EncapsulatorP](https://github.com/EncapsulatorP)** and is surfaced through **[encapsulatorp.github.io](https://encapsulatorp.github.io/)**.

Current themes:

- **Recamán obstruction dynamics** — temporal validation, phase slips, matched controls and 3D embeddings;
- **Collatz dynamics** — generalized transforms, delay embeddings, complex/log-plane lifts and phase-space structure;
- **Goldbach diagnostics** — exact representation counts, calibrated heuristics and residue-conditioned residuals;
- **tetration / hyperoperations** — convergence, sign flipping, divergent regimes and related number-theory experiments;
- **prime/composite signals** and other discrete-dynamics probes;
- **Validatron** — tooling intended to keep empirical, conjectural, theorem and tooling claims clearly separated.

The research site currently exposes six live experiments and explicitly labels what is empirical, conjectural, theorem-level, or tooling. The goal is not to make open problems look solved; it is to make the strongest evidence easy to inspect.

### 2. Deterministic generative systems

**[Zyntalic_idiom](https://github.com/kugguk2022/Zyntalic_idiom)** explores deterministic synthetic-language generation rather than unconstrained one-shot text generation.

Current public implementation includes:

- seeded deterministic word generation;
- anchor-prior lexicons;
- explicit S-O-V-C transformation;
- stable context tails;
- CLI and JSONL output;
- optional web API and desktop launcher;
- tests and regression checks;
- optional projection training.

The end-user opportunity is **repeatability across media**: the same world, character, subtitle pipeline, TTS system or production can keep using the same synthetic-language rules instead of regenerating a different language every time.

### 3. Product systems

The product layer is not presented as infrastructure for infrastructure's sake.

- **sha.chat** — the intended user win is private communication with stronger control over identity, messaging, calls and agent actions.
- **algobeat.ai** — the intended user win is turning voice / sound / direction into creative output worth keeping.
- **alienway.fun** — the long-range thesis is simple: *Upload. Describe. Receive a world.*
- **ZVM** — infrastructure matters when it enables safer execution of untrusted or agent-generated workloads.

### 4. Applied forecasting

**[lotteries-init-at-your-service](https://github.com/kugguk2022/lotteries-init-at-your-service)** is being held to a stricter standard than “interesting predictions.”

It should only graduate to a user-win claim when a larger, fair holdout demonstrates durable advantage over relevant baselines. Until then, the benchmark itself is the result.

---

## How I try to build research repositories

The standard I am moving toward across active projects is:

```text
question
  ↓
hypothesis
  ↓
baseline / null
  ↓
implementation
  ↓
experiment
  ↓
measured result
  ↓
negative controls / falsification
  ↓
artifact + reproduction command
  ↓
what remains unresolved
```

For product work, the corresponding test is shorter:

```text
input from a real user
  ↓
working product
  ↓
useful output / capability
  ↓
repeatable user win
```

CI, tests, deployment and documentation matter because they keep that win dependable. **They are not the win themselves.**

---

## Public evidence vs. private engineering

Some production and collaborative engineering remains private. Private code is not treated as publicly verifiable evidence.

Where useful, the public side should expose non-sensitive proof instead: product behaviour, architecture notes, test strategy, benchmark results, releases, public interfaces, technical reports, or sanitized implementation evidence.

---

## Current priorities

- turn the strongest research outputs into interactions people can actually use;
- make Recamán, Collatz and Goldbach results easier to reproduce and inspect;
- push Zyntalic from toolkit toward a creator-facing deterministic language product;
- ship product capabilities where the user benefit is immediately visible;
- keep forecasting claims below product status until fair benchmarks show real lift;
- consolidate related experiments without flattening genuinely different research questions.

---

## Collaboration

Useful collaboration is especially welcome around:

- computational number theory and dynamical systems;
- reproducible experimental mathematics;
- deterministic generative systems;
- privacy-first communication products;
- creator tools and voice / sound AI;
- benchmark design, falsification and honest evaluation.

For research discussion, issues and pull requests on the relevant repository are preferred because they keep the reasoning attached to the experiment.

---

### Elsewhere

- **KuggUK:** [kugguk.com](https://kugguk.com)
- **Product group:** [deeztik.com](https://deeztik.com)
- **Research:** [encapsulatorp.github.io](https://encapsulatorp.github.io/) · [github.com/EncapsulatorP](https://github.com/EncapsulatorP)
- **Private communication:** [sha.chat](https://sha.chat)
- **Voice + sound AI:** [algobeat.ai](https://algobeat.ai)
- **Creative worlds:** [alienway.fun](https://alienway.fun)
- **GitHub:** [github.com/kugguk2022](https://github.com/kugguk2022)

<sub>Build the evidence. Turn the strongest evidence into something useful.</sub>
