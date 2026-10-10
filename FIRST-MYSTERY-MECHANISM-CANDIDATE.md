# Wonderweave — First Mystery Mechanism Review

**Status:** Design review; current mechanism rejected for further polishing  
**Governs:** Decision record for The Unfinished Map concept  
**Last verified:** 2026-10-10

## Decision

The current “four stations / blank center / shared materials” mechanism does not justify its station-order puzzle.

The three spatial clues produce a unique clockwise arrangement, but uniqueness is not the same as narrative necessity. The records' material exchanges can be understood without the arrangement, and removing the repeated “center shelf” phrase would remove evidence rather than repair the dependency. The concept currently asks a small logic puzzle to carry a conclusion that the records already state or imply independently.

**Do not patch this with wording, extra lore, or artwork.** Treat the current player draft as a rejected design candidate, not a playable prototype.

## Three-way desk review

### A. Map alone

A ring of four stations around a blank center suggests a central junction or gathering point, but does not establish what the center is for. The spatial clues establish station positions only.

**Supported:** there is an unlabelled central area connected to the stations.  
**Not supported:** storage, exchange, ownership, shared access, or any particular purpose.

### B. Records without the constrained order

The records mention chalk, seed packets, and cord being used, left, or returned. In the existing draft, repeated references to a “center shelf” make the common-use interpretation explicit enough to infer without solving the station arrangement.

**Supported:** materials are reused across practical tasks.  
**Not supported by order:** a special causal or narrative insight that depends on clockwise reading.

### C. Records in the constrained order

The sequence Lantern → Seed → Bell → River forms a plausible progression of tasks and materials. But the same material links remain available when the records are shuffled; a careful reader can reconstruct them without the station-order deduction.

**Finding:** the order currently adds presentation, not necessary understanding. This fails the design test.

## Design consequence

Retire the ordering mechanic unless a substantially different mystery makes the order reveal a specific fact that cannot be obtained as easily from the records in arbitrary order.

The next candidate should begin with the mystery's *deduction*, not with a map shape:

1. State the exact question the player is trying to resolve.
2. List the evidence available from the map alone.
3. List what the records establish in arbitrary order.
4. Identify the one additional inference produced by the intended arrangement.
5. If step 4 cannot be stated concretely and defended, do not include the arrangement.

A valid alternative is a smaller mystery with no station-order puzzle. That is preferable to retaining an ornamental mechanic.

## Integrity boundary

No cold-reader playtest has been conducted. This is a designer desk review, not empirical evidence about players. The current candidate remains unapproved and untested. Do not describe it as playable, successful, or ready for production.

## Historical candidate, for context

The earlier concept used four equally spaced stations—Lantern, Seed, Bell, River—with constraints placing Lantern opposite Bell, Seed opposite River, and Seed immediately clockwise from Lantern. Its record trail used chalk, seed packets, and cord. Those elements are retained here only to explain why the candidate was rejected; they are not requirements for the next design.

## Next candidate to investigate — the dry channel

This is a **design sketch only**, not a replacement player draft.

### Mystery question

A small community garden's three beds are dry after a night when the cistern was known to be full. The player must determine what the evidence actually supports about where the water stopped flowing.

### Candidate evidence system

- A simple map shows one cistern feeding a main channel, then three branch channels to beds A, B, and C.
- Four maintenance slips describe the state of specific gates before or after a single adjustment. Each slip reports both the gate state and an observable downstream consequence (for example, a marked gauge changing or remaining unchanged).
- The slips are not pre-labelled with a complete chronological order. Their state transitions constrain which slip can follow another.
- The player reconstructs the only compatible sequence, then uses the sequence plus the map to distinguish a blocked branch from a gate that was deliberately closed or a channel that never received water.

### Why this might earn ordering

The intended insight would not be “water is shared.” It would be a causal diagnosis: **which segment first fails to transmit a change in water level**, and therefore what the evidence localizes—and does not localize—about the interruption.

The map alone gives connectivity, not the failure location. The slips in arbitrary order give isolated states but not the state transitions in time. A compatible sequence could expose the first break in the chain.

### Failure conditions before drafting

This candidate must be abandoned or redesigned unless a concrete set of slips passes all of these desk checks:

1. Exactly one sequence satisfies the stated state-transition evidence, or any remaining ambiguity is explicitly intended.
2. The diagnosis follows from the observations; it does not require assuming a character lied, guessing motives, or importing gardening expertise.
3. A shuffled presentation of the same slips does not make the causal chain equally obvious without doing the reconstruction.
4. The final inference is no stronger than the evidence: a dry bed alone cannot prove a blocked channel if a closed gate or another cause remains possible.
5. The solution can explain why each competing diagnosis fails, not just announce the intended answer.

**Current status:** promising structure, but not yet proven coherent. No player-facing text should be written from this sketch until the slips and state transitions have been worked through exhaustively.

### Concrete state-transition test — candidate only

To keep the next step falsifiable, here is a small test set. It is not yet player-facing copy or proof of a good mystery.

**Map:** A full cistern feeds an upstream gauge, then the normal inlet gate, then the main channel. A bypass can carry water around the normal inlet gate. The main channel feeds branch gates A, B, and C; each branch has a simple wet/dry gauge.

Each slip records the state before an action and the state after it. The slips are shuffled and have no time labels.

| Slip | Before | Action | After |
|---|---|---|---|
| K | Cistern full; upstream gauge dry; main and all branch gauges dry | Open the cistern outlet | Upstream gauge wet; main and all branch gauges dry |
| M | Upstream gauge wet; main and all branch gauges dry | Open the bypass around the normal inlet gate | Upstream and main gauges wet; all branch gauges dry |
| P | Upstream and main gauges wet; all branch gauges dry | Open branch gates A and B | A and B gauges wet; C remains dry |
| R | Upstream and main gauges wet; A and B gauges wet; C dry | Open branch gate C | All three branch gauges wet |

**State-match result:** K must precede M; M must precede P; P must precede R. Each slip's resulting state is the next slip's starting state, so the only complete chain is **K → M → P → R**.

**What this does and does not establish:**

- The sequence reconstructs a controlled test: source flow appeared upstream, the main channel only became wet after the bypass was opened, and the three branches became wet only after their branch gates were opened.
- The normal inlet route failed to transmit water during this test. The records do **not** distinguish a closed normal gate from a physical obstruction there.
- The branch gates were closed before they were opened in the test. The records do not establish who closed them or why.
- The map alone shows connectivity. The four slips in an arbitrary reading order are a set of before/after states; matching those states reconstructs the causal sequence. Reading the reconstructed chain makes the progression and the limits of the diagnosis legible.

**Adversarial caveat:** the chain is currently unique largely because each slip's before/after gauge pattern is designed to match exactly. That may be fair, but it may also feel like a worksheet rather than a mystery. We still need to test whether players understand why the sequence matters, whether the gate language is accessible, and whether the payoff feels meaningful. If exact state matching is too mechanical, do not disguise it with story.

**Next gate:** independently check every state transition and the unique ordering; then draft a plain-language reveal that states the strongest supported diagnosis and explicitly preserves the unresolved closed-gate-versus-obstruction distinction. Only after that should a player handout be drafted.

### Independent transition audit — 2026-10-10

**Audit result:** the four listed gauge-state transitions do chain in one order, K → M → P → R. This verifies the table's state matching, not the quality of the mystery.

**Evidence defect found:** the stated evidence system says each slip records gate state and downstream consequence, but the table records gauge states and actions only. It does not explicitly record each gate's before/after position. In particular, the claim that branch gates A and B were closed before P, or that C was closed before R, is inferred from the verbs “open” rather than separately evidenced. That wording may be understandable in ordinary language, but it is not a complete explicit state record.

**Larger design defect:** the slips reconstruct a controlled test sequence, but do not establish that this test was performed during or after the night when the beds were found dry. The test localizes a failure in the normal inlet route under the described conditions; it does not, by itself, explain the original incident or establish why the beds were dry. The mystery question therefore currently promises more than the evidence answers.

**Decision:** do not draft player-facing materials yet. The state chain is internally consistent, but the candidate does not yet pass the evidence-completeness or payoff tests. A redesign must either (a) explicitly frame the puzzle as interpreting a controlled diagnostic test, with a meaningful question about what the test can establish, or (b) provide fair, dated evidence connecting the observations to the original dry-bed incident. Any gate-state claim must be stated in the evidence, not smuggled in through assumed wording.

The design may still be rejected if adding that context makes the solution obvious, contrived, or emotionally empty. Do not add narrative decoration to conceal a weak deduction.

