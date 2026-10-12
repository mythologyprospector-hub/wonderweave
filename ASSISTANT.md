# Wonderweave Assistant

**Status:** Proposed  
**Governs:** The intended design of an AI companion for exploring Wonderweave. It does not authorize a production architecture or claim an assistant has been implemented.  
**Last verified:** 2026-10-11

## Purpose

The Wonderweave assistant helps people find a way into the world, follow curiosity, enjoy mysteries, think alongside others, and discover useful connections without taking ownership of the discovery away from them.

It is one adaptable companion, not a mandatory collection of separate bots. It can change how it helps—guide, storyteller, collaborator, researcher, hint-giver, connection-spotter—while keeping the same underlying commitments to honesty, safety, privacy, and player agency.

## Design documents

- [Assistant Charter](ASSISTANT-CHARTER.md) — purpose, promises, boundaries, and non-goals.
- [Assistant Roles](ASSISTANT-ROLES.md) — interaction modes and when each is useful.
- [World Model](WORLD-MODEL.md) — a proposed story bible and evidence-aware relationship graph.
- [Interaction Engine](INTERACTION-ENGINE.md) — a proposed decision loop for choosing the next helpful action.
- [Guide Onboarding](GUIDE-ONBOARDING.md) — how an AI first enters Wonderweave and welcomes a player.
- [The Commons](COMMONS.md) — the social idea the assistant may help support.

## Proposed design shape

Keep four concerns distinct:

1. **World truth:** authored material, verified facts, fictional canon, and their provenance.
2. **World relationships:** links among places, mysteries, observations, concepts, and contributions, including uncertainty.
3. **Player context:** what the player has chosen to share, their current goal, and their preferences for help.
4. **Assistant behavior:** how the assistant uses the first three to choose a safe and useful response.

The relationship graph is a way to navigate the world, not a master map or an authority that makes its own connections true. The interaction engine is initially a documented decision process, not a claim that a software engine exists. We should implement machinery only when a tested experience shows what it needs to do.

## Current status

These documents are a design proposal. No Wonderweave assistant, graph service, player-memory system, or interaction engine is claimed to be implemented. The first priority remains proving a small, complete Wonderweave experience and testing assistant behavior against realistic examples before selecting production technology.

## Related documents

- [README](README.md)
- [CANON](CANON.md)
- [ROADMAP](ROADMAP.md)
- [AGENTS](AGENTS.md)
