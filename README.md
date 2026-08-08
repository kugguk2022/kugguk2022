# Zolton Farkas · kugguk2022

I build **research systems and end-user products that try to produce visible, testable outcomes** — not just infrastructure for its own sake.

My work spans computational mathematics, deterministic generative systems, private communications, applied forecasting, and creative AI. The strongest projects are the ones where another person can **run something, inspect the result, reproduce the experiment, or use the product**.

[![Research](https://img.shields.io/badge/Research-EncapsulatorP-6f42c1)](https://github.com/EncapsulatorP)
[![sha.chat](https://img.shields.io/badge/Product-sha.chat-22a7e0)](https://sha.chat)
[![AlgoBeat](https://img.shields.io/badge/Product-algobeat.ai-111111)](https://algobeat.ai)
[![Alienway](https://img.shields.io/badge/Product-alienway.fun-8a2be2)](https://alienway.fun)

---

## What I am trying to ship

The goal is not to be evaluated as a CI/CD manager of many repositories.

The goal is to turn research and engineering into **things that create a meaningful win for the person using them**:

- a communication product that gives users stronger control over identity, privacy, and transport;
- a deterministic language engine that produces stable, reusable synthetic-language output;
- creative systems that turn source material into new audio / visual experiences;
- research tools that reveal structure, falsify hypotheses, or produce genuinely useful numerical evidence;
- forecasting systems that only graduate to product claims when they demonstrate real lift against relevant baselines.

That last rule matters: **interesting code is not automatically a successful product.**

---

## Products and live surfaces

| Product / site | What it is for | Current role |
| --- | --- | --- |
| **[sha.chat](https://sha.chat)** | Privacy-focused communication, calls, agents, wallet and identity work | Primary end-user product direction |
| **[algobeat.ai](https://algobeat.ai)** | Generative music / creative-AI experimentation | Product and creative-system surface |
| **[alienway.fun](https://alienway.fun)** | Cinematic world-generation and creator tooling | Early-stage creative product |
| **[EncapsulatorP](https://encapsulatorp.github.io/)** | Interactive computational-mathematics experiments | Public research surface |
| **[kugguk.com](https://kugguk.com)** | Broader project / company surface | Portfolio and navigation |

---

## Strongest public repositories by result

These are ranked by **what they currently produce**, not by repository size or DevOps polish.

### 1. [collatz_lift](https://github.com/EncapsulatorP/collatz_lift)

**Best current public research result.**

A numerical investigation of a lifted Collatz observable using complex analysis and Nevanlinna-style diagnostics.

Current checked-in results include:

- 153 directly scanned zeros across `k ∈ [-4,+4]`;
- fitted lattice generators and a measured lattice RMS;
- a negative quasi-periodicity result rather than a promoted false positive;
- a sector-imbalance sign change at `k = 0`;
- preservation of the `I2` sign under three perturbation families;
- 108 additional roots found through lattice-guided continuation from 25 seeds.

Why it belongs at the top: it has **explicit quantities, artifacts, falsification, and follow-on experiments** rather than only a conceptual proposal.

### 2. [Zyntalic_idiom](https://github.com/kugguk2022/Zyntalic_idiom)

**Best current public end-user tool.**

A deterministic synthetic-language engine with stable output for the same input/configuration.

Users can already access the work through:

- CLI translation;
- JSONL output for pipelines;
- web API;
- desktop launcher;
- deterministic seeded word generation;
- anchor-prior lexicons;
- S-O-V-C transformation;
- tests / regression checks;
- optional projection training.

The product opportunity is larger than the repo: deterministic language generation can become a reusable layer for **video, audio, subtitles, TTS, fictional worlds and media pipelines**.

### 3. [collatz_kesten-goldie](https://github.com/EncapsulatorP/collatz_kesten-goldie)

**Strong empirical cross-check.**

This project compares Collatz/RBOI-style affine recursions with Kesten-style heavy-tail regimes.

The strongest current result is the `7x+1` SSI case, where the empirical tail exponent is reported as almost exactly aligned with the theoretical prediction. The repository also documents the weaker and unstable cases instead of flattening them into one claim.

That combination — **positive result + failed/ambiguous controls** — makes it stronger research than a prettier but less discriminating experiment.

### 4. [goldbach_busy_collatz](https://github.com/EncapsulatorP/goldbach_busy_collatz)

**Best current diagnostic / exact-computation pipeline.**

The main path computes exact Goldbach representation counts on finite ranges and compares them with a calibrated heuristic model.

Its strongest result is not a new theorem. It is that the exact-count pipeline is currently trustworthy while the heuristic layer still shows residual drift and residue-class structure. That makes it valuable as **reliable experimental infrastructure with honest model diagnostics**.

### 5. [lotteries-init-at-your-service](https://github.com/kugguk2022/lotteries-init-at-your-service)

**High product upside, but not yet a demonstrated end-user win.**

The repo has become much more rigorous: forward-only evaluation, holdouts, reproducible benchmarks, schema validation, saved artifacts, and fairer comparisons.

But the current benchmark does **not** justify marketing it as a system that beats the house or produces a dependable user advantage. Until larger holdouts demonstrate durable lift, it stays in the research tier rather than the top product tier.

That is intentional. A product claim should be earned by the result.

---

## Product direction

### sha.chat

The most important product direction is private communication with stronger user control over identity, messaging, calls, and agents.

The intended win is not “better infrastructure.” It is a user being able to communicate without the product model depending on exposing a phone number, giving up unnecessary metadata, or blindly trusting autonomous actions.

### Zyntalic

Zyntalic is closest to a **small, usable public tool today**.

The next product leap is to stop presenting it mainly as a conlang experiment and package it as a deterministic media component:

```text
text / transcript
    ↓
Zyntalic deterministic transform
    ↓
subtitles / TTS / voice processing
    ↓
consistent fictional-language media
```

That gives creators something concrete they cannot get reliably from unconstrained one-shot generation: **repeatability**.

### AlgoBeat

The opportunity is an end-user creative loop where a person's source audio, voice, rhythm or direction becomes generated music / audiovisual output.

The flagship threshold should be simple: can a new user create something worth keeping without understanding the underlying model stack?

### Alienway

Alienway has the strongest long-range creative-product thesis: **Upload. Describe. Receive a world.**

Its public repository describes a Connection Engine intended to preserve relationships between shots, spaces, characters, motion, atmosphere and creator intent. It is explicitly early stage, so it belongs under product direction rather than shipped-result claims.

---

## Research philosophy

I am more interested in experiments that survive attempts to break them than in accumulating speculative claims.

The working pattern is:

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

A negative result can be valuable. A result that only exists because the benchmark was weak is not.

---

## Public research surface

Most computational-mathematics work lives under **[EncapsulatorP](https://github.com/EncapsulatorP)** and is increasingly surfaced through **[encapsulatorp.github.io](https://encapsulatorp.github.io/)**.

Current themes include:

- Collatz dynamics and generalized transforms;
- complex / log-plane lifts;
- Nevanlinna-style zero and growth diagnostics;
- Kesten-Goldie heavy-tail regimes;
- delay embeddings and computational geometry;
- Goldbach exact-count and residual diagnostics;
- prime/composite signal experiments;
- tetration and hyperoperation dynamics.

None of these are presented as proofs of open conjectures unless a proof actually exists.

---

## Private engineering

Some production, mobile, product and collaborative work remains private.

Private code is not used here as public evidence. Where useful, the public side should expose non-sensitive evidence such as:

- product behavior;
- public interfaces;
- architecture notes;
- release history;
- benchmark results;
- security / testing strategy;
- sanitized implementation evidence.

---

## What gets promoted to flagship status

A repository or product moves upward when it demonstrates at least one of these:

1. **Users can do something useful with it now.**
2. **It produces a measurable result that survives relevant controls.**
3. **It creates a repeatable output unavailable or unreliable elsewhere.**
4. **It materially improves a user's outcome against a fair baseline.**
5. **It turns a research result into a usable interaction instead of leaving it in a notebook.**

CI, tests, documentation and deployment matter because they make those wins dependable — **they are not the win themselves**.

---

## Elsewhere

- **Research:** [encapsulatorp.github.io](https://encapsulatorp.github.io/) · [github.com/EncapsulatorP](https://github.com/EncapsulatorP)
- **Private communication:** [sha.chat](https://sha.chat)
- **Generative music:** [algobeat.ai](https://algobeat.ai)
- **Creative worlds:** [alienway.fun](https://alienway.fun)
- **Project surface:** [kugguk.com](https://kugguk.com)
- **GitHub:** [github.com/kugguk2022](https://github.com/kugguk2022)

<sub>Build the evidence. Then make the evidence useful to somebody.</sub>
