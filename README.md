# NextOne Observatory / AI Observatory

**AI runtime governance, evidence of control, observability, and human authority at the point of execution.**

NextOne Observatory is an independent research and prototype direction exploring how AI-enabled and agentic systems can remain observable, controllable, reconstructable, and human-governable while they are operating.

The core question is:

> Can an organization prove that an AI-enabled system was used under valid, monitored, human-controllable and reconstructable conditions when its output influenced consequence?

This repository develops concepts, examples, and prototype documentation around runtime governance for AI-supported workflows.

---

## Why this exists

AI governance is often discussed through policies, approvals, model documentation, audits, and post-event review.

Those layers matter, but they do not fully answer the operational question:

> Was control still real when the AI-supported workflow moved toward consequence?

An audit trail may prove participation, but not control.

NextOne Observatory focuses on the runtime layer where AI outputs, agentic workflows, permissions, evidence, human authority, and operational consequences meet.

---

## Research focus

The project explores how AI systems and organizations can reason about:

- who or what is acting
- under which authority
- under which current conditions
- with what evidence
- what the system can observe, recommend, write, trigger, change, or make real
- whether authorization is still valid now
- whether human intervention is still meaningful before consequence
- whether the system should allow, hold, escalate, revalidate, refuse, or fail closed

---

## Core concepts

This repository develops and documents concepts including:

- runtime governance
- evidence of control
- human-in-control
- authority continuity
- runtime-validity objects
- intervention viability
- governance surface drift
- permission and authorization drift
- safe reliance
- observability versus control
- ALLOW / HOLD / ESCALATE / REFUSE runtime states

---

## Article 26 as runtime governance

NextOne Observatory includes public research on Article 26 of the EU AI Act as an operational deployer responsibility problem.

The central operating sentence of that work is:

> A deployer should be able to prove that a high-risk AI system was used under valid, monitored, human-controllable and reconstructable conditions when its output influenced consequence.

Public reference:

- Article 26 as Runtime Governance  
  https://nextone.ie/observatory/article26/

---

## External reference: StratoAtlas Pressure Signal

This work is connected to a published named contribution to StratoAtlas.

Published reference:

- Runtime Authorization History Does Not Prove Runtime Control  
  https://stratoatlas.com/pressure/runtime-authorization-history-does-not-prove-control

The contribution focuses on runtime authorization, authority-state continuity, and evidence of control.

It distinguishes between:

1. declarative control
2. the authority object
3. the runtime-validity object
4. evidence of control

It also develops the distinction between authorization-history evidence and evidence that valid authority remained causally connected to execution.

The contribution was integrated into StratoAtlas' Helsing — Declarative Control structural map:

- Helsing — Declarative Control  
  https://stratoatlas.com/maps/helsing/declarative-control

---

## Example runtime trace

The repository includes an example AI agent execution trace showing how runtime evidence might be represented:

- examples/agent-trace-example.json

The example explores visibility into decisions, permissions, execution context, authorization conditions, and human intervention capability.

---

## Prototype direction

The long-term direction is to explore how AI-supported systems could expose runtime governance signals such as:

- active authority state
- current evidence state
- permission and tool-use boundaries
- admissibility before execution
- escalation paths
- human intervention windows
- control degradation signals
- reconstructable decision context
- runtime state transitions

This is not only about whether an AI system produced an output.

It is about whether the organization can prove why that output was allowed to matter.

---

## Status

Independent research and early prototype documentation.

This repository is not legal advice, certification guidance, or a compliance product.

It is a public research and systems-thinking workspace for AI runtime governance, evidence of control, and human authority at execution.

---

## Guiding sentence

**Brilliance without control is exposure.**
