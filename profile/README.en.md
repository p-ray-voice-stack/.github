# P-Ray Voice Stack

**LANGUAGE:** [中文版](./README.md)

> **P-Ray Voice Stack** is a GitHub organization focused on enterprise-grade voice systems and delivery engineering.  
> Our priority is not to ship a one-off demo, but to turn voice-related capabilities into deliverable, deployable, maintainable, and commercially operable systems.

## Positioning

`p-ray-voice-stack` does not exist to host a single product repository or a loose collection of experiments.  
It functions as a **commercial voice systems workspace** where open-source mainline work, website systems, image publishing, deployment contracts, operational handoff, and delivery boundaries are kept explicit instead of being mixed together.

We treat the following as first-order concerns:

- **business-facing system credibility comes from clear boundaries, not feature sprawl**
- **infrastructure, publishing, and host contracts are part of product capability**
- **there must be evidence between “deployable” and “deployed,” not just verbal status**

## What We Work On

Current work across this organization is concentrated around:

- **architecture and runtime design for voice-related application systems**
- **engineering of public website frontend, backend, and access layers**
- **deployment contracts for containers, host environments, reverse proxy, and release paths**
- **repository and responsibility layering across open-source mainline, website runtime, and commercial delivery lines**

If a system may eventually enter a customer environment or be handed across teams, “it runs on my machine” is not enough.  
It should be able to explain:

- why repositories are split this way
- why images are published from a specific path
- why a runtime depends on a specific host-side contract
- which parts are public mainline and which parts belong to private delivery or operational boundaries

## Repository Roles

Repositories in this organization currently serve different roles:

- **`P-Ray-Voice-Stack`**
  - the open-source mainline repository
  - public systems work, protocol shape, runtime boundaries, and long-term mainline implementation

- **`pray-site-frontend`**
  - the website frontend repository
  - public presentation layer, content layer, and frontend experience responsibilities

- **`pray-site-backend`**
  - the website backend repository
  - API, container image, host contract, and backend deployment responsibilities

- **additional delivery- or environment-specific repositories**
  - used when a runtime, customer environment, or delivery surface should remain separate from the public mainline

This is not temporary structure. It is deliberate commercial layering:  
**not every code path belongs in the same repository, and not every responsibility should share the same release line.**

## What We Optimize For

In business-facing voice systems, we optimize for the following more than superficial feature count:

- **explicit contracts**
  - containers, ports, domains, proxy rules, image tags, and environment variables should be explainable

- **reproducible release**
  - image paths, version identifiers, compose structure, and host contracts should remain stable

- **handoff-ready operation**
  - operational notes, deployment boundaries, and private handoff materials should support safe transfer of ownership

- **clear public/private boundaries**
  - open-source mainline, website runtime, and delivery runtime should not collapse into one mixed track

- **narrow checkpoints**
  - we prefer small, reviewable infrastructure and runtime checkpoints over “magic” one-shot deployment

## Collaboration

We welcome collaboration that is **careful, engineering-minded, and explainable**.  
In this organization, strong contributions usually improve one or more of the following:

- clearer repository boundaries
- more reliable release paths
- more reviewable runtime behavior
- easier maintenance for website and delivery lines
- more accurate documentation and handoff material

If you are reading this page, the key point is not only what we build, but how we keep each system line understandable, reviewable, and safe to evolve in a commercial setting.

## Organization Information

- **Organization:** `p-ray-voice-stack`
- **Founding company:** **Suzhou Industrial Park Qiguang Artificial Intelligence Technology Co., Ltd.**
- **English company name:** **P-ray AI**

## Contact And Follow-Up

For collaboration, technical coordination, or business-facing discussion, please prefer the relevant repository through:

- Issues
- Pull Requests
- documented repository-level communication channels where available

For systems, deployment, and organizational structure, we strongly prefer communication that is **traceable, referenceable, and reviewable**.
