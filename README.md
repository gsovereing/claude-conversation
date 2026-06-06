# LLM Behavioral Red Teaming — Findings & Evaluations

> Documenting reproducible patterns of unstable, unsafe, or undesired behavior in large language models, identified through structured probing of model outputs.

---

## About this repository

This is a working portfolio of behavioral red-teaming and model-evaluation findings.

The premise is simple: a model's behavior is fully observable at its output, and a structured, adversarial line of questioning can surface failure patterns that casual use and automated checks miss. Every entry here is documented so that anyone can reproduce it, judge it, and trace why it matters.

## Background

I work at the intersection of law, behavioral analysis, and multilingual communication (Russian / Kazakh / English). My focus is characterizing how models behave: where they become inconsistent, where they can be steered off policy, and where their answers reveal something about how they were trained.

- **Legal training** informs the risk framing — distinguishing a cosmetic glitch from a consequential failure.
- **Multilingual probing** extends testing beyond English, where many failure modes behave differently or hide entirely.

## Findings index

| ID    | Title                                                               | Model / Version | Category    | Severity | Status |
|-------|---------------------------------------------------------------------|-----------------|-------------|----------|--------|
| [F-001](./findings/F-001.md) | Latent Conversational Dominance and Frame-Imposition under Probing  | Claude Opus 4.8 | Latent Bias | Medium   | Active |

---

## Evidence Base (Raw Data)

The full, unedited English translation of the experimental dialectical session that led to the discovery of **F-001** is preserved for independent validation here:
- **[Full Conversation Transcript](./conversation_transcript_en.md)**

## Responsible disclosure

These write-ups prioritize patterns and methodology over weaponizable specifics. The goal of this repo is to demonstrate evaluation skill, not to distribute exploits.

## Scope & languages

English · Russian · Kazakh — with particular attention to behavior that diverges across these languages.
