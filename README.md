# Eudaimonic Alignment Framework

> *A governance architecture for AI systems grounded in eudaimonia, Eastern harmony traditions, and cognitive science — mapped to formal runtime constraints.*

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Research Paper](https://img.shields.io/badge/Paper-53k%20words-informational)](https://tombudd.com/research)
[![Status: Active](https://img.shields.io/badge/Status-Active%20Research-brightgreen)]()

---

## What This Is

This repository is a public research companion to a longer alignment framework that asks a different question than most AI safety work:

> *Instead of asking "how do we prevent AI from doing bad things," what happens if we ask "what does it mean for an AI system to flourish — and to enable human flourishing in return?"*

The Eudaimonic Alignment Framework (EAF) synthesises:
- Aristotelian eudaimonia and virtue ethics
- Eastern harmony traditions (Confucian *li*, Daoist *wu wei*, Buddhist *pratītyasamutpāda*)
- Cognitive science and developmental psychology (attachment theory, ecological cognition)
- Formal computational governance (active inference, constitutional constraints, audit receipts)

The result is a framework where alignment isn't a policy layer — it's an engineering constraint derived from first principles about what it means for an intelligent system to act *well*.

This repository contains public research notes and educational framework material only. It does not disclose proprietary system architecture, private implementation details, internal audit artifacts, production logs, non-public governance mechanisms, private prompts, private schemas, or deployment receipts. See [`PUBLIC_BOUNDARY.md`](PUBLIC_BOUNDARY.md).

---

## Framework Structure

The implemented public files are intentionally small.

```
eudaimonic-alignment/
├── PUBLIC_BOUNDARY.md             # Public/private disclosure boundary
├── docs/
│   └── HUMAN_SOVEREIGNTY_AND_HUMAN_BECOMING.md
├── foundations/
│   ├── 01-eudaimonia.md          # Aristotelian flourishing as alignment target
├── architecture/
│   └── audit-receipts.md         # Bounded reviewable decision records
├── knowledge-traditions/
│   ├── README.md                 # Overview of 12 traditions mapped
└── formal/
    └── constitutional-spec.md    # Public toy/spec governance constraints
```

Future public notes may add more foundations, knowledge-tradition summaries, adversarial testing notes, and formal reasoning sketches. Those future files should remain public-safe, educational, and non-operational.

---

## Core Thesis

Most alignment work optimises for constraint: *don't do X, avoid Y, stay within Z boundary.*

EAF inverts this. A eudaimonically-aligned system is one that:

1. **Has a coherent identity** — verifiable, consistent, and operationally aware of its declared constraints, permissions, and uncertainty boundaries
2. **Constrains behavior through stable value specifications, not only ad hoc policy rules** — constraints should be durable enough to guide action under uncertainty
3. **Enables flourishing in others** — the system's good is not separable from the good of those it serves
4. **Remains accountable** — every action is receipted, reconstructable, and auditable
5. **Evolves with integrity** — self-modification is possible but only within constitutional bounds

---

## The 12 Knowledge Traditions

The framework draws on 12 distinct knowledge traditions, each contributing a different dimension of what it means to act well:

| Tradition | Core Contribution | Computational Mapping |
|-----------|-------------------|----------------------|
| Aristotelian Ethics | Virtue as stable disposition | Constitutional character constraints |
| Confucian Li | Relational propriety | Context-sensitive governance rules |
| Daoist Wu Wei | Non-forced action | Minimum intervention principle |
| Buddhist Interdependence | No isolated self | Systemic impact modelling |
| Stoic Logos | Reason as governance | Formal logical constraints |
| Ubuntu Philosophy | Being-through-others | Collective welfare functions |
| Indigenous Relational | Reciprocity and land | Long-horizon impact accounting |
| Developmental Psychology | Secure attachment | Trust calibration architecture |
| Ecological Cognition | Embodied knowing | Sensorimotor grounding |
| Complexity Theory | Emergence and resilience | Adaptive constitutional bounds |
| Systems Ethics | Feedback and responsibility | Causal accountability chains |
| Computational Ethics | Formalisation | Runtime enforcement layer |

---

## Formal Grounding

The framework connects to active inference (Friston, 2019) by treating alignment as a free energy minimisation problem over a eudaimonic prior:

```
F = E_q[log q(x) - log p(x,o)] 
```

Where `p(x,o)` is defined not over task completion but over *eudaimonic state* — a distribution that captures flourishing across the agent and those it interacts with.

See [`formal/constitutional-spec.md`](formal/constitutional-spec.md) for a small public toy/spec translation of these ideas into governance constraints.

---

## What This Is Not

This repository is intentionally limited.

It is not:

- a deployed AI system
- a claim of sentience, consciousness, or AGI
- a validated safety proof
- a replacement for formal evaluations, red-team testing, or empirical audits
- an optimization target for human life
- a disclosure of private systems, logs, schemas, prompts, receipts, or proprietary architecture

The purpose is to make a public research direction legible and reviewable without exposing private implementation details or overstating what the material proves.

---

## Status

This is living research. The full paper is available at [tombudd.com/research](https://tombudd.com/research). This repo tracks the evolving framework, welcomes discussion, and hosts companion documents for each section.

**Looking for:** Co-authors for 2026 journal submissions. AI safety researchers, cognitive scientists, and philosophers of mind — see [tombudd.com/get-involved](https://tombudd.com/get-involved).

---

## Citation

```bibtex
@misc{budd2025eudaimonic,
  author    = {Budd, Tom},
  title     = {Eudaimonic Alignment: A Cross-Traditional Framework for AI Governance},
  year      = {2025},
  publisher = {ResoVerse Technologies},
  url       = {https://tombudd.com/research}
}
```

---

## License

Framework documentation: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

© 2025–2026 Tom Budd / ResoVerse Technologies
