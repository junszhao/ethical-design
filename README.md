# Designing for Children's Agency in AI

**Open-source resources for building child-centred AI systems that respect children's agency, protect their wellbeing, and amplify their voice.**

From the [Oxford Child-Centred AI (OxfordCCAI) Design Lab](https://oxfordccai.org/) · Department of Computer Science, University of Oxford

---

## What Is This?

This repository provides practical resources for anyone designing, building, or evaluating AI systems that children interact with. At its core is the **CHAI (Designing for Children's Agency in AI) framework** — a conceptual framework that helps design teams reason explicitly about children's agency during the design process.

**Agency** — the ability to make meaningful choices, act with intention, and influence one's own experiences — is foundational to children's development. Yet in practice, it is rarely considered systematically when designing AI systems for children. Design teams tend to rely on implicit judgements, focus narrowly on safety, or treat agency as an abstract principle rather than something that can be mapped onto concrete system functions.

The CHAI framework addresses this gap. Rather than prescribing specific design solutions, it provides a structured way to surface assumptions, articulate trade-offs, and connect values to design decisions.

## Who Is This For?

| Audience | How this helps |
|---|---|
| **Designers & developers** building AI products for or used by children | A step-by-step reasoning process for embedding agency considerations into your design workflow |
| **Researchers** in child–computer interaction, AI ethics, or participatory design | A conceptual framework with empirical grounding, plus workshop materials for running your own studies |
| **Educators** teaching ethical design, HCI, or responsible AI | Ready-to-use workshop structures and case study material for classroom and studio settings |
| **Policy & advocacy professionals** working on children's digital rights | An evidence-based perspective on what "designing for agency" means in practice |

## The CHAI Framework

### Core Concepts

The framework is built around two sets of reasoning lenses and a four-stage process.

**Four types of agency** — drawn from Bandura's social cognitive theory — prompt designers to consider how agency is distributed across stakeholders:

- **Individual agency** — the child acts and chooses independently within the system
- **Co-agency** — control and influence are shared between the child and others (parent, peer, teacher)
- **Proxy agency** — others act on the child's behalf, while the child's voice should remain represented
- **Collective agency** — children act together with peers or communities to influence shared outcomes

**Three levels of agency** (low, medium, high) describe the degree of children's involvement, expressed from the child's point of view. Importantly, higher is not always better — trade-offs are inherent and children's best interests should guide decisions.

### The Four-Stage Reasoning Process

| Stage | What happens | Output |
|---|---|---|
| **1. Assessment** | Articulate agency-related design goals. Clarify which forms of agency are valued, for whom, and why. | Shared understanding of agency intent |
| **2. Mapping** | Link agency types and levels to concrete system components using the agency mapping matrix. | Agency priority map |
| **3. Application** | Select consequential system functions and explore redesigns to better support target agency levels. | Redesign proposals with trade-off analysis |
| **4. Reflection** | Examine how reasoning evolved. Surface tensions, constraints, and next steps. | Design brief for implementation |

## What's in This Repository

```
├── case_studies/                          # Worked examples from participatory design workshops
│   ├── case study 0/                      # Pilot study (workshop board images)
│   ├── case study 1/                      # Workshop session 1 (3 workshop PDFs)
│   ├── case study 2/                      # Workshop session 2 (3 workshop PDFs)
│   └── case study 3/                      # Workshop session 3 (3 workshop PDFs)
├── docs/                                  # Project documentation
│   └── Designing for Children's Agency Report.md
├── workshop_material/                     # Participatory workshop materials
│   ├── Design for Agency Workshop - Example.pdf
│   ├── Design for Agency Workshop - Stage 1.pdf
│   ├── Design for Agency Workshop - Stage 2.pdf
│   ├── Design for Agency Workshop - Stage 3.pdf
│   └── Design for Agency Workshop - Stage 4.pdf
└── README.md
```

> **Note:** This repository is actively being developed. Some directories may be added or restructured as we release additional materials. Watch or star the repo to stay updated.

## Getting Started

### If you're a design team

1. **Read the framework overview** in `framework/` to understand the four agency types and three levels
2. **Download the mapping matrix** template — this is the hands-on tool you'll use in design sessions
3. **Run a workshop** using the facilitator guide in `workshops/` (60–90 minutes, works remotely via any whiteboard tool)
4. **Review case studies** to see how other teams navigated agency trade-offs

### If you're a researcher

1. Start with the framework documentation for the conceptual grounding
2. The workshop materials include the full study protocol, questionnaires, and Figma board templates used in our participatory workshops
3. Adapt and extend for your own research context

### If you're an educator

1. The workshop structure is designed for small teams (2–4 people) and works well in studio or seminar settings
2. Case studies provide ready-made discussion material
3. The pre/post questionnaires can support assessment

## What We Found

We ran participatory workshops with four design teams (nine designers) building child–AI systems. Key findings:

- **Agency is rarely explicit.** Before using the framework, designers almost never articulated children's agency as a distinct design concern — it was implicit in safety or functionality choices, or absent entirely.
- **The framework surfaces misalignments.** Teams discovered that their designs contradicted their stated values — e.g., limiting child interaction "for safety" while claiming to support children's voice.
- **Complexity is productive.** Designers reported the process was "more complicated" but valued this as deeper engagement with real trade-offs, describing the framework as "positive constraints" on design thinking.
- **Operationalisation remains hard.** Conceptual understanding grew faster than the ability to translate it into concrete features — an area for future tool development.

## Partners & Collaborators

This work is developed in collaboration with:

- [LEGO Group](https://www.lego.com/en-gb/aboutus/lego-group?locale=en-gb)
- [FAM Studio](https://famstudio.co/)
- [CHAILD Project](https://oxfordccai.org/) (UKRI-funded, Children's Agency in the Age of AI)

## Contributing

We welcome contributions from researchers, designers, and practitioners. You can:

- **Share case studies** of agency-related design decisions in child–AI systems
- **Translate materials** into other languages
- **Report issues** or suggest improvements via [GitHub Issues](../../issues)
- **Adapt and extend** the framework for new contexts (and let us know how it went)

## Citation

If you use the CHAI framework or workshop materials in your work, please cite:

```
@article{yang2026exploring,
  title={Exploring a Design Framework for Children's Agency through Participatory Design},
  author={Yang, Boyin and Zhao, Jun},
  year={2026},
  note={Under review}
}
```

## Licence

This work is openly available for research and educational use. See [LICENSE](LICENSE) for details.

## Contact

- **Oxford Child-Centred AI Design Lab** — [oxfordccai.org](https://oxfordccai.org/)
- **Dr. Boyin Yang**: boyin.yang@cs.ox.ac.uk 
- **Dr. Jun Zhao**: jun.zhao@cs.ox.ac.uk

---

*Every child deserves technology that respects their agency, protects their wellbeing, and amplifies their voice.*