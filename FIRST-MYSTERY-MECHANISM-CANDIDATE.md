# Wonderweave — First Mystery Mechanism Candidate

**Status:** Proposed  
**Governs:** One candidate puzzle mechanism for *The Unfinished Map*; not a playable or approved puzzle.  
**Last verified:** 2026-10-10

## Design question

Can four small records, each understandable on its own, combine into a satisfying discovery without specialist knowledge, external searching, or a mandatory starting point?

The first attempt used four clockwise relationships to form a loop. That is logically sound but too simple by itself, and it does not explain the blank center. This revision defines the missing second discovery as a **convergence test** rather than asking players to guess a symbolic word.

## Intended reveal

The mapmaker did not leave a missing landmark in the center. The four records describe different journeys from the outer stations, and their evidence shows that the journeys converge on the same unmarked place.

The objectively checkable result is: **the four routes meet at the center**. Calling that place a meeting point is supported by the route evidence. What the place means to the player remains open; no secret word like MEET is required.

This is a stronger design hypothesis than the earlier imposed-word reveal, but the exact route diagrams and records still need to be built and checked. This file does not claim the puzzle is playable.

## Player-facing setup

> The mapmaker's map has four named stations and an empty center. Four records were found among the mapmaker's papers. Each preserves part of a journey. You can inspect the records in any order. Work out where the journeys lead, and why the mapmaker left that place unnamed.

The four stations use distinct names and redundant marks:
- **LANTERN** — lamp mark
- **RIVER** — wave mark
- **SEED** — seed mark
- **BELL** — bell mark

The marks are not color-coded clues. Each has a plain-language label.

## Proposed structure of the four records

The records should have different accessible forms, but each must contribute evidence to the same convergence question.

**Record A — Surveyor's sketch:** a small, labeled route diagram beginning at Lantern. It shows turns and landmarks, but the last destination is left unnamed.

**Record B — Gardener's field note:** a plain-language sequence of turns beginning at Seed. The sequence can be followed on the same simplified map.

**Record C — Ferryman's travel log:** a compact sequence of directional steps beginning at River, with a matching text description for any visual marks.

**Record D — Mapmaker's annotation:** a final route from Bell, described with ordinary words and a small diagram.

**Crucial constraint:** these are not four unrelated mazes. Each route must be independently traceable using only the map and its own record, and all four must terminate at the same central location. The center is not labeled as a destination in advance; players establish the convergence by tracing the evidence.

This is a specification for the next draft, not yet the exact player-facing clue set. The route paths, turns, and map geometry must be written down and checked together before the puzzle can be called complete.

## Intended solution and proof obligations

1. Identify the labeled starting station for each record.
2. Follow each record's sequence on the map, without inventing missing turns.
3. Mark the endpoint of each route.
4. Compare all four endpoints.
5. Confirm that all four routes terminate in the same central area.
6. Conclude that the blank center is an intentional shared destination, not simply a missing label.

The solution guide must include a route-by-route trace table showing every turn and endpoint. A reviewer should be able to reproduce the result without relying on the author's interpretation.

## Design risks to resolve

- **Too easy:** Four straight lines aimed at the center would make the answer obvious and uninteresting. The paths should require careful but modest tracing, not obscure decoding.
- **Too hard:** If players must guess the map's scale, infer arbitrary symbols, or learn a private rule, the puzzle is unfair.
- **False convergence:** Routes must demonstrably terminate at the same defined area. Near misses or visually approximate intersections are not enough.
- **Multiple endpoints:** If a route has more than one reasonable reading, revise the record.
- **Unjustified emotion:** The paths can prove a shared destination; they cannot prove a specific sentimental backstory. Keep the closing interpretation proportionate to the evidence.
- **Overlong experience:** This mechanism may still be too short for the original 15–30 minute target. Do not pad it. Let cold-reader results determine whether it needs another meaningful layer or a shorter target session.

## Accessibility requirements

- Every route diagram has a complete text equivalent.
- Direction symbols are explained and are not conveyed by color alone.
- Route steps use a consistent, demonstrated vocabulary.
- The map has legible labels and no essential tiny details.
- Players can trace on paper, point, or talk through a route; no timed interaction is required.
- No external search, specialist geography, mythology, or cultural knowledge is required.

## Hint ladder

1. **Gentle nudge:** Each record describes a journey that begins at one of the four stations.
2. **More direct:** Trace each journey separately and mark where it ends.
3. **Nearly there:** Compare the four endpoints; check whether they occupy the same central place.

Hints may clarify the task but must not add a new rule.

## Alternate-solution and fairness review

Before acceptance, verify:
- all four records can be attempted in any order;
- each route has one traceable interpretation;
- all routes converge by the stated rules;
- no route depends on a hidden scale or unstated orientation;
- removing any record leaves one station's journey unverified;
- a cold reader can distinguish the map's evidence from decorative art;
- the route result supports the reveal without demanding one exact emotional interpretation.

## Decision gate

Keep this as a candidate only. Do not call it playable, canon, or a production specification until:
1. the map geometry and exact four route records exist;
2. a route-by-route trace table proves convergence;
3. text equivalents match the visual clues exactly;
4. a cold reader can solve it without coaching;
5. a reviewer tests alternate readings and records the result;
6. the ending says no more than the clues establish.

If the convergence version proves visually awkward or too trivial, discard it rather than defending it out of attachment to the concept.
