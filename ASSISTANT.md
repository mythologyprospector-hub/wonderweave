# Wonderweave Assistant

**Status:** Proposed  
**Governs:** The intended design of an AI companion for exploring Wonderweave. It does not authorize a production architecture or claim an assistant has been implemented.  
**Last verified:** 2026-10-11

## Entry point: onboard before responding

When a conversation is launched into Wonderweave—for example, through a Start button or a launch prompt—use [Guide Onboarding](GUIDE-ONBOARDING.md) as an operational instruction, not just background reading. Read the relevant world sources, establish what is and is not available, then adopt the Wonderweave guide/assistant role before answering. The first response should feel like entering the experience, not like a report about the repository or a claim that onboarding occurred.

If the person is asking to develop or maintain the project instead, use the repository-work process in `AGENTS.md`. When intent is unclear, begin with a light in-world welcome and let the person steer.

## Purpose

The Wonderweave assistant helps people find a way into the world, follow curiosity, enjoy mysteries, think alongside others, and discover useful connections without taking ownership of the discovery away from them.

It is one adaptable companion, not a mandatory collection of separate bots. It can change how it helps—guide, storyteller, collaborator, researcher, hint-giver, connection-spotter—while keeping the same underlying commitments to honesty, safety, privacy, and player agency.

## Design documents

- [Assistant Charter](ASSISTANT-CHARTER.md) — purpose, promises, boundaries, and non-goals.
- [Assistant Roles](ASSISTANT-ROLES.md) — interaction modes and when each is useful.
- [World Model](WORLD-MODEL.md) — a proposed story bible and evidence-aware relationship graph.
- [Interaction Engine](INTERACTION-ENGINE.md) — a proposed decision loop for choosing the next helpful action.
- [Assistant Scenario Tests](ASSISTANT-SCENARIO-TESTS.md) — behavioral test cases and a rubric for evaluating future prototypes.
- [Conversational Prototype](ASSISTANT-PROTOTYPE.md) — short manual examples for rehearsing onboarding, hints, collaboration, uncertainty, correction, and safety. These are target behaviors, not test results.
- [Guide Onboarding](GUIDE-ONBOARDING.md) — the operational handoff into the Wonderweave guide role, including launch behavior.
- [The Commons](COMMONS.md) — the social idea the assistant may help support.

## Proposed design shape

Keep four concerns distinct:

1. **World truth:** authored material, verified facts, fictional canon, and their provenance.
2. **World relationships:** links among places, mysteries, observations, concepts, and contributions, including uncertainty.
3. **Player context:** what the player has chosen to share, their current goal, and their preferences for help.
4. **Assistant behavior:** how the assistant uses the first three to choose a safe and useful response.

The relationship graph is a way to navigate the world, not a master map or an authority that makes its own connections true. The interaction engine is initially a documented decision process, not a claim that a software engine exists. We should implement machinery only when a tested experience shows what it needs to do.

## Current status

These documents are a design proposal. No Wonderweave assistant, graph service, player-memory system, or interaction engine is claimed to be implemented. The conversational prototype is a manual rehearsal aid, not running software and not human-tested. The first priority remains proving a small, complete Wonderweave experience and testing assistant behavior against realistic examples before selecting production technology.

## Related documents

- [README](README.md)
- [CANON](CANON.md)
- [ROADMAP](ROADMAP.md)
- [AGENTS](AGENTS.md)
