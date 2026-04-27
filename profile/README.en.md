# P-Ray Voice Stack

**LANGUAGE:** [中文版](./README.md)

> **P-Ray Voice Stack** is an organizational workspace centered on voice-related software systems.  
> We treat research, system design, website engineering, deployment contracts, and runtime governance as one continuous engineering workflow rather than isolated stages.

## Abstract

The purpose of `p-ray-voice-stack` as a GitHub organization is not to host a single repository or a single product line. Instead, it provides a stable structure for a set of related system efforts whose boundaries must remain explicit. Our current work spans applied AI, web systems, runtime hosts, image publishing pipelines, deployment governance, and operational handoff documentation.

We make one principle especially clear: **infrastructure is not an afterthought; it is part of system design.**  
For that reason, image publishing, host contracts, deployment boundaries, repository layering, and operational handoff notes are documented deliberately and reviewed as first-class engineering artifacts.

## Research And System Scope

Our current work focuses on:

- **architecture and runtime design for voice-related software systems**
- **engineering of public website frontend, backend, and access layers**
- **container, host, and release contracts for reproducible deployment**
- **repository governance across open-source mainline, website runtime, and delivery runtime layers**

We place a high value on system legibility.  
A repository should be able to explain why it exists. A deployment line should make its ownership clear. An image path should be justified. A host contract should be explicit. These answers should come from documentation rather than oral memory.

## Repository Structure

Repositories in this organization currently serve distinct roles:

- **`P-Ray-Voice-Stack`**
  - the open-source mainline repository
  - broader public systems work, research direction, and mainline implementation

- **`pray-site-frontend`**
  - the public website frontend repository
  - focused on the public-facing presentation and frontend experience layer

- **`pray-site-backend`**
  - the public website backend repository
  - focused on API, backend runtime, and backend deployment line responsibilities

- **additional delivery- or environment-specific repositories**
  - used when a runtime, delivery environment, or deployment concern should remain distinct from the public mainline

This structure is intentional rather than temporary:  
**not every code path belongs in the same repository, and not every runtime responsibility should share the same deployment line.**

## Method And Style

We prefer:

- **explicit contracts over hidden environment drift**
- **immutable release identifiers over ambiguous runtime state**
- **narrow, reviewable infrastructure checkpoints over one-step “magic” deployment**
- **clear repository and runtime boundaries**
- **handoff documentation that supports long-term maintainability instead of personal memory**

In practice, this means we care about:

- image repository paths and tag rules
- nginx and host-side port contracts
- the separation of roles between organization profile, repository governance docs, and private operational notes
- evidence-based transitions between “deployable” and “deployed”

## Collaboration

We welcome collaboration that is **careful, systems-minded, and explainable**.  
Within this organization, valuable contributions often improve one or more of the following:

- repository boundary clarity
- deployment reproducibility
- runtime reliability
- maintainability of website-facing systems
- accuracy and continuity of documentation and operational handoff material

If you are reading this page, the most important point is not simply what we build, but how we want it to remain understandable, reviewable, and safely handoff-ready over time.

## Organization Information

- **Organization:** `p-ray-voice-stack`
- **Founding company:** **Suzhou Industrial Park Qiguang Artificial Intelligence Technology Co., Ltd.**
- **Working English company name (provisional):** **P-ray AI Ltd.**

## Contact And Follow-Up

For collaboration or technical coordination, please prefer the relevant repository:

- Issues
- Pull Requests
- documented repository-level communication channels where available

For systems, deployment, and organizational structure, we strongly prefer communication that is **traceable, referenceable, and reviewable**.
