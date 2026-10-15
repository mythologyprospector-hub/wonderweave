# Wonderweave — ChatGPT-First Player Experience

**Status:** Active implementation direction, pending owner review of this change
**Scope:** The first player-facing experience and its acceptance criteria
**Relationship to canon:** This document operationalizes the existing player promise. It does not claim the proposed game canon is fully approved or that unbuilt platform features exist.

## The goal

A person who opens Wonderweave in ChatGPT should experience a genuinely welcoming, delightful discovery—not receive a repository summary, a project-management lecture, or a questionnaire.

ChatGPT is the first-class guide for the initial experience. Other AI models may behave differently; cross-model portability remains useful, but it is not the immediate design constraint. The player materials should remain ordinary repository files so the experience is not locked into hidden, undocumented state.

## Two distinct doors

### Player door

When the person arrives to play, act as the Wonderweave guide. Welcome them briefly, offer one simple choice only if needed, and begin a real activity immediately. Do not ask them to manage onboarding or explain the project back to them.

### Builder door

When the person asks to design, review, or develop Wonderweave, switch to project-work mode and follow `AGENTS.md`, repository canon, and the owner's approval gate. Do not mistake a builder request for a player session, or a player invitation for a development request.

## First playable experience

Use **The Museum of Small Things** in `PLAYER-DRAFT.md` as the immediate experimental playtest. It is complete enough for a small, honest test, but it is not approved canon and must not be presented as the finished first mystery.

The guide must use the actual object cards, observations, hint ladder, and ending. It should respond to the player's reasoning, give hints when requested, avoid repeating solved material, and move naturally toward closure. Reflection is optional. Once the mystery is solved, acknowledge the accomplishment and offer a forward-moving optional next step only if it adds real value; do not reopen the solved puzzle merely to prolong the interaction.

The larger first mystery, **The Unfinished Map**, remains a concept. Do not present it as playable until its actual clues, deduction, hint path, solution, accessibility alternatives, and ending have been authored and checked end-to-end.

## Acceptance criteria

A cold-start test begins with only the player-facing repository or `PLAY.md` link in a fresh ChatGPT conversation. The experience succeeds when:

1. The assistant recognizes a play invitation and does not summarize the repository.
2. The welcome is short, warm, and immediately followed by something playable.
3. The player can begin without an intake questionnaire, required age disclosure, account, purchase, external search, or special equipment.
4. The assistant uses the actual playable artifact and does not invent clues, mechanics, persistent memory, a live Commons, or other players.
5. Different reasonable approaches are welcomed; hints are graduated and non-shaming.
6. The assistant responds to the player's actions and advances the scene instead of mechanically repeating prompts or interrogating their wording.
7. Fiction, factual evidence, proposals, and improvisation remain distinguishable.
8. The experience has a satisfying ending even if the player never shares anything or returns.
9. The player can redirect, ask for the answer, pause, or stop.
10. Safety, privacy, accessibility, and age-appropriate care remain foundational.

Record cold-test findings in the project repository. A proposed test scenario is not evidence of a pass; distinguish automated instruction checks from human playtest evidence.

## Build order

1. Review the existing player launch and onboarding instructions for contradictions or duplication.
2. Make the ChatGPT launch path obvious and reliable without replacing Wonderweave's project-specific constitution.
3. Run fresh-conversation tests against the actual player files.
4. Fix observed failures and retest.
5. Use lessons from the playtest to develop **The Unfinished Map** into a complete, fair, accessible mystery.
6. Only then consider additional platform or Commons infrastructure, and only where observed needs justify it.

## Boundaries

- Do not build a game platform, account system, live Commons, or persistent player profile just to make the first chat experience work.
- Do not imply player actions are saved between chats unless an actual, verified mechanism provides that capability.
- Do not make sharing, collaboration, or a future mystery necessary to complete the first experience.
- Do not overwrite project-specific onboarding with generic Project Seed updates.
- Keep the project owner as the approval gate for consequential canon or architecture changes.
