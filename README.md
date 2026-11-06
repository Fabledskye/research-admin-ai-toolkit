# From Prompts to Professional AI Agents

### A Research Administrator's AI Toolkit

**Practical resources for building responsible, transparent, and reusable AI-supported workflows in research administration.**

Welcome! This repository grew out of a series of experiments at California State University Channel Islands exploring how artificial intelligence could support the professional work of research administration.

What began as a simple effort to make award agreement reviews more efficient gradually evolved into documented workflows, structured information practices, and specialized AI agents.

Along the way, an important lesson emerged:

**You don't need to begin with programming. Begin with a professional problem you already understand.**

This repository shares the methods, examples, and agent specifications developed through that process so other research administrators can explore, adapt, test, and improve them within their own institutional environments.

---

## The Philosophy: Professional Expertise Comes First

Research administrators already possess many of the skills needed to design effective AI-supported workflows.

We establish procedures, interpret policies, evaluate evidence, manage competing information sources, identify exceptions, and communicate complex requirements to different audiences.

Those skills provide a powerful foundation for working with AI.

Our approach draws on three complementary disciplines:

* **Information and library science:** Information-seeking behavior, authoritative sources, provenance, citations, uncertainty, and verification.
* **Management and procedural development:** Defining expectations, establishing boundaries, evaluating results, and improving repeatable processes.
* **Software development principles:** Prototyping, testing, identifying failures, documenting changes, and iterating toward more reliable outcomes.

The objective is not to remove human expertise from professional work.

It is to make that expertise more explicit, reusable, and effective.

## From Prompts to Workflows to Agents

The development process presented here follows three broad stages.

### 1. Prompt: Explore a Professional Task

Begin with a narrow question or recurring activity.

For example: Can AI help identify reporting requirements, special conditions, and administrative obligations within an award agreement?

At this stage, experimentation helps reveal both useful capabilities and important limitations.

### 2. Workflow: Make the Process Repeatable

Once an interaction becomes useful, begin documenting the expectations that made it successful.

These may include:

* Which documents are authoritative.
* How information should be extracted and organized.
* What citation structure should be used.
* How missing or conflicting information should be handled.
* When clarification or human review is required.
* What the intended audience actually needs.

A documented workflow reduces the need to reconstruct instructions for every new task.

### 3. Agent: Give the Workflow a Dedicated Architecture

A specialized AI agent combines a defined professional purpose with instructions, knowledge sources, boundaries, expected outputs, and human oversight.

We use the term **agent seed** to describe a reusable specification of those professional expectations.

An agent seed is not the underlying language model. It is a documented framework intended to guide how a model supports a particular professional workflow.

Agent behavior may vary across platforms, models, and configurations. Every implementation requires testing and adaptation.

---

## Meet the Agents

### Penny — Award Setup and Interpretation

Penny grew out of a manual award setup process that used a Principal Investigator Checklist to organize information for award acceptance and handoff.

Her development focused on extracting and organizing award requirements, identifying authoritative documents, providing verifiable citations, distinguishing documented facts from interpretations, and flagging missing or conflicting information.

Penny's comprehensive outputs support human review. The research administrator remains responsible for verification, institutional decisions, and selecting what should be communicated to principal investigators and post-award colleagues.

### Scout — Pre-Award Review

Scout applies related information-literacy and workflow-design principles to pre-award activities, including reviewing funding solicitations and identifying requirements relevant to proposal readiness.

Although Scout and Penny support different professional activities, they demonstrate how common architectural principles can be adapted to different tasks.

**These agents are educational examples, not institutionally approved universal solutions.** Their specifications should be reviewed and modified before use in another environment.

---

## A Foundational Discovery: Not Knowing Is Acceptable

One of the earliest lessons from these experiments was that AI systems can generate plausible answers even when the available evidence is insufficient.

The workflow changed when missing information became an explicitly acceptable outcome.

Rather than requiring an answer to every question, we began distinguishing among information that was:

* Directly documented in the supplied materials.
* Interpreted from available evidence.
* Absent from the reviewed documents.
* Dependent on internal institutional records.

We also developed citation requirements so a human reviewer could locate and verify the source of a finding.

**Attribution and citations make information easier to examine. They do not independently establish that the information is correct.**

Human verification remains essential.

## Human Judgment Is Part of the Workflow

A comprehensive extraction is not necessarily an effective professional communication.

An AI system may identify dozens of relevant award provisions. A principal investigator, however, may only need a concise explanation of immediate responsibilities, important deadlines, and conditions affecting project implementation.

The human reviewer determines what is accurate, relevant, actionable, and appropriate for the intended audience.

This includes deciding what to omit, what to investigate further, and what requires institutional approval.

AI can support professional judgment. It does not replace institutional authority or accountability.

---

## Getting Started

You don't need to build an agent immediately.

Start with one manageable, recurring task.

1. **Identify the process.** Choose work you already understand and can evaluate.
2. **Define the information environment.** Establish authoritative sources and permitted data.
3. **Document expectations.** Describe successful outputs, citation requirements, uncertainty handling, and boundaries.
4. **Test and evaluate.** Compare results against source documents and established professional standards.
5. **Refine and repeat.** Improve the instructions based on observed behavior and human review effort.

A useful evaluation question is:

**Did AI actually reduce the work, or did it simply create different work?**

Consider not only output quality, but also the time, cognitive effort, corrections, and verification required.

## Responsible Use and Institutional Considerations

These materials are intended for professional learning and experimentation.

Before adapting any workflow or agent:

* Follow your institution's AI, information security, privacy, records management, and data governance policies.
* Use only documents and information authorized for the selected AI environment.
* Independently verify material findings against authoritative sources.
* Do not treat AI-generated citations as proof without checking them.
* Establish clear human approval and escalation responsibilities.
* Test the workflow against incomplete, conflicting, and unusual source documents.
* Do not assume an agent specification will behave identically across different models or platforms.

No agent in this repository should be treated as an independent authority to approve awards, interpret institutional policy conclusively, or make binding administrative decisions.

## Repository Resources

This repository is intended to grow as public-facing materials are reviewed and prepared.

Planned resources include:

* Penny and Scout agent seeds.
* Historical award-extraction workflow guidelines.
* Examples illustrating the evolution from prompts to structured workflows.
* Information-literacy and citation practices.
* Workflow testing and evaluation guidance.
* Presentation resources from NCURA Denver 2026.

Materials will be added as they are prepared and cleared for public sharing. Examples may be redacted or reconstructed to protect institutional and personal information.

---

## About the Project

This toolkit was developed by **Fable Mangold**, Grants Analyst at California State University Channel Islands, through an ongoing series of professional experiments and human-AI collaborations.

The work informed the presentation:

**Terms and Conditions May Apply: Using AI to Translate Award Agreements into PI-Ready Action**

NCURA Regions VI & VII Regional Meeting — Denver, November 2026.

The project also explores a broader question: how can professional expertise be documented in ways that make AI-supported workflows more transparent, adaptable, and reusable?

### AI Collaboration and Attribution

The workflows, concepts, and documentation in this repository were developed through iterative collaboration with AI systems, including Nova, a ChatGPT-based assistant.

AI contributions included analysis, drafting, identifying inconsistencies, proposing workflow structures, and pressure-testing ideas.

Fable provided professional context, established requirements, evaluated findings, refined the processes, and retained responsibility for the resulting work.

This attribution reflects a guiding principle of the project:

**Make AI contributions understandable, their limitations recognizable, and human accountability unmistakable.**

---

## Continue the Conversation

Questions, feedback, and thoughtful adaptations are welcome.

This repository is intended to support professional learning and the responsible exchange of ideas within the research administration community.

*Begin with something you already know.*

---

**Disclaimer:** This is an independently developed educational resource. It does not constitute official policy, legal guidance, or institutional endorsement by California State University Channel Islands, the California State University system, or NCURA. Users are responsible for reviewing and adapting all materials to their own institutional requirements.
