# P-Ray Voice Stack

**LANGUAGE:** [中文版](./README.md)

> **P-Ray Voice Stack** is an organization centered on voice-related software systems as its core problem domain.  
> We treat research, systems design, website engineering, deployment contracts, and runtime governance as one continuous engineering workflow rather than as disconnected stages.

## Summary

The purpose of `p-ray-voice-stack` as a GitHub organization is not to host a single repository or a single product line. It exists to provide a stable structure for a set of related system efforts whose boundaries must remain clear. Our current work spans applied artificial intelligence, website frontend and backend systems, host-side runtime environments, image publishing pipelines, and deployment governance and handoff documentation.

We emphasize one point in particular: **infrastructure is not an accessory; it is part of system design.**  
For that reason, image publishing, host-side contracts, deployment boundaries, repository layering, and operational handoff are all explicitly documented, reviewed, and constrained.

## Research And System Scope

The main areas of work in this organization currently include:

- **architecture and runtime design for voice-related application systems**
- **engineering for the public website frontend, public website backend, and access entry points**
- **containers, host environments, and publishing contracts aimed at reproducible deployment**
- **repository governance across the open-source mainline, website runtime line, and delivery runtime line**

We tend to place a high value on system explainability.  
Why a repository exists, who owns a deployment line, why an image is published from a specific path, and why a service must keep a specific host-side contract should all be answerable through documentation rather than personal memory.

## Repository Structure

Repositories in this organization broadly serve the following different roles:

- **`P-Ray-Voice-Stack`**
  - the open-source mainline repository
  - carries broader public systems work, research context, and mainline implementation

- **`pray-site-frontend`**
  - the public website frontend repository
  - focused on the public presentation layer and frontend experience layer

- **`pray-site-backend`**
  - the public website backend repository
  - focused on website APIs, backend runtime logic, and the backend deployment line

- **other delivery- or environment-specific repositories**
  - when a runtime, delivery environment, or deployment surface should not be mixed with the open-source mainline, it remains behind an independent repository boundary

This structure is not temporary. It is an intentional form of layering:  
**not all code should go into the same repository, and not all runtime responsibilities should share the same deployment line.**

## Methods And Style

We prefer the following engineering methods:

- **replace implicit environment drift with explicit contracts**
- **replace ambiguous runtime state with immutable version identifiers**
- **replace black-box “one-shot” deployment with narrow, reviewable infrastructure checkpoints**
- **use repository boundaries and runtime boundaries to keep system responsibilities clear**
- **use handoff documents to maintain long-term maintainability instead of relying on personal memory**

In practice, this means we take the following seriously:

- image repository paths and tag rules
- nginx and host-side port contracts
- the role split between the organization profile, repository governance documents, and private operational documentation
- the evidence chain behind each step from “deployable” to “deployed”

## Collaboration

We welcome **careful, systematic, and explainable** collaboration.  
In this organization, good contributions usually improve one or more of the following:

- clearer repository boundaries
- more reproducible deployment paths
- more stable runtime behavior
- easier maintenance for website-related systems
- more accurate and more sustainable documentation and handoff materials

If you are reading this homepage, the most important point is not simply how much we have built, but this:  
**we want every systems thread to remain understandable, reviewable, and safe for the next contributor to take over when necessary.**

## Organization Information

- **Organization name:** `p-ray-voice-stack`
- **Founding company:** **Suzhou Industrial Park Qiguang Artificial Intelligence Technology Co., Ltd.**
- **English name (provisional):** **P-ray AI Ltd.**

## Contact And Follow-Up

If you would like to collaborate, communicate, or discuss technical coordination, please prefer the relevant repository’s:

- Issues
- Pull Requests
- documented contact channels inside the repository where available

For systems, deployment, and organizational structure themselves, we prefer communication that is **traceable, citable, and reviewable**.
