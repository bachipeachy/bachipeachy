# About My Flagship Research Initiative
My current work is centered on the Protocol Governance System (PGS)—an experimental software engineering platform exploring how AI changes the way software is created.

Traditional software development treats source code as the primary artifact and business knowledge as something embedded within it. PGS explores the opposite approach: making business behavior, governance, and execution protocols the primary artifacts, while treating implementation as a replaceable execution detail.

The goal is to enable software systems whose behavior can be authored, validated, compiled, and executed directly from governed protocols—allowing implementations, programming languages, AI models, and runtime technologies to evolve independently without changing the business intent.

This is an active research effort documenting the architecture, experiments, and engineering needed to make protocol-driven software development practical in the AI era.

# PGS — Protocol-Governed Software

> **A new paradigm for software engineering in the AI era.**

Traditional software treats source code as the system.

PGS treats **business behavior** as the system.

Everything else—including implementation—is a replaceable execution strategy.

---

# The Problem

For more than fifty years, software has followed essentially the same model:

```
Business Requirements
        ↓
Specification
        ↓
Source Code
        ↓
Executable
```

Over time, business knowledge becomes embedded inside millions of lines of implementation.

Business rules become scattered.

Process becomes implicit.

Governance becomes documentation.

Changing behavior requires changing code.

The implementation becomes the product.

---

# The PGS View

PGS inverts this relationship.

Business behavior is authored as governed protocols.

Those protocols are compiled into executable representations while preserving their semantics.

The runtime executes compiled protocols—not handwritten implementations.

```
Business Behavior
        │
        ▼
Authoring Protocol
        │
        ▼
Governed Construction
        │
        ▼
Compiler
        │
        ▼
Semantic Verification
        │
        ▼
Runtime
```

Implementation becomes infrastructure.

Behavior remains the product.

---

# Core Principles

## Behavior is the asset

Business processes.

Business rules.

Governance.

Lifecycle.

Authority.

Identity.

These define the system.

Not source code.

---

## Implementation is interchangeable

A protocol may execute on:

* a Python runtime
* a distributed runtime
* an embedded runtime
* a cloud service
* a future execution engine

without changing the authored business behavior.

---

## Governance is executable

Governance is not documentation.

It is compiled.

Validated.

Verified.

Executed.

---

## Compilation must preserve meaning

PGS introduces **Compilation Semantic Integrity (CSI)**.

Compilation is not considered successful merely because it generates artifacts.

It must demonstrate that the compiled protocol preserves the semantics of the authored protocol.

This introduces semantic verification as a first-class architectural concern.

---

## AI becomes an interchangeable worker

In PGS, an AI model is not the authority.

It is simply another worker.

Whether the worker is:

* Claude API
* Claude Code
* ChatGPT
* Gemini
* an open-source model
* or a human expert

the governing protocol remains identical.

Every stage is validated before entering the system.

The protocol—not the model—is the system of record.

---

# A Different Separation of Concerns

Traditional software separates:

```
Requirements
↓

Code
↓

Runtime
```

PGS separates:

```
Business Behavior
↓

Governance
↓

Construction
↓

Verification
↓

Execution
```

This distinction allows implementation technologies to evolve independently from business behavior.

---

# Architectural Pillars

PGS currently rests on four architectural pillars.

### 1. Authoring Protocol

Business behavior is authored as governed protocols rather than embedded directly in code.

### 2. Protocol Compiler

Transforms authored protocols into executable protocol snapshots.

### 3. Compilation Semantic Integrity (CSI)

Independently verifies that compilation preserves authored semantics.

### 4. Worker Observability

Measures AI and human worker conformance through objective protocol contracts rather than subjective output quality.

---

# Guided Authoring

PGS supports multiple authoring modes.

* Fully automated using model APIs.
* Guided authoring using conversational AI such as Claude Code.
* Deterministic replay using recorded stage artifacts.

The protocol remains identical across all modes.

Only the transport changes.

---

# Why This Matters

As AI increasingly generates software, the critical question is no longer:

> *Can AI write code?*

The more important question becomes:

> **How do we guarantee that generated systems preserve intended business behavior?**

PGS answers that question by making behavior explicit, governed, verifiable, and independent of implementation.

---

# Vision

We believe the next generation of software systems will not be defined by programming languages.

They will be defined by **governed protocols describing behavior**, with compilers, verification engines, and runtimes ensuring that those behaviors execute faithfully across any implementation technology.

In the AI era, software engineering should optimize for **behavioral correctness**, not implementation ownership.

PGS is an exploration of that future.
