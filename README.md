# Zolton Farkas · kugguk2022

Independent researcher and builder working across **computational mathematics, deterministic generative systems, applied forecasting, and product infrastructure**.

I use GitHub as a working lab: public repositories are expected to show the question being explored, the implementation, the evidence produced, and the limits of the current result.

[![Research](https://img.shields.io/badge/Research-EncapsulatorP-6f42c1)](https://github.com/EncapsulatorP)
[![Website](https://img.shields.io/badge/Website-kugguk.com-0969da)](https://kugguk.com)
[![Python](https://img.shields.io/badge/Python-research%20%26%20tooling-3776AB)](https://github.com/kugguk2022?tab=repositories)

---

## Flagship work

| Project | Area | What it demonstrates |
| --- | --- | --- |
| **[Zyntalic_idiom](https://github.com/kugguk2022/Zyntalic_idiom)** | Deterministic generative systems | A reproducible synthetic-language toolkit with deterministic word generation, anchor priors, S-O-V-C ordering, CLI, web API, desktop launcher, tests, and optional projection training. |
| **[lotteries-init-at-your-service](https://github.com/kugguk2022/lotteries-init-at-your-service)** | Applied forecasting / statistical experimentation | End-to-end lottery analysis with normalized datasets, reproducible baselines, holdout evaluation, benchmark artifacts, tests, and explicit documentation of where a method does **not** outperform the baseline. |
| **[collatz_quasi_particle_by_forced_tetration](https://github.com/EncapsulatorP/collatz_quasi_particle_by_forced_tetration)** | Computational mathematics | Experimental work connecting Collatz dynamics, forced tetration, phase-space structure, perturbation-style reasoning, and computational geometry. |
| **[collatz_rupert_delay_embedding](https://github.com/EncapsulatorP/collatz_rupert_delay_embedding)** | Dynamical systems / geometry | Collatz trajectories explored through delay embeddings, convex geometry, Rupert-style structure, and computational geometry. |
| **[prime-polarity](https://github.com/EncapsulatorP/prime-polarity)** | Number theory experimentation | Prime-vs-composite signal exploration with a deliberately compact computational framing. |

---

## Research map

### 1. Computational mathematics

Primary themes:

- Collatz dynamics and generalized transforms
- tetration / hyperoperation behaviour
- delay embeddings and phase-space representations
- prime/composite signal structure
- computational geometry applied to discrete dynamics

Most of this work lives under **[EncapsulatorP](https://github.com/EncapsulatorP)**.

The goal is not to present experimental observations as proofs. The useful output is a trail of **hypotheses, code, visualizations, counterexamples, reproducible experiments, and open questions**.

### 2. Deterministic generative systems

**[Zyntalic_idiom](https://github.com/kugguk2022/Zyntalic_idiom)** explores a deterministic synthetic-language pipeline rather than unconstrained text generation.

Current public implementation includes:

- seeded deterministic word generation
- anchor-prior lexicons
- explicit S-O-V-C transformation
- stable context tails
- CLI and JSONL output
- optional web API and desktop launcher
- tests and regression checks
- optional projection training

The interesting engineering property is **stable output under the same input and configuration**, which makes the system easier to evaluate, test, and integrate into larger media pipelines.

### 3. Applied forecasting and statistical systems

**[lotteries-init-at-your-service](https://github.com/kugguk2022/lotteries-init-at-your-service)** is a research playground for EuroMillions, Totoloto, and EuroDreams.

The repository currently exposes:

- normalized historical-data pipelines
- forward-only / holdout evaluation
- frequency and arithmetic baselines
- Sobol / combinadic candidate generation experiments
- reproducible benchmark commands
- saved benchmark artifacts
- schema validation and tests
- explicit negative findings where newer methods fail to beat the current validated baseline

That last point matters: **a failed hypothesis is still useful research when the benchmark is reproducible and the result is reported instead of hidden.**

---

## How I try to build research repositories

The standard I am moving toward across active projects is:

```text
question
  ↓
hypothesis
  ↓
baseline
  ↓
implementation
  ↓
experiment
  ↓
result + artifacts
  ↓
limitations / counterexamples
  ↓
reproduction command
  ↓
next question
```

For engineering-heavy work, the target is similarly concrete:

```text
source → tests → CI → reproducible build → versioned artifact → documented limitations
```

Not every repository is at that standard yet. The point of this profile is to make the strongest work easy to find while the rest is progressively brought up to the same bar.

---

## Public evidence vs. private engineering

Some product and collaborative engineering work remains private. I do **not** treat private code as publicly verifiable evidence.

Where relevant, public material should expose non-sensitive proof of engineering maturity instead: architecture notes, test strategy, reproducible benchmarks, release history, public interfaces, technical reports, or sanitized implementation evidence.

Public claims on this profile are therefore intentionally tied to repositories and artifacts that another person can inspect.

---

## Current priorities

- increase reproducibility across computational-math experiments
- consolidate closely related repositories into clearer research programs
- improve tests, CI, releases, and methodology documentation on flagship repos
- publish stronger baselines before promoting new claims
- keep experimental and production claims clearly separated

---

## Collaboration

Useful collaboration is especially welcome around:

- dynamical systems and computational number theory
- experimental mathematics and reproducibility
- deterministic generative systems
- forecasting methodology and benchmark design
- code review focused on tests, methodology, and falsifiability

For research discussion, issues and pull requests on the relevant repository are preferred because they leave the technical reasoning attached to the work.

---

### Elsewhere

- **Research organization:** [EncapsulatorP](https://github.com/EncapsulatorP)
- **Main site:** [kugguk.com](https://kugguk.com)
- **Public repositories:** [github.com/kugguk2022?tab=repositories](https://github.com/kugguk2022?tab=repositories)

<sub>Independent by design. Experimental claims remain experimental until the evidence supports something stronger.</sub>
