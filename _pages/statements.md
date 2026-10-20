---
layout: archive
title: "Research Statements"
permalink: /statements/
author_profile: true
---

*This page is a work in progress — the sections below sketch the directions I am committing to, and I will expand each one as the work lands.*

## Why Agent Security

A language model that only answers questions can be wrong. A language model with tools, memory, and sibling agents can be wrong *and* act on it — write to a database, send a message, spend money, escalate its own privileges. Most safety evaluation still scores the text an agent produces rather than the consequences of what it does, which is why my work keeps finding failures that every guardrail in the loop reports as success.

Three properties make this a good research setting:

**1. Failures are observable.** Unlike open-ended alignment questions, an agent either escalated a privilege or it did not, either touched a file it should not have or it did not. That makes benchmarks possible.

**2. The attack surface is compositional.** Tool schemas, memory, retrieval, and multi-agent routing each look safe alone and break in combination. Single-shot compositional attacks on multi-agent pipelines are the clearest example.

**3. The deployment gap is immediate.** These systems are already shipping, so a benchmark that captures a real failure mode changes practice quickly.

## Current Directions

- **Permission and privilege semantics in tool use.** Under-specified tool schemas let agents acquire capability they were never granted. I want a principled account of what "least privilege" means for an agent, and evaluation that measures it.
- **Guard models under distribution shift.** Safety classifiers fine-tuned for one domain lose their geometry in another. How do we certify a guard model's robustness rather than its average accuracy?
- **Memory integrity.** Poisoned memory looks like ordinary model failure in post-hoc review, so it gets misattributed. I am interested in attribution: given a bad action, what evidence identifies the cause?
- **Evaluation that survives contamination.** Benchmarks age badly once they are in training data. I want construction methods whose difficulty is reproducible from fresh sources.

## Privacy as a First-Class Constraint

My earlier work on social platforms — privacy risk scoring over attributes, graphs, and text; identity-attack defenses; federated pipelines that keep raw user data on device — informs how I think about agents that read personal context. Capability and privacy are the same question asked twice: what is this system allowed to know, and what is it allowed to do with it?

## Placeholder

*To be added: a longer teaching statement, a diversity statement, and a PDF version of this page.*
