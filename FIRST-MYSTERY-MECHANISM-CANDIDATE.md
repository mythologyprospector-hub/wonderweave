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
### Candidate disposition — 2026-10-10

The independent audit leaves the dry-channel concept **not approved as the first mystery**. Its sequence is valid, but its evidence describes a test without tying it to the incident, and the current payoff is mostly a technical diagnosis. Fixing that would require adding evidence and a human-relevant reason to care; adding atmosphere alone would not solve either problem.

Do not continue polishing the four-slip version. Keep it as a useful test of state-transition logic, not as the selected mystery.

### Next design pass: compare mystery cores before choosing a mechanism

The next work should compare a small number of genuinely different mystery cores against the first-proof-of-craft requirements in `CANON.md` and `ROADMAP.md`. For each candidate, answer:

1. What specific question makes a newcomer curious within the first minute?
2. What surprising but fair conclusion can the evidence support?
3. What evidence is needed, and what tempting conclusion must remain unproven?
4. Why does solving it matter emotionally or intellectually beyond “the puzzle has an answer”?
5. Can different strengths contribute, can a solo player finish, and can hints help without giving away the reveal?
6. What is the smallest complete ending that feels like a gift rather than a teaser?

Only then choose a mechanism. A map, sequence, cipher, or physical pattern is a tool, not a requirement. No candidate should advance to player-facing drafting until its core deduction and payoff can be stated plainly and withstand an adversarial review.

**Current project state:** both the station-order concept and the current dry-channel version have failed to earn a player draft. No playable mystery or successful playtest is claimed.


## Mystery-core comparison — 2026-10-10

This comparison evaluates story questions before selecting a puzzle mechanism. These are design hypotheses, not tested player experiences. Scores are qualitative desk judgments, not measurements.

### Candidate A — The town's unreliable sundial

**Hook:** A public sundial appears to be wrong on some days. Is it damaged, badly placed, or telling a different kind of time?

**Possible deduction:** Dated shadow observations and a simple site diagram show that the apparent error changes predictably with the Sun's seasonal path and the dial's orientation. Players distinguish a genuine fault from a mismatch between expectation and what the instrument measures.

**Evidence burden and limits:** The observations need dates, a consistent reference time, location/orientation information, and a clear explanation of what “correct” means. Without those, several explanations remain open. Do not ask players to rely on specialist astronomy or claim more precision than the observations support.

**Payoff:** A satisfying shift in perspective: the object was not necessarily wrong; the question was incomplete. This is intellectually clean, but the human/emotional stakes are modest unless the sundial has a real, well-sourced community purpose.

**Participation/access:** Observation, pattern finding, drawing, and basic reasoning offer different entry points. Provide a printed data table and an explanation route that does not require being outdoors or reading a physical shadow.

**Ending:** Reveal the pattern, explain its limits, and offer a tiny optional observation that lets players see the principle themselves.

**Desk verdict:** Strong fair-deduction potential; currently feels more like a science activity than a memorable mystery.

### Candidate B — The repaired thing with no named repairer

**Hook:** A familiar public object—a little free library, community noticeboard, or shared tool cabinet—was found working again after being damaged. Several notes and dated observations disagree about who fixed it.

**Possible deduction:** The evidence establishes a sequence of small, complementary contributions, while disproving the neat story that one identifiable person did everything. The mystery is not “guess the hero”; it is “what actually made the repair possible?”

**Evidence burden and limits:** Each clue must establish only what its author could directly observe: a replacement part arriving, a measurement being taken, a note being left, or a repair step completed. Dates and physical compatibility must constrain the sequence. The evidence must not pretend to identify an anonymous person or infer their motives without support.

**Payoff:** The reveal reframes an apparent individual achievement as a chain of useful contributions. It can model collaboration without making cooperation compulsory or treating anonymity as suspicious.

**Participation/access:** Players can sort evidence, notice material details, compare timelines, or question assumptions. A solo player can solve it from the same packet; hints can progress from chronology to compatibility to the limits of attribution.

**Ending:** A short, concrete account of how the object became usable again, followed by an invitation to notice the often-invisible work that makes shared things possible. No forced sharing or real-world investigation.

**Desk verdict:** Best alignment with Wonderweave's human promise and collaborative design, but at risk of sentimentality or a predetermined moral if the evidence does not genuinely require the conclusion.

### Candidate C — The message that seems to contradict itself

**Hook:** Three short messages about the same harmless event seem mutually inconsistent. Which account is wrong?

**Possible deduction:** Each message describes a different time, viewpoint, or meaning of a shared term. A small set of independent records resolves the apparent contradiction without requiring anyone to be lying.

**Evidence burden and limits:** The distinctions must be inferable from clues available to every player, not from hidden author intent, cultural insider knowledge, or ambiguous wording alone. The resolution should not depend on declaring one narrator unreliable without evidence.

**Payoff:** Players discover that disagreement can result from incomplete perspectives rather than deception. This can be a strong lesson in interpretation, but the concept risks feeling like a familiar lateral-thinking riddle.

**Participation/access:** Reading, timeline building, and comparing interpretations can all contribute. Use short plain-language texts and a non-reading-heavy alternate representation; a solo route and graduated hints are feasible.

**Ending:** Reconstruct the event from the distinct viewpoints and state exactly which uncertainties remain.

**Desk verdict:** Flexible and accessible in principle, but the premise is generic until anchored to a distinctive, concrete event.

### Comparative decision

| Criterion | A: Sundial | B: Shared repair | C: Conflicting messages |
|---|---|---|---|
| Immediate curiosity | Strong | Strong | Strong |
| Fair, bounded deduction | Strong if observations are rigorous | Promising; needs evidence architecture | Promising; wording must not do all the work |
| Human-relevant payoff | Moderate | Strongest potential | Moderate |
| Different contribution paths | Good | Good | Good |
| Solo finish and hints | Feasible | Feasible | Feasible |
| Main design risk | Becomes a lesson, not a mystery | Moral arrives before evidence; attribution overreach | Becomes a generic lateral-thinking riddle |

**Provisional choice: Candidate B — The repaired thing with no named repairer.** It has the strongest potential to make the deduction matter beyond solving a mechanism and directly embodies the game's promise that different kinds of contribution can combine. This is a choice for the *next design test*, not approval of the story or its conclusion.

### Adversarial gate before any player draft

Candidate B advances only to a mechanism/evidence outline. It must answer all of these without relying on a moral speech:

1. What exactly was damaged, and what observable evidence proves the final repair worked?
2. What are the distinct contributions, and what independent evidence dates or constrains each one?
3. Which tempting single-person explanation is contradicted by evidence, rather than merely being less appealing?
4. Could the same clues support a materially different sequence or conclusion? If so, either add fair discriminating evidence or narrow the claimed answer.
5. Can the reveal be stated as a factual reconstruction first, with its human meaning left for players to recognize?
6. Can the entire mystery be played safely from supplied materials, without contacting strangers, visiting a site, or identifying real people?

If those questions cannot be answered with a compact, non-contrived evidence set, reject Candidate B and return to the comparison rather than decorating it.

**Current status:** no core has been player-tested. Candidate B is the next concept to test on paper, not a selected playable mystery. The Unfinished Map and Dry Channel remain rejected as first-mystery candidates.


## Candidate B pressure test — evidence outline — 2026-10-10

**Purpose:** Try to break the shared-repair concept before writing player-facing copy. This is a fictional design test, not a playable draft.

### Proposed incident

A small, fictional neighborhood book-exchange cabinet was found dry inside after heavy rain, despite a report that its door had been hanging crooked and leaking the day before. The mystery question is deliberately narrow:

**What combination of changes made the cabinet weatherproof again, and what can the surviving notes actually tell us about how the repair happened?**

This is not a “who was the anonymous hero?” mystery. The supplied evidence cannot identify people, and the game should not invite players to do so.

### Minimal proposed evidence set

1. **Before note, 09:10:** “Door drops toward the latch. Upper edge touches the frame; lower latch-side corner leaves a visible gap. Water reached the bottom shelf during yesterday's rain.” A simple diagram marks the gap.
2. **Fit note, 10:00:** “A thin spacer under the lower hinge brings the latch edge level. Door now closes evenly, but a strip of paper placed across the lower edge pulls out without resistance.” The note includes before/after measurements and a diagram.
3. **Material tag, 10:20:** “Offcut used as hinge spacer: 6 mm dry hardwood, trimmed to the measured gap.” The tag establishes the material and dimension, not who supplied or installed it.
4. **Seal note, 11:00:** “Old lower seal is split. Replacement seal fitted after hinge alignment. Paper strip now grips continuously along the lower edge.”
5. **Test note, 11:30:** “Water poured gently over the closed door from outside; no water reached the inside shelf. Latch opened and closed three times without binding.” The note records a bounded test, not proof that the cabinet will resist every storm forever.

These are proposed fictional records. Their times and measurements are design inputs, not external facts.

### Intended reconstruction

The crooked door and failed lower seal are two distinct problems. Aligning the door with a spacer corrects the geometry but does not make the lower edge watertight; replacing the split seal after alignment closes the remaining path. The final controlled test supports the claim that the cabinet passed that test after both changes.

The reveal is therefore not “a mysterious person fixed it.” It is that **the repair required two different corrections, and the first successful-looking change was not enough**. The object became usable through diagnosis, a fitted material, sealing, and a test.

### Adversarial audit

- **Does the evidence support the conclusion?** Mostly, if the diagrams and measurements are internally consistent. The paper-strip observations distinguish alignment from sealing; the final water test supports only the tested condition.
- **Does it prove multiple people contributed?** No. Multiple notes are not proof of multiple authors. Do not make that claim.
- **Does it prove why the earlier leak occurred?** It supports two plausible contributing defects, but the fictional “yesterday's rain” report must be a trustworthy direct observation. Otherwise the original incident is only background.
- **Can a different explanation fit?** Yes: another unrecorded change might have helped, and a single person could have completed all steps. The mystery must concern the documented repair logic, not authorship or credit.
- **Is the ordering mechanic necessary?** The dependencies matter—alignment precedes meaningful seal fitting and testing—but explicit times make the order too easy. If chronology is the puzzle, the evidence must constrain sequence without simply printing timestamps; however, removing timestamps must not make the result ambiguous or contrived.
- **Is the payoff emotionally meaningful?** The current version illustrates layered troubleshooting but still risks feeling like a maintenance worksheet. Its human meaning—care for a shared resource—is inferred from context rather than earned by a surprising deduction.
- **Is it accessible and safe?** Yes in principle: all clues can be supplied on paper, with a diagram and text descriptions; no real cabinet, tools, stranger contact, or outdoor activity is required. A solo player can complete it.

### Disposition

**Candidate B does not yet pass the first-mystery bar.** The technical reconstruction is plausible, but the central insight is predictable and the evidence does not establish the stronger “many hands” story that made the concept attractive. Removing timestamps to create a puzzle would risk artificial obscurity; adding more notes would likely inflate the packet without improving the payoff.

Do not draft player-facing materials from this outline. Keep it as a useful adversarial test and reconsider the core question. The next concept must make the evidence reveal something genuinely unexpected about the shared object or its history—not merely the correct order of sensible repairs. A meaningful human implication must follow from the evidence, not be pasted on afterward.

**Current status:** the shared-repair concept is not selected. No player draft, playtest, or success claim is authorized.


## Fresh mystery-core pass — 2026-10-10

The failed concepts shared a hidden habit: starting with a mechanism (ordering, state transitions, repair steps), then asking it to carry meaning. This pass starts instead with a concrete apparent contradiction and asks what discovery could change the reader's understanding of an ordinary shared object. These are still desk hypotheses, not player-tested concepts.

### Candidate D — The bench that is too short

**Hook:** A public meeting-room bench appears to have been built incorrectly: its measurements do not match the old plan, and the surviving pieces seem not to belong together.

**Possible discovery:** The evidence may show that the bench was designed to change configuration: one short arrangement keeps a passage clear, while a removable section extends it for larger gatherings. The “missing” section is not missing at all; it belongs to a different documented configuration.

**Evidence needed:** A plan with dimensions; matching, distinctive joinery on the loose section and bench; two dated room layouts with measured clearance; and a record or physical mark that discriminates a deliberate modular design from an improvised later alteration.

**Human implication:** The shared object was made to serve two incompatible room needs rather than one idealized use. This would be earned only if the two configurations are independently evidenced; it cannot be inferred merely because flexibility is a nice story.

**Risk:** A loose part plus two layouts may make the answer trivial. If the records do not establish the part's intended role, the “designed for everyone” reading is sentimental overreach. No claim about accessibility or who benefited should be made without evidence.

### Candidate E — The notice that was never wrong

**Hook:** Three preserved notices give different instructions for the same community event. Each seems authoritative, so at least two appear mistaken.

**Possible discovery:** They refer to distinct phases of one event, and the apparent contradiction comes from treating a changing process as a single static instruction. A small floor plan, a sequence of setup marks, and one independently dated notice might establish the transition.

**Evidence needed:** Each notice must contain a discriminating detail that pins it to a phase; the physical or dated records must independently corroborate that phase. Mere ambiguity in wording is not enough.

**Human implication:** The event was coordinated through changing conditions, not one universal instruction. That is potentially useful, but weak as a first-mystery payoff unless the revealed transition changes what the player thinks happened.

**Risk:** This easily becomes a generic “everyone was right in their own way” riddle. Reject it if the resolution depends on charitable reinterpretation rather than evidence.

### Candidate F — The path that seems to waste space

**Hook:** A small public courtyard has a path that takes a strange bend even though a straight route would be shorter. Old diagrams disagree about whether the bend was planned.

**Possible discovery:** Layered plans, runoff marks, and a measured contour may show that the bend follows the only route that stays passable when water crosses the courtyard. The path is not inefficient; the simple map omitted a condition that matters.

**Evidence needed:** A scale plan; contour or level measurements; a mapped water route; and an observation showing why the straight route fails under the specified condition. Aesthetic intent, access benefits, and historical motive must remain unclaimed unless directly supported.

**Human implication:** A choice that looks irrational from a simplified view may be sensible under a constraint that view leaves out. This is a strong transferable insight, but the emotional payoff is modest and the puzzle risks turning into an engineering worksheet.

### Comparative screen

| Candidate | Surprise potential | Evidence can bound the answer | Human meaning earned by evidence | Main failure risk |
|---|---|---|---|---|
| D: Reconfigurable bench | Moderate | Moderate | Potentially strong | “Designed for everyone” invented after the fact |
| E: Changing event instructions | Low–moderate | Moderate | Low–moderate | Generic lateral-thinking riddle |
| F: Bent courtyard path | Moderate | Strong | Moderate | Technical explanation mistaken for a mystery |

**Decision:** none yet clears the first-mystery bar. D has the most human potential but repeats the repair concept's temptation to tell a generous story that the evidence may not prove. F is the most readily falsifiable, but risks being a lesson rather than a mystery. Do not choose one just to maintain momentum.

### Stronger test before another concept is promoted

The next concept must have a *specific reversal*: a plausible initial interpretation, at least two independent evidence strands that undermine it, and a narrower replacement interpretation that explains both. The replacement must change the meaning of the object or event, not merely explain how it works. Before drafting any player-facing material, write:

1. The first interpretation a reasonable newcomer would make.
2. Two independent clues that make that interpretation fail.
3. The exact revised conclusion those clues support.
4. One plausible alternative that remains possible, and the evidence that prevents claiming more.
5. The human implication in one sentence, followed by the evidence for each factual premise in that sentence.
6. Why a player would care even if the object had no sentimental backstory.

If no candidate can satisfy all six without hidden assumptions, the correct action is to keep searching—not to write a handout. The rejected Map, Dry Channel, and shared-repair concepts remain historical design tests. No candidate is approved, playable, or tested with players.


## New direction: evidence of a relationship — 2026-10-10

The last passes kept explaining a single object's apparent flaw. A stronger mystery may reveal a relationship between artifacts that initially seem unrelated. This is a direction to test, not a selected concept.

### Candidate J — The mark shared by unrelated objects

**Initial reading:** Several everyday objects in a community collection carry the same unusual notch. It could be a maker's mark, decoration, or coincidence.

**Evidence that could discriminate:** (1) scaled drawings show the notch has the same non-decorative dimensions and position relative to a functional edge; (2) a dated workshop diagram shows a reusable jig with that exact spacing; (3) independent acquisition records place the objects in different locations before they entered the collection.

**Possible discovery:** The mark is not evidence that one person made all the objects; it records a shared process or tool that linked otherwise separate work. The records could reveal a hidden production relationship without identifying an individual.

**Limits:** Matching dimensions alone do not prove use of the same jig. The workshop diagram must predate the objects or otherwise be independently linked, and alternative standard sizes must be considered. Do not claim a network, collaboration, or shared purpose unless the evidence establishes it.

**Payoff test:** This could change the story from “these objects are alike” to “these objects share a production history.” That is a real relational discovery, but its human meaning is still weak and the exact jig evidence could make the answer too technical.

**Verdict:** Hold for further testing; not approved for a player draft.

### Candidate K — The route that links places no map connects

**Initial reading:** Several old records describe separate deliveries to different public places, with no obvious connection.

**Evidence that could discriminate:** The same rare container dimensions recur in independent receiving records; a route ledger records return intervals; and a dated inventory shows the containers were reused rather than separately owned by each location.

**Possible discovery:** The records may describe a circulating system rather than unrelated deliveries. The relationship is a repeated movement of shared containers, not just a shared label.

**Limits:** Common dimensions and repeated dates are not enough by themselves; a continuous chain of custody or unique marks would be needed. The records must support the route and recurrence, not motives or community impact.

**Payoff test:** Potentially reveals invisible infrastructure behind apparently separate activities. But without a compelling consequence of that circulation, it risks becoming a logistics puzzle.

**Verdict:** Hold. Needs a sharper human or intellectual payoff before any mechanism is designed.

### Current finding

These relational candidates are more promising in kind because they seek to uncover a connection across independent evidence rather than reinterpret one object's condition. Neither currently earns a first mystery: J is too technical, and K has no compelling consequence yet. The next pass should find a relationship whose discovery matters in its own right, while preserving a narrow, evidence-bounded conclusion. No candidate is approved, playable, or player-tested.
