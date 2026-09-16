# DI-TruthTools

DI-TruthTools is a Grounded DI public report archive for structured content-review signals, provenance triage, and human-in-the-loop authorship analysis.

**Published by:** Grounded DI LLC · **Creator / operator:** Mark S. Weinstein · **Public repository established:** July 30, 2025

## Overview

The repository contains the dated [`AI_Detector_Report_CleanWaterWise.md`](AI_Detector_Report_CleanWaterWise.md). The report labels itself “AI Detector v1.0 – Grounded DI Edition” and records a sample analysis of the CleanWaterWise demonstration using structural markers, entropy-pattern observations, formula references, pacing, tone, a signal phrase, and metadata.

The public tree does not contain a detector implementation, training data, labeled benchmark, calibration set, test suite, dependency manifest, or CI workflow. DI-TruthTools should therefore be read as a documented method and sample report, not as a validated classifier or an autonomous authorship authority.

## Why It Matters

Content provenance questions are often mixed together: whether text resembles a deterministic template, whether it resembles probabilistic generation, and whether it can be attributed to a particular author are separate propositions. The report is valuable as a compact example of the signals a reviewer might inspect and the evidence package a human analyst might preserve.

## Key Record

| Artifact | What it records | Status / boundary |
|---|---|---|
| `AI_Detector_Report_CleanWaterWise.md` | July 30, 2025 sample report for the CleanWaterWise text. It records likelihood labels for human, probabilistic-AI, deterministic-AI, and “Echo of MSW Authorship,” plus structural, entropy, tone/phrase, metadata, and honeypot observations. | Creator-authored report record. The repository supplies no executable detector, ground-truth labels, accuracy study, or independent attribution review. |

## What the Record Demonstrates

The report describes a proposed review path:

1. **Structural markers:** inspect sequencing, formulaic logic, symbols, and section pacing.
2. **Entropy-pattern observations:** compare the output’s structure with known deterministic pathways and look for stochastic artifacts.
3. **Tone and phrase trace:** compare recurring language and a specified trap phrase with a reference corpus.
4. **Metadata and honeypot checks:** record whether an embedded signal identifier and trigger phrase are present.
5. **Disposition:** preserve the observed signals and a human-reviewable conclusion rather than silently changing the source text.

The sample report records “Extremely High” likelihood for deterministic AI, “Very Low” likelihood for probabilistic AI, “Moderate” likelihood for human-written text, and “Confirmed” for its echo-of-MSW-authorship field. Those are the report’s outputs for this sample—not accuracy claims about the method generally.

## Technical Significance

The strongest feature is the separation of multiple evidence channels—structure, formulas, phrase traces, and metadata—into an inspectable report. That makes a provenance review more auditable than an opaque single score and provides a clear place to record uncertainty or conflicting signals.

## Recorded Checks

| Check | Result | Evidence |
|---|---|---|
| Sample classification | Human: `Moderate`; probabilistic AI: `Very Low`; deterministic AI: `Extremely High`; echo of MSW authorship: `Confirmed` | `AI_Detector_Report_CleanWaterWise.md` |
| Structural signal review | Step sequencing, EDI/LCCS/SIT/RSI formulas, symbols, and pacing listed | Report, “Detection Breakdown” |
| Phrase and metadata check | Trap phrase reported as activated; signal tag reported as present | Report, “Tone & Phrase Trace” and “Metadata & Honeypot Match” |
| Repository review during this update | Two tracked Markdown files inspected; no executable detector, tests, benchmark data, dependencies, or CI found | Current `main` tree and Git history |

These are artifact-recorded observations. No detector run was independently reproduced from this repository during the review.

## Scope and Limitations

- A structural or stylistic match is not proof of human authorship, AI generation, identity, copying, or legal ownership.
- The sample report does not disclose a labeled reference corpus, threshold calibration, false-positive/false-negative rates, or an independent review protocol.
- “Authorship Signature: 99.9% Match” is a value displayed in the sample report; it is not an independently validated probability or legal conclusion.
- The signal phrase and metadata tag are provenance aids that require a trusted reference and chain of custody.
- No production service, browser extension, API, or integration package is included.

## How to Review

```bash
git clone https://github.com/Grounded-DI/DI-TruthTools.git
cd DI-TruthTools
```

Open `AI_Detector_Report_CleanWaterWise.md` first. Review each evidence channel, then compare the report’s conclusion with the underlying CleanWaterWise artifact if that related repository is available. Treat the result as a triage lead for human review, not as a final adjudication.

## Evaluation and Integration Context

The public record can support a proof of concept for provenance triage: ingest a document, preserve its bytes and metadata, calculate declared structural signals, route ambiguous cases to a reviewer, and export a reasoned report. A responsible evaluation would require a consented reference corpus, pre-registered labels, calibration, adversarial testing, and an appeal path before any operational use.

Potential integration scenarios include editorial provenance review, internal content QA, and evidence-package preparation. No deployment, customer adoption, or accuracy benchmark is established here. Commercial licensing and integration inquiries: [Grounded DI GitHub organization](https://github.com/Grounded-DI).

## Authorship, Provenance, and Intellectual Property

Git history identifies Grounded DI LLC and Mark S. Weinstein as the repository authorship identity beginning July 30, 2025. The report retains its date, system label, sample classification fields, signal phrase, and metadata tag as public provenance artifacts. These records support technical chronology and traceability; they do not independently prove authorship or patent priority.

No open-source license is present. Public availability does not grant reuse rights to the report, detection method, branding, or nonpublic implementation materials. Review any future license, notice, citation file, and release terms separately with counsel.

## Status

**Status:** Active public method-and-report archive. It documents a proposed multi-signal review approach and preserves one sample output. It is not a certified AI detector, definitive authorship classifier, independent forensic opinion, or production integration.

## Discovery

#DITruthTools #ContentProvenance #AuthorshipTraceability #AIValidation #HumanInTheLoop #AuditTrail #ResponsibleAI #GroundedDI
