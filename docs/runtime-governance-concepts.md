# Runtime Governance Concepts

This document summarizes the core concepts used in NextOne Observatory.

## Runtime governance

Runtime governance is governance that remains visible and actionable while a system is operating.

It asks whether control remains valid when an AI-supported workflow moves toward consequence, not only whether the system was previously approved or later audited.

## Evidence of control

Evidence of control is observable proof that permissions, constraints, escalation paths, monitoring, and human authority remained valid when they mattered.

An audit trail may prove participation, but not control.

## Human-in-control

Human-in-control is different from human-in-the-loop.

A human is meaningfully in control only if they have the information, authority, time, and technical path to intervene before consequence.

## Authority continuity

Authority continuity asks whether the authority behind an action remains valid as conditions change.

An approval may have been valid at issuance but no longer executable under current conditions.

## Runtime-validity object

A runtime-validity object is an active evaluation structure that compares the current execution state with the validity conditions of the approved authority envelope.

It supports the question:

> Are the conditions that made this authority valid still present now?

## Intervention viability

Intervention viability asks whether a human intervention path still exists in practice.

Oversight becomes symbolic when the human cannot see, understand, pause, escalate, or stop the workflow before consequence.

## Governance surface drift

Governance surface drift occurs when the technical system remains functional but the governance assumptions around it change.

Roles, permissions, dependencies, evidence freshness, data sources, policies, escalation paths, or tool access may drift while dashboards still look healthy.

## Permission and authorization drift

Permission drift occurs when what a system can observe, recommend, write, trigger, change, or make real changes over time.

Authorization drift occurs when the authority basis for those actions is no longer aligned with current execution conditions.

## Safe reliance

Safe reliance asks whether a user or organization is justified in relying on an AI output in the current context.

A fluent or useful answer may still create unsafe reliance if uncertainty, scope, reversibility, or expert review conditions are not handled correctly.

## Runtime states

NextOne Observatory uses four practical runtime governance states:

- ALLOW: continue under valid control conditions
- HOLD: pause because evidence, context, or authority is incomplete
- ESCALATE: route to human or higher authority before consequence
- REFUSE: do not continue because action is outside valid or safe conditions
