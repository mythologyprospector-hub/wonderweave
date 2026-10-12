# Wonderweave World Model

**Status:** Proposed  
**Governs:** A conceptual model for organizing world knowledge and relationships. It does not establish production storage, a graph database, or new game canon.  
**Last verified:** 2026-10-11

## Purpose

The assistant needs a reliable way to understand what exists, what relates, and what remains uncertain without pretending to know the whole world. This document proposes a layered world bible and a relationship graph as concepts to test—not a mandate to build a graph database now.

## Separate four kinds of information

### 1. Established world material

Authored and maintained material: published mysteries, fictional characters and places, rules, endings, approved contributions, and other material whose status is known. Each item should have a source and a clear status.

### 2. Real-world knowledge

Facts about history, language, culture, nature, science, and other subjects. Important claims should retain sources, context, and relevant uncertainty. Fictional framing does not turn a claim into evidence.

### 3. Player discoveries and contributions

Observations, solutions, artwork, questions, theories, and unfinished work shared by players. A contribution belongs to its contributor and keeps its context and credit. Private session material does not become a Commons contribution by default.

### 4. Assistant interpretations

Suggestions, hypotheses, possible connections, generated story details, and inferred meanings. These remain attributed to the assistant and provisional unless reviewed through an explicit process. The assistant cannot promote its own speculation into established canon.

## A graph without a master map

A relationship graph may eventually help Wonderweave navigate links among discoveries. The world can be represented as a network of local, partial relationships rather than a complete map designed in advance.

Possible node types include:

- mystery, scene, character, place, artifact, clue, rule, and fictional event;
- real-world concept, source, observation, question, and research finding;
- player contribution, creative work, hypothesis, and unresolved question.

Possible relationship types include:

- **part-of / appears-in:** a clue belongs to a mystery or an artifact appears in a scene;
- **supports / contradicts:** evidence bears on a hypothesis;
- **resembles / may-relate-to:** two observations share a possible pattern without implying proof;
- **depends-on / explains:** one item is needed to understand another, or provides an explanation;
- **created-by / sourced-from / derived-from:** provenance and credit;
- **responds-to / builds-on:** one contribution develops another;
- **leads-to:** a designed next step, distinguished from an optional suggestion.

These are candidate vocabulary, not a fixed taxonomy. Add a relationship only when it helps a real task. Do not force every item into a category or every node to have a link.

## Every meaningful connection needs context

A useful relationship record should be able to answer:

- What are the two things being connected?
- What kind of relationship is claimed?
- What evidence, source, or reasoning supports it?
- Who or what proposed it?
- Is it confirmed, disputed, speculative, fictional, or unknown?
- When and in what context was it added or reviewed?
- Is it private, session-local, or intentionally shared?

A graph edge is a claim, not proof. Similarity alone does not establish causation, common origin, intended puzzle linkage, or real-world significance.

## Keep status explicit

Use plain status distinctions appropriate to the material:

- **Established:** supported by the project's authorized canon or reliable evidence for the relevant kind of claim.
- **Proposed:** an authored idea awaiting review or adoption.
- **Supported hypothesis:** a plausible interpretation with stated evidence, still open to revision.
- **Speculative:** a possibility with limited or incomplete support.
- **Disputed:** meaningful disagreement or conflicting evidence exists.
- **Unknown:** available information does not settle the question.
- **Fictional:** true within a stated fictional context, not a real-world claim.

These labels are not a universal truth score. Fictional canon, scientific evidence, player observations, and puzzle solutions need different standards of review.

## The story bible

The story bible should preserve what future experiences need to remain coherent:

- established setting and story facts;
- rules and constraints that mysteries rely on;
- character, place, artifact, and terminology references;
- chronology when chronology matters;
- source and provenance notes;
- unresolved questions and deliberate ambiguities;
- version history and the authority that approved changes.

Do not write a complete encyclopedia before there is a world worth documenting. Begin with the material needed to make the current experience fair and coherent. Extend the bible when new experiences create a real continuity need.

## Knowledge boundaries and spoilers

The assistant's access to information should be separated from what is appropriate to reveal. A facilitator solution may be needed to check a puzzle's fairness, but that does not mean the player should receive it unasked.

For any future challenge, track spoiler-sensitive information separately from player-facing material where practical. The interaction policy should honor the player's requested hint level and avoid accidental solution leaks. A player can always request a direct answer.

## Change and review

The graph must not silently rewrite canon. A future workflow should distinguish:

1. a contribution or hypothesis being submitted;
2. a connection being suggested;
3. evidence or review being added;
4. a human-authorized or otherwise defined decision establishing shared canon, when applicable.

Not every observation needs formal review. Not every theory needs to become canon. Unresolved and unconnected material can remain valuable.

## Build only when justified

For the first playable experience, well-structured Markdown and links may be enough. A graph data file, database, search service, or semantic retrieval system should be considered only after real examples show that manual navigation is inadequate. If a graph is implemented later, preserve provenance, privacy, correction, and exportability from the beginning.

## Related documents

- [Assistant overview](ASSISTANT.md)
- [Assistant charter](ASSISTANT-CHARTER.md)
- [Assistant roles](ASSISTANT-ROLES.md)
- [Interaction engine](INTERACTION-ENGINE.md)
- [The Commons](COMMONS.md)
- [Game canon](CANON.md)
