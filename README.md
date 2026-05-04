# Academic Research Workflow (学术研究全流程技能包)

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](SKILL.md)
[![Materials](https://img.shields.io/badge/distilled%20materials-33-green)]()
[![Disciplines](https://img.shields.io/badge/disciplines-10%2B-orange)]()
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

> A growable cognitive exoskeleton for humanities & social science research. Not a paper mill — a thinking scaffold that asks you the right questions at the right time.

一个可成长的社科人文研究认知外挂。它不替你写论文，但在你需要做判断的时候，基于 33 份权威学者材料，问你一系列正确的问题。

---

## What It Is (and Isn't)

| It IS | It is NOT |
|-------|-----------|
| A systematic diagnostic toolkit for your research | A paper generator — give it a topic, it won't spit out a paper |
| A growing knowledge base distilled from 33 authoritative sources | A one-size-fits-all template |
| A question-asking engine — you provide the answers | A replacement for your own thinking and disciplinary intuition |

Think of it as a senior mentor's external brain: it remembers the methodological essence of every important paper you've read; it gives you systematic checklists when you need to examine your own research; it helps you locate where you're stuck when you can't articulate the problem yourself.

---

## Architecture: 3 Layers, 4 Steps

```
          research-architecture (trunk — horizontal positioning)
          "Where am I stuck? Which stage?"
                         │
    ┌────────────────────┼────────────────────┐
    │                    │                    │
topic-problematization  research-execution  research-contribution
  (branch 1: anchoring) (branch 2: execution) (branch 3: convergence)
    "Is my topic good?" "Is my design sound?"  "Is my contribution real?"
                         │
          research-distiller (root — knowledge intake)
          "Extract the research framework from this paper"
```

| Sub-skill | Role | What it diagnoses |
|-----------|------|-------------------|
| `research-distiller` | Knowledge intake (root) | Extracts research frameworks from academic materials and feeds the shared knowledge base |
| `research-architecture` | Stage positioning (trunk) | Locates which of the 3 research stages you're stuck in |
| `topic-problematization` | Anchoring (branch 1) | 4-step topic diagnosis: origin → quality → defensibility → operationalization |
| `research-execution` | Execution (branch 2) | Full chain: theory derivation → literature dialogue → method justification |
| `research-contribution` | Convergence (branch 3) | 4-step contribution diagnosis: type → construction → Discussion writing → limitations |

**Design philosophy**: Knowledge grows (compendium accumulates), diagnostic standards stay stable (sub-skills only update when new materials genuinely expand the framework).

---

## Evidence Base: 33 Materials, 10+ Disciplines

Every diagnostic question and checklist item traces back to a specific scholar and publication. No generic advice.

### Foundation (5 sources)

| Source | Key insight |
|--------|-------------|
| **Li Huaizu** (XJTU) — Management methodology | "Hypothesis tree" concept; distinction between research logic and writing logic |
| **Lu Ming** (Fudan) — Public lecture | "The distance from topic to question"; writing IS research |
| **UW Writing Center** (2021) — "20 Tips" | Argument-driven structure; "jigsaw test" for structural coherence |
| **"Degree & Writing"** — 3-layer framework | "Closed-loop writing" — writing that can't close the loop signals research flaws |
| **Wang Fansen** (Academia Sinica) — Lecture | "Knowledge tree" metaphor; "A good topic is 70% of success" |

### Anchoring / Topic stage (9 sources)

| Source | Key insight |
|--------|-------------|
| **Zhao Dingxin** (UChicago/ZJU) — Sociology | "Difference-oriented questioning" — ask not "what is X?" but "why X and not Y?" |
| **Li Mianguan** (SYSU) — Public administration | Distinguishes "puzzles" (worth studying) from "difficulties" (operational obstacles) |
| **Alvesson & Sandberg** (2024, SAGE) | "Gap-spotting" vs. "problematization" — the latter challenges assumptions |
| **Zhong Kaikai** (PKU) — Doctoral thesis review (2014) | Complete 3-round topic iteration documented in first person |
| **Jin Dalu** (SASS) — Historical research (2024) | "Coordinated source clusters" and "topic coordinate method" (era × domain) |
| **Han Liang** — Top-100 doctoral thesis analysis | MIT's 7 thesis types; title-keyword-heading coherence test |
| **Yu Sumei** (NIES) — Sports science methodology | 6 topic pathologies; dual-step topic narrowing method |
| **Gerring & Seawright** (2022, CUP) — Political science | "Research sandbox" — topic selection as exploratory play, not one-shot decision |
| **NENU Journal Press** (2026) — Editorial studies | Institutional dimension of topic selection under impact-factor pressure |

### Execution / Design stage (8 sources)

| Source | Key insight |
|--------|-------------|
| **Sparrowe & Mayer** (2011, AMJ) | Hypothesis grounding: positioning → logic → coherence; draft without citations first |
| **Zhang Lianxiang** (Peking UP) | Operationalization triad: denominator → unit → boundary |
| **Causal inference primer** | Potential outcomes framework (Rubin Causal Model) |
| **Tang Lingfeng** (ScienceNet) | 8-question literature dialogue model |
| **Li Xu & Chen Lihong** (BJTU, 2023) | Literature reading layers: search → skim → deep read; 92%+ of grad students spend >50% time reading |
| **Teresa Chan** (McMaster) — Health education | "Throughline" concept — RQ → epistemology → methodology → method → results must align |
| **Xu Zhili & Xu Ge** (Beihang, 2021) | Mixed methods: 3 justification logics (pragmatist / dialectical / complexity) |
| **Univ. of Melbourne** Academic Skills | Method selection 5-point self-check |

### Convergence / Contribution stage (8 sources)

| Source | Key insight |
|--------|-------------|
| **Gruber et al.** (2021, AMJ) | Dual contribution standard: theoretical advancement + real-world impact |
| **Ravasi et al.** (2025, AMJ) | 6-path contribution construction framework with failure modes |
| **Geletkanycz & Tepper** (2012, AMJ) | Discussion as "ending + new beginning"; 3 traps (rehash / wander / overreach) |
| **AOM Editors** (2021, AMD) | 6 journals × 6 contribution types matrix |
| **Ross & Bibler Zaidi** (2019) — Medical education | 4-element limitations framework; counterintuitive: good limitations writing increases acceptance |
| **AJE** (2023) | 5-category limitations taxonomy; independently consistent with Ross & Zaidi |
| **USC Library** — Discussion guide | Inverted pyramid structure; 7-segment organization |
| **USC Library** — Conclusion guide | Hourglass structure; "new insights, not new information" |

### Empirical validation (3 sources)

3 papers from *Management World* and *Nankai Business Review* (China's top management journals) validate the 3-layer architecture across qualitative single-case, qualitative dual-case, and quantitative experimental designs.

---

## Quick Start

### Prerequisites

This is a [Claude Code](https://claude.ai/code) skill. Install it by copying to your skills directory:

```bash
# Clone or copy to your Claude Code skills directory
cp -r academic-research-workflow ~/.agents/skills/
```

### First-time usage flow

1. **Have materials to analyze?** → Say "蒸馏这篇材料" or "Extract the research framework from this paper"
2. **Stuck on your topic?** → Say "帮我看看我的选题" — goes through a 4-step diagnosis
3. **Topic set, need research design?** → Say "我有了研究问题，接下来怎么设计研究"
4. **Not sure your contribution is strong enough?** → Say "帮我看看我的论文贡献"
5. **Don't know where you're stuck?** → Say "我改不下去了，帮我看看到底哪出问题了" — architecture locates your stage first, then hands off to the right sub-skill

### Key constraints

- All diagnostic guidance must be traceable to a distilled source
- No unsourced universal assertions
- Declare distillation intent before any analysis (Step 0)
- Specific problem, specific analysis — no fixed templates

---

## File Structure

```
academic-research-workflow/
├── SKILL.md              # Skill definition & metadata
├── README.md             # This file
├── LICENSE               # MIT License
├── compendium.md         # Unified knowledge base (grows with new distillations)
├── memory.md             # Skill memory & state
└── sub-skills/
    ├── research-distiller/
    │   └── SKILL.md
    ├── research-architecture/
    │   └── SKILL.md
    ├── topic-problematization/
    │   └── SKILL.md
    ├── research-execution/
    │   └── SKILL.md
    └── research-contribution/
        └── SKILL.md
```

---

## Growth Model

- **Knowledge base (compendium.md)** grows automatically with each new distillation — organized under 5 stable chapters: Foundation → Anchoring → Execution → Convergence → Appendix
- **Diagnostic sub-skills** update only when new materials provide genuinely novel logic not covered by the existing framework. At least 3 materials in a direction are needed before considering an update. Coherence and explanatory power are the only criteria — novelty alone is not enough.

---

## Limitations (Transparency)

- **Literature dialogue materials are the thinnest** (2 sources) — this is the weakest link in the evidence base
- **Qualitative methodology guidance is thinner than quantitative** — mixed methods and qualitative sources come from review articles rather than primary methodological research
- **Not a substitute for a mentor** — it doesn't know your field's frontier dynamics or your academic community's norms
- **Not a substitute for thinking** — the ability to find conceptual connections, judge what's worth studying, and discover innovation at disciplinary intersections remains in your brain

---

## Version

- **Version**: 1.0.0
- **Distilled materials**: 33
- **Disciplines covered**: 10+
- **Sub-skills**: 5 (1 distiller + 1 architecture map + 3 stage diagnostics)

---

## License

MIT
