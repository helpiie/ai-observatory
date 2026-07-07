# AI Observatory

An experimental research project exploring AI agent observability, runtime governance, and evidence of human control.

## Overview

As AI systems become more autonomous, understanding their behaviour during execution becomes increasingly important.

AI Observatory explores how we can observe:

* AI agent decisions
* runtime context
* execution boundaries
* authorization conditions
* human intervention opportunities

## Motivation

Traditional AI governance often focuses on policies, documentation, approval processes, and post-event analysis.

AI Observatory explores a different question:

> Can we demonstrate that meaningful human control still exists while an AI system is operating?

The project investigates how runtime evidence can help make AI-enabled workflows more observable, explainable, and controllable.

## Research Questions

* Can we measure meaningful human control during AI execution?
* How can AI systems provide evidence about their decisions?
* What signals indicate that control is degrading before failure occurs?
* How can systems know when to continue, escalate, hold, or refuse an action?

## Core Concepts

The project explores:

* runtime governance
* evidence of control
* decision context
* authorization validity
* intervention capability
* execution boundaries

## Vision

AI systems should not only produce outputs.

They should provide evidence about:

* why actions happened
* under what conditions they happened
* what permissions were active
* whether humans still had meaningful ability to intervene

## Example Runtime Trace

The project includes an example AI agent execution trace showing how runtime evidence could be captured.

See:

`examples/agent-trace-example.json`

The example explores visibility into:

* decisions
* permissions
* execution context
* human intervention capability

## Status

Early research prototype and documentation project.

Current release:

`v0.1.0 – Conceptual Runtime Governance Model`

The project is intended as an open exploration of practical approaches to AI observability and runtime control.

## Future Exploration

Potential future areas include:

* agent event schemas
* runtime monitoring concepts
* decision timelines
* control state modelling
* escalation mechanisms
* evidence collection patterns
