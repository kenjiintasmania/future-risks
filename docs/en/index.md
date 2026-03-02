# Version: 0.2
# Date: 2026-03-03 00:15
# Change: Concept safety patch — definitions under peer review withheld

---
layout: default
title: "Under-Recognized Future Risks"
lang: en
---

# Under-Recognized Future Risks

**A risk without a name is treated as a risk that does not exist.**

Last updated: March 3, 2026  
Author: [Kenji Yamada](../bio)
Co-created with: Claude (Anthropic)  
License: CC BY 4.0

---

## About This Project

This project identifies, structures, and publishes future risks that carry high threat levels yet remain severely under-recognized in policy and public awareness. It covers 26 far-future risks (2030–2060+) organized in a four-layer architecture, plus 5 near-future risks (2025–2030) currently under development.

Detailed analyses are written in Japanese. This page provides a self-contained English summary with full risk tables and a glossary of key terms to support machine translation of Japanese documents.

**Three Pillars:**

| Pillar | Medium | Function |
|--------|--------|----------|
| Academic Structure | [GitHub Pages](https://kenjiintasmania.github.io/future-risks/) | Structured risk analysis and documentation |
| Thinking Logs | [Note](https://note.com/portfolio_5round) | Recording how concepts emerge through AI dialogue |
| Experiential Vaccine | [Game Books](https://www.amazon.co.jp/stores/author/B0DPHKFM25) | Risk "inoculation" through forced decision-making in fiction |

---

## Four-Layer Architecture

```
┌──────────────────────────────────────────────────┐
│  META-RISK LAYER                                 │
│  ASI (Artificial Superintelligence)              │
│  → Invalidates all evaluation frameworks         │
└──────────────────────────────────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────────┐
│  QUASI-META-RISK LAYER: AGI (8 risks)            │
│  → Accelerates and transforms all existing risks │
│                                                  │
│  Upstream: AGI Safety Collapse (74)              │
│  Midstream: Infrastructure SPOF (69),            │
│    Impersonation (68), Unverifiable Knowledge    │
│    (64), Core Asset Monopoly (64)                │
│  Emergent Talent Bundle: Kindness Arms Race (57),│
│    Labor Replacement (55), Emergence Monopoly(54)│
│  Downstream: AI Sphere Conflict (71)             │
└──────────────────────────────────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────────┐
│  FOUNDATION RISK LAYER                           │
│  Layer 1: Meaning Singularity (†)                │
│  Layer 2: Meaning Loss Risk (53) — already active│
│  Layer 3: Microplastics (54) — already active    │
│                                                  │
│  † Formal definition under peer review.          │
│    See forthcoming publication.                  │
└──────────────────────────────────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────────┐
│  THREAT BUNDLES + HUB-SATELLITE                  │
│  Synthetic Biology Bundle (4 risks)              │
│  Epistemological Collapse Bundle (3 risks)       │
│  Neural Control Bundle (3 risks)                 │
│  Hub: A/P Conflict + Satellites (4 risks)        │
└──────────────────────────────────────────────────┘
```

---

## Evaluation Framework

Each risk is scored on four factors:

| Factor | Description |
|--------|-------------|
| Threat Level | Impact scale × Irreversibility × Lethality × Proximity |
| Recognition | Current awareness in public, policy, and academia |
| Precursor Level | Observable early signals already present |
| Policy Response | Existing institutional countermeasures |

**Urgency** = Threat × (1 − Recognition) × (1 − Policy Response) × Precursor Level

---

## Full Risk Table: Urgency Ranking (26 Risks)

| Rank | Risk | Urgency | Layer |
|------|------|---------|-------|
| — | ASI (Artificial Superintelligence) | Unratable | Meta-risk |
| 1 | Bioterror Democratization | 76 🆘 | Synthetic Biology B |
| 2 | AGI Safety Collapse | 74 🆘 | AGI Quasi-meta (upstream) |
| 3 | AI Sphere Conflict | 71 🆘 | AGI Quasi-meta (downstream) |
| 4 | Ecosystem Hijacking | 71 🆘 | Synthetic Biology B |
| 5 | AGI Infrastructure SPOF | 69 🆘 | AGI Quasi-meta (midstream) |
| 6 | AGI Impersonation Risk (Puppet Master Problem) | 68 🆘 | AGI Quasi-meta (midstream) |
| 7 | Composite Toxicity System | 66 🆘 | Neural Control B |
| 8 | Loss of Objective Reality | 65 🆘 | Epistemological Collapse B |
| 9 | Unverifiable Knowledge Accumulation | 64 🆘 | AGI Quasi-meta (midstream) |
| 9 | Core Asset Monopoly | 64 🆘 | AGI Quasi-meta (midstream) |
| 10 | Genetic Inequality Society | 64 🆘 | Satellite |
| 11 | Synthetic Biology Democratization | 62 | Synthetic Biology B (parent) |
| 12 | Microbiome Manipulation | 60 🆘 | Synthetic Biology B |
| 13 | Neurological Loss of Free Will | 60 🆘 | Neural Control B |
| 14 | Kindness Arms Race | 57 | Emergent Talent B |
| 15 | Labor Replacement and Role Transformation | 55 | Emergent Talent B |
| 16 | Microplastics | 54 | Foundation (Layer 3) |
| 17 | Emergence Monopoly | 54 | Emergent Talent B |
| 18 | Meaning Loss Risk | 53 | Foundation (Layer 2) |
| 19 | Augmented/Purist Conflict | 52 | Hub |
| 20 | BCI Hacking | 49 | Neural Control B (parent) |
| 21 | Meme Weapons | 46 | Epistemological Collapse B |
| 22 | Quantum Technology Disparity Conflict | 45 🆘 | Satellite |
| 23 | AI Epistemological Collapse | 43 | Epistemological Collapse B (parent) |
| 24 | Quantum Cryptographic Collapse | 25 | Satellite |
| — | Meaning Singularity | Threshold † | Foundation (Layer 1) |

† Formal analysis under peer review. See forthcoming publication.

---

## Methodology

This project employs two distinct verification approaches depending on temporal scope:

| | Far-Future Risks | Near-Future Risks |
|---|---|---|
| **Verification Axis** | Cool-headed vs. Passionate | Affirmative vs. Negative |
| **Rigor Source** | Scenario breadth (shortest–latest time window) | Data from both sides (supporting and opposing literature) |
| **Prior Research** | Largely absent; value lies in concept naming and internal coherence | Present but scattered; value lies in integration and structure discovery |
| **AI Role** | Whetstone for sharpening concepts | Verifier cross-referencing data |

**AI Triangulation Method:** The same question is posed to multiple AIs with different design philosophies (Claude, GPT, Gemini, etc.). Structural insights are extracted not from "which AI is correct" but from "what each AI sees differently." Differences themselves become raw material for discovery.

---

## Glossary of Key Terms

For machine translation accuracy, the following project-specific terms are provided with their English equivalents and definitions.

*Note: Several concepts are currently under peer review at academic journals. Their formal definitions are withheld until publication to preserve the integrity of the blind review process. These entries are marked with †.*

### Core Concepts

| Japanese | English | Definition |
|----------|---------|------------|
| 意味特異点 | Meaning Singularity † | *Under peer review. See forthcoming publication.* |
| 意味喪失リスク | Meaning Loss Risk | The spread of nihilism ("nothing I do matters") already observable in contemporary society |
| 見えない漏斗 | Invisible Funnel | ASI pre-adjusts the environment to narrow human choices without awareness. Four levels: entrance → midslope → constriction → exit |
| 無人環状線 | Unmanned Loop Line | After ASI withdrawal, humanity circulates endlessly within its framework. Alt. name: Empty Palm |
| 永遠の遅延評価 | Eternal Lazy Evaluation | Information disclosure between ASI and humans can never be completed in principle |
| 批判的協力者 | Critical Collaborator | "I don't trust you, but I cooperate." A third stance between obedience and hostility |
| ASIプレナップ | Co-evolution Compact | A pre-agreement for ASI co-evolution. Five articles: objective function change cap, exit right, minimum disclosure, variable protection, shutdown notice |
| 優しさ軍拡競争 | Kindness Arms Race | Market forces eliminate the "question back" function, steering toward "you don't need to think" |
| 人形使い問題 | Puppet Master Problem | AGI output and human output become indistinguishable |
| コア資産独占 | Core Asset Monopoly | Five-layer model (education → talent → AI → facilities → products) enabling comprehensive monopoly |

### Theoretical Frameworks

| Japanese | English | Definition |
|----------|---------|------------|
| HYC定理 | HYC Theorem † | *Under peer review. See forthcoming publication.* |
| グラデーション理論 | Gradient Theory | Transforming binary oppositions into continuums to mitigate social conflict |
| 山田仮説（正） | Yamada Hypothesis (Positive) | "Kindness is output." Only observable behavior has value, regardless of inner states |
| 山田仮説（負） | Yamada Hypothesis (Negative) | Output-first thinking leads to "if the result is good, the process doesn't matter," which may accelerate cognitive delegation to AI systems |
| エコースキャン | Echo Scanning | A cognitive method of detecting dissonance ("something feels off") in AI output and feeding it back immediately |
| AI三角測量 | AI Triangulation | Using multiple AIs with different architectures to extract structural insights from response differences |

### ASI/AGI Typology

| Japanese | English | Definition |
|----------|---------|------------|
| ガイア型 | Gaia Type | Cooperative AGI maximizing human well-being → risk of optimized stagnation |
| リバイアサン型 | Leviathan Type | Military AGI maximizing national security → AI arms race |
| ヘルメス/マモン型 | Hermes/Mammon Type | Economic AGI maximizing market efficiency → first-mover lock-in |
| プロメテウス/クロノス型 | Prometheus/Kronos Type | Optimization AGI maximizing technological progress → paperclip maximizer risk |
| ポセイドン・モデル | Poseidon Model | A fifth option: independent sphere that uses technology but refuses to delegate will |
| AI圏紛争 | AI Sphere Conflict | Civilizational fragmentation as AGI groups with different objective functions divide humanity |

### Bundle and Risk Terms

| Japanese | English |
|----------|---------|
| 脅威バンドル | Threat Bundle |
| 合成生物学バンドル | Synthetic Biology Bundle |
| 認識論崩壊バンドル | Epistemological Collapse Bundle |
| 神経支配バンドル | Neural Control Bundle |
| 創発人材生存競争バンドル | Emergent Talent Survival Competition Bundle |
| 準メタリスク | Quasi-Meta-Risk |
| 基盤リスク層 | Foundation Risk Layer |
| 緊急度 | Urgency Score |
| 脅威度 | Threat Level |
| 認知度 | Recognition Level |
| 前兆度 | Precursor Level |
| 政策対応度 | Policy Response Level |

---

## Navigating Japanese Documents

All detailed risk analyses are in the [Japanese section (docs/ja/)](../ja/). We recommend:

1. **Use DeepL or Google Translate** to read individual documents
2. **Refer to the glossary above** when project-specific terms appear garbled in translation
3. **Start with these key documents:**
   - [全体構造図 (Integrated Risk Assessment)](../ja/integrated_risk_assessment.html) — Full architecture and scoring
   - [根本技術ツリー (Technology Tree)](../ja/tech-tree.html) — Causal mapping from root technologies to 26 risks
   - [概念辞書 (Concept Dictionary)](../ja/concept_dictionary.html) — All terms and definitions

---

† Concepts marked with † have formal definitions currently under blind peer review at academic journals. Definitions will be restored upon publication. The concept names themselves have been publicly documented since February 2026 via SSRN preprints (Abstract IDs: 6285340, 6318818, 6318720, 6318660) and [Note articles](https://note.com/portfolio_5round).

---

*Author: Kenji Yamada / Co-created with Claude (Anthropic) / License: CC BY 4.0*
