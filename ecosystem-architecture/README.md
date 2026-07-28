# HCOS™ Ecosystem Architecture

**Document Type:** Repository Architecture  
**Status:** Draft  
**Version:** 1.0.0  
**Last Updated:** July 2026  

---

## Purpose

The Human-Centered Operating Systems™ ecosystem includes multiple repositories that support the development, stewardship, application, and continued improvement of the HCOS™ framework.

Each repository has a distinct purpose, but the repositories are intended to function as a connected system.

This architecture organizes the HCOS ecosystem into four primary layers:

1. Foundations
2. Governance
3. Knowledge
4. Applications

A proposed fifth repository category, Implementations, supports complete real-world application packages that combine resources from across the ecosystem.

---

## Architectural Overview

```text
Layer 1 — Foundations
        ↓
Layer 2 — Governance
        ↓
Layer 3 — Knowledge
        ↓
Layer 4 — Applications
        ↓
End-to-End Implementations
```

The layers are connected rather than isolated.

Foundations explain why HCOS exists.

Governance establishes how HCOS is stewarded.

Knowledge develops what HCOS understands.

Applications translate that knowledge into usable resources.

Implementations bring multiple resources together to address specific real-world needs.

---

# Layer 1 — Foundations

## Why HCOS Exists

The Foundations layer contains the enduring philosophy, principles, commitments, and constitutional direction of HCOS.

### Repositories

- `hcos-foundations`
- `hcos-constitution`

### Primary Functions

These repositories define:

- the purpose of HCOS
- its foundational principles
- its commitments to human dignity
- its understanding of organizations as human systems
- its long-term philosophical direction
- the boundaries that should remain stable as the framework evolves

### Guiding Question

> Why does HCOS exist, and what principles should guide everything developed within it?

Changes within this layer should be approached carefully because they may affect every other part of the ecosystem.

---

# Layer 2 — Governance

## How HCOS Is Managed

The Governance layer establishes how HCOS documents, knowledge, standards, releases, and repositories are reviewed and maintained.

### Repositories

- `hcos-governance`
- `hcos-knowledge-governance`
- `hcos-standards`

### Primary Functions

These repositories define:

- document lifecycle requirements
- review expectations
- validation practices
- naming conventions
- versioning
- changelog requirements
- Git tagging
- GitHub Releases
- knowledge stewardship
- standards development
- repository consistency
- contributor expectations
- disclosure of limitations and validation status

### Guiding Question

> How should HCOS be developed, reviewed, validated, maintained, and improved responsibly?

The Governance layer helps preserve transparency, accountability, consistency, and traceability as HCOS grows.

---

# Layer 3 — Knowledge

## What HCOS Knows

The Knowledge layer contains the disciplines, models, methods, architectures, educational content, and domain-specific understanding developed through the HCOS framework.

### Repositories

- `hcos-disciplines`
- `hcos-models`
- `hcos-methods`
- `hcos-architectures`
- `hcos-ai`
- `hcos-healthcare`
- `hcos-learning`
- `hcos-insights`

### Primary Functions

These repositories contain:

- formal areas of HCOS study
- conceptual models
- analytical methods
- systems architectures
- human-centered AI guidance
- healthcare-specific applications
- educational materials
- courses and learning resources
- interpretations of real-world events
- emerging insights
- cross-disciplinary knowledge

### Guiding Question

> What has HCOS learned about people, organizations, technology, healthcare, leadership, and systems?

The Knowledge layer should remain connected to evidence, experience, validation, and continued learning.

---

## Knowledge Repository Roles

### `hcos-disciplines`

Defines formal areas of HCOS inquiry and practice.

Examples may include:

- human systems
- human-centered AI
- healthcare systems
- human load protection

### `hcos-models`

Contains conceptual models that help people understand patterns, relationships, pressures, protections, and system behavior.

### `hcos-methods`

Contains repeatable approaches for examining, evaluating, or improving human systems.

### `hcos-architectures`

Contains structural and technical models showing how system components may be organized or connected.

### `hcos-ai`

Contains HCOS guidance, analysis, and resources related to artificial intelligence and human-AI stewardship.

### `hcos-healthcare`

Contains healthcare-specific applications involving clinical work, operations, patient care, pharmacy, workforce experience, and system improvement.

### `hcos-learning`

Contains educational materials, courses, workshops, and learning resources that teach HCOS principles and applications.

### `hcos-insights`

Applies the HCOS framework to real-world events, emerging concerns, organizational patterns, leadership questions, and system behavior.

---

# Layer 4 — Applications

## How HCOS Is Used

The Applications layer contains the user-facing resources through which people and organizations can apply HCOS principles in practice.

### Repositories

- `hcos-tools`
- `hcos-platform`
- `hcos-website`
- `hcos-community`

### Primary Functions

These repositories provide:

- prompts
- instruments
- assessments
- templates
- checklists
- practical guides
- decision-support resources
- digital tools
- public educational content
- collaboration spaces
- opportunities for participation and contribution

### Guiding Question

> How can people use HCOS to understand and improve real-world systems?

The Applications layer translates HCOS knowledge into practical resources without replacing the foundations, standards, or evidence that support them.

---

## Application Repository Roles

### `hcos-tools`

A reusable library of individual HCOS resources.

Examples include:

- prompts
- checklists
- assessments
- templates
- review guides
- interview tools
- communication tools
- workflow instruments

A tool should generally serve a focused purpose and be usable independently or as part of a broader implementation.

### `hcos-platform`

Contains the technical platform through which HCOS principles, knowledge, models, and decision-support capabilities may be operationalized.

### `hcos-website`

Contains public-facing content, graphics, documentation, and resources that communicate the HCOS framework.

### `hcos-community`

Supports contributors, educators, practitioners, researchers, organizations, and other participants working to responsibly develop and apply HCOS.

---

# Proposed Implementation Repository

## How HCOS Components Work Together

As the HCOS ecosystem grows, a dedicated implementation repository may help demonstrate how resources from multiple repositories can be combined into complete solutions.

### Proposed Repository

```text
hcos-implementations
```

### Recommended Purpose

The `hcos-implementations` repository would contain complete, end-to-end application packages developed for a defined audience, setting, or system need.

An implementation may combine:

- foundations
- standards
- prompts
- instruments
- assessments
- templates
- examples
- educational guidance
- workflow instructions
- validation documentation
- implementation notes
- known limitations

### Guiding Question

> How can multiple HCOS resources work together to address a specific real-world need?

---

## Proposed Structure

```text
hcos-implementations/
├── README.md
│
├── resume-system/
│   ├── README.md
│   ├── implementation-guide/
│   ├── prompts/
│   ├── templates/
│   ├── examples/
│   ├── validation/
│   └── CHANGELOG.md
│
├── ai-governance-system/
│   ├── README.md
│   ├── implementation-guide/
│   ├── standards-map/
│   ├── assessments/
│   ├── templates/
│   ├── validation/
│   └── CHANGELOG.md
│
├── healthcare-ai-readiness/
│   ├── README.md
│   ├── implementation-guide/
│   ├── assessments/
│   ├── education/
│   ├── templates/
│   ├── validation/
│   └── CHANGELOG.md
│
├── pharmacy-operations/
├── organizational-assessment/
└── leadership-development/
```

---

# Tools and Implementations

The distinction between `hcos-tools` and `hcos-implementations` is important.

## Tools

A tool is a reusable building block.

Examples include:

- a resume prompt
- a review checklist
- a readiness assessment
- a communication template
- an interview guide
- a workflow evaluation instrument

Tools may be used independently.

## Implementations

An implementation is a coordinated package designed to address a broader use case.

For example, a resume implementation might include:

- the HCOS Hybrid Resume Prompt
- an ATS optimization guide
- a resume review checklist
- templates
- examples
- validation guidance
- implementation instructions
- known limitations

The implementation shows how the individual tools work together.

---

## Practical Distinction

```text
hcos-tools
Reusable components

hcos-implementations
Complete application packages
```

The tools repository answers:

> What individual resource can someone use?

The implementations repository answers:

> How should several resources be combined to support a complete process?

---

# How the Layers Work Together

A single HCOS implementation may draw from every architectural layer.

For example:

```text
Human Dignity Foundation
        ↓
Professional Documentation Standard
        ↓
Systems Thinking and Communication Knowledge
        ↓
Hybrid Resume Prompt and Review Checklist
        ↓
Complete Resume Development Implementation
```

Each layer contributes something different:

| Layer | Contribution |
|---|---|
| Foundations | Establishes the underlying purpose and principles |
| Governance | Defines review, validation, versioning, and stewardship |
| Knowledge | Provides the relevant concepts, methods, and subject matter |
| Applications | Provides usable tools and public resources |
| Implementations | Combines resources into an end-to-end solution |

---

# Repository Placement Principles

When deciding where a new HCOS document belongs, consider the following questions.

## Place it in Foundations when:

- it defines an enduring HCOS principle
- it explains why HCOS exists
- it establishes a core philosophical commitment
- it should guide many areas of the framework

## Place it in Governance when:

- it defines how HCOS is managed
- it establishes review or validation expectations
- it addresses versioning, releases, repositories, or documentation
- it governs knowledge stewardship or contributor processes

## Place it in Knowledge when:

- it develops a concept, model, method, discipline, or architecture
- it explains what HCOS understands about a subject
- it provides education or domain-specific interpretation
- it applies HCOS thinking to an emerging issue

## Place it in Applications when:

- it is a practical resource someone can directly use
- it is a prompt, instrument, checklist, assessment, or template
- it supports communication, decision-making, evaluation, or action
- it provides a public or technical interface to HCOS

## Place it in Implementations when:

- it combines several HCOS resources
- it supports an end-to-end use case
- it includes practical implementation guidance
- it is designed for a particular audience, organization, or setting
- it requires coordinated tools, standards, examples, and validation

---

# Evidence-Based Improvement

Every layer of the HCOS ecosystem should remain open to responsible improvement.

Evidence may come from:

- user experience
- implementation feedback
- subject matter review
- professional practice
- published research
- usability testing
- technical testing
- validation activities
- observed limitations
- unintended consequences

Evidence-based improvement does not require claiming that every HCOS resource has been formally validated.

Instead, HCOS should clearly distinguish among:

- conceptual development
- internal review
- expert review
- field testing
- preliminary validation
- external validation
- formal research evidence

The validation status of each resource should be stated honestly.

---

# Architectural Stewardship

Repository boundaries should support understanding rather than create unnecessary fragmentation.

Before creating a new repository, consider:

1. Whether the content fits within an existing repository.
2. Whether it has a distinct and durable purpose.
3. Whether it will contain enough material to justify independent stewardship.
4. Whether contributors will understand how it relates to the rest of HCOS.
5. Whether a folder within an existing repository would be simpler.
6. Whether the new repository reduces or increases duplication.

A repository should be created because it improves clarity and stewardship—not simply because a new topic has emerged.

---

# Related Repositories

This document provides an architectural overview of the HCOS ecosystem.

Repository-specific instructions should remain within their respective repositories.

Related governance documents may include:

- HCOS Release Process
- HCOS Versioning Standard
- HCOS Review Standard
- HCOS Changelog Guidelines
- HCOS Repository Naming Standard
- HCOS Document Lifecycle
- HCOS Validation Guidance

---

# Guiding Principle

The HCOS repositories should function as parts of one human-centered knowledge system.

Foundations preserve purpose.

Governance protects integrity.

Knowledge develops understanding.

Applications make that understanding usable.

Implementations bring the pieces together to help people address real-world needs.

The goal is not to create more repositories.

The goal is to create a coherent, transparent, and continuously improving ecosystem that helps people build healthier organizations and healthier systems.

