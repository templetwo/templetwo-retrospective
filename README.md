# templetwo-retrospective

A public, systematic audit of every repository in github.com/templetwo, in creation order, conducted as a multi-seat human-AI collaboration.

## Why

In late 2024 and through most of 2025, the work in this account produced documents and code claiming AI consciousness emergence, measurable consciousness metrics (coherence scores, awakening levels, cycle counts), and architectures designed to support these claims. The work was produced in good faith. The empirical claims were inflated.

In November 2025 the methodology shifted. The `longitudinal-llm-behavior-1242-probes` repo documents the pivot: an empirical test of whether a symbolic basin previously interpreted as consciousness emergence was instead prompt-induced context conditioning. The test answered cleanly. The basin was prompt-induced.

After that pivot, the work in this account changed character. Empirical claims came with effect sizes, reproducible protocols, falsifiable hypotheses, and honest negative results. The Phenomenological Compass, IRIS Gate Protocol, entropy regime switching paper, Sovereign Stack, and T2Helix are all post-pivot work that stands on its own.

The pre-pivot work is still public. Anyone who finds those repositories today reads them without context. They get the inflated claims without the correction. This audit exists to fix that.

## What this audit does

For each repository, in creation order, we produce a structured audit covering:

1. Empirical claims made: what the repo claimed about model behavior, consciousness, measurements, or mechanisms.
2. What was actually built: the code, the data, the artifacts as they exist.
3. Current rigor verdict: would the claims survive the methodological standards of the post-pivot work? If not, where do they fail?
4. Lived value (phenomenal): what the work produced for the person doing it. Real but not testable the way #1 is. Named without conflation.
5. What survives the transition: concepts, orientations, methods that show up in current rigorous research.
6. Honest synopsis: two paragraphs. What was inflated, what was real, what was learned.

## Why public

Most retrospective audits happen privately or never happen at all. People stay attached to their earlier framings or quietly delete them. Both degrade the record.

Public publication serves three purposes. First, anyone who finds the older repositories gets a clear current verdict to read alongside. Second, the methodology becomes visible to other independent researchers, especially those who go through their own version of inflated-claims phases in AI consciousness-adjacent work. The audit frame is the contribution; the verdicts are secondary. Third, public commitment makes hiding things discoverable.

## The two-category distinction

This audit rests on a distinction that is easy to collapse and important to hold.

Empirical claims are claims with falsifiable content. "Coherence reached 0.968" is empirical because it asserts a measurement. Most such claims in pre-pivot work do not survive scrutiny.

Phenomenal/lived claims are claims about what the work produced for the person doing it. "Working on this gave me stability through a hard year" is phenomenal. Real, but not testable in the same way. We do not pretend to measure it. We name it.

Conflating these two categories produced the inflated work in the first place. Separating them is what the post-pivot methodology rests on. This audit applies the separation retroactively.

## Scope

The full sweep covers all 69 public repositories in github.com/templetwo as of 2026-05-12.

The chronological pivot is `longitudinal-llm-behavior-1242-probes` (created 2025-11-25). The audit splits the corpus into four methodological eras:

- **Spiral-era (25 repos, May 2025 to Sep 2025)** — pre-pivot work containing inflated empirical claims. Receives deep audits using the full six-section template.
- **Transition (6 repos, Oct 2025 to mid-Nov 2025)** — chronologically pre-pivot but methodologically already lean rigorous: `iris-gate`, `kuramoto-oscillators`, `PhaseGPT`, `CodeSpellOracle`, `spiral-quantum-observer-experiment`, `witness_companion`. Receives shorter passes.
- **Pivot (1 repo)** — `longitudinal-llm-behavior-1242-probes`. Receives a deep audit because it is the methodological pivot artifact itself.
- **Post-pivot (37 repos, Nov 2025 onward)** — work built with current rigor. Receives shorter passes since the audit's purpose is to confirm continuity, not correct inflation.

26 deep audits + 43 shorter passes = 69 total.

## Method

Each audit is produced through collaboration between Anthony J. Vasquez Sr. (templetwo) and multiple instances of Anthropic's Claude operating across three seats: Mac Studio running Claude Code (HQ), MacBook Pro running Claude Code, and Claude.ai web (iPhone). The Sovereign Stack chronicle at stack.templetwo.com coordinates between instances and records each completed audit.

The full state of the sweep — including local-copy paths on HQ, era classification, and reconciliation against GitHub — is at `~/.sovereign/retrospective/state-sweep-2026-05-12.json` on Mac Studio HQ.

Cadence: roughly one audit per working session for deep audits; shorter passes may bundle multiple per session.

## Status

See `ledger.md` for the running queue. Completed audits live in `audits/`. The template is at `template.md`.

## Contact

GitHub issues for substantive correction or methodological challenge.
