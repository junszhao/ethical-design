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

The CHAI framework distinguishes four types of agency, drawn from Bandura's social cognitive theory. These function as **reasoning lenses** — they prompt you to consider how agency is distributed across different stakeholders in your system.


<figure align="center">
  <img src="/images/four_types_of_agency.png" alt="Four types of agency used in the CHAI framework as reasoning lenses." width="60%">
  <figcaption>Fig. 1: Four types of agency used in the CHAI framework. The visual abstractions represent different loci of action, control, and coordination across key stakeholders in each agency type.</figcaption>
</figure>


**Three levels of agency** (low, medium, high) describe the degree of children's involvement, expressed from the child's point of view. Importantly, higher is not always better — trade-offs are inherent and children's best interests should guide decisions.

<figure align="center">
  <img src="/images/three_levels_of_agency.png" alt="Three levels of agency used in the CHAI framework as reasoning lenses." width="70%">
  <figcaption>Fig. 2: Three levels of agency. The levels capture differences in children's involvement in initiating actions, influencing decisions, and shaping outcomes, as well as how these processes are mediated by other stakeholders and the AI system.</figcaption>
</figure>

### The Four-Stage Reasoning Process

![The four-stage reasoning process of the CHAI framework, showing how designers’ reasoning about children’s agency is transformed from an initial design context into explicit agency design through assessment, mapping, application, and reflection. The process produces intermediate reasoning artefacts and allows iteration among later stages.](/images/four_stages.png)
*Fig. 3: The four-stage reasoning process of the CHAI framework, showing how designers’ reasoning about children’s agency is transformed from an initial design context into explicit agency design through assessment, mapping, application, and reflection. The process produces intermediate reasoning artefacts and allows iteration among later stages.*


## What's in This Repository

```
├── case_studies/                               # Worked examples from participatory design workshops
│   ├── case study 0/                           # Pilot study outputs (2 workshop board images)
│   ├── case study 1/                           # Workshop session 1 outputs (3 PDFs)
│   ├── case study 2/                           # Workshop session 2 outputs (3 PDFs)
│   └── case study 3/                           # Workshop session 3 outputs (3 PDFs)
├── docs/                                       # Project documentation and usage guidance
│   ├── INSTRUCTION.md                          # How to apply the CHAI framework step-by-step
│   └── Designing for Children's Agency Report.md
├── images/                                     # Framework figures used in this README
│   ├── four_stages.png
│   ├── four_types_of_agency.png
│   └── three_levels_of_agency.png
├── workshop_material/                          # Participatory workshop templates and examples
│   ├── Design for Agency Workshop - Example.pdf
│   ├── Design for Agency Workshop - Stage 1.pdf
│   ├── Design for Agency Workshop - Stage 2.pdf
│   ├── Design for Agency Workshop - Stage 3.pdf
│   ├── Design for Agency Workshop - Stage 4.pdf
│   └── questionnaire/
│       ├── Pre-Questionnaire.pdf
│       └── Post-Questionnaire.pdf
└── README.md
```

## Getting Started

Please read `INSTRUCTION.md` in `docs/`.

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

## Contact

- **Oxford Child-Centred AI Design Lab** — [oxfordccai.org](https://oxfordccai.org/)
- **Dr. Boyin Yang**: boyin.yang@cs.ox.ac.uk 
- **Dr. Jun Zhao**: jun.zhao@cs.ox.ac.uk

---

*Every child deserves technology that respects their agency, protects their wellbeing, and amplifies their voice.*
