# Interaction Prototype Blueprint

## Prototype question

Can *Beyond the Ridge* hold a high-school player's attention through work, relationship pressure, evidence, and curiosity without relying on cutscenes or source knowledge?

## Target experience

The prototype should feel grounded, responsive, and socially tense.

The player should understand what Mara can do before the prototype explains what the game means.

The first build should last 45 to 60 minutes for a first-time player.

## Connected playable area

The prototype uses one continuous local region.

- Vale compound.
- Lower and upper salvage yards.
- Mercy House.
- County road.
- Cedar Gate edge and three accessible destinations.
- Vale supper table.
- Mara's room and evidence journal.
- Ridge trail threshold.

Do not include a full college region in the first engine build.

The college motion study remains a later expansion gate.

## Playable sequence

### 0–5 minutes — Ridge dawn

**Purpose:** establish place, routine, and curiosity.

The player can move across the compound, inspect familiar objects, hear family activity, and notice the school bus on the road.

The player chooses one small morning action before breakfast.

Possible actions include checking the generator, feeding an animal, carrying parts, or looking at a hidden book.

The action changes one breakfast line and one later detail.

### 5–10 minutes — Breakfast pressure

**Purpose:** establish family roles through interaction.

The player remains free to look, listen, respond, stay quiet, or leave when the work assignment ends.

The table conversation includes ordinary humor, work planning, a phone interruption, and one disagreement.

Do not present a full dialogue wheel before every line.

Use short intent choices only when Mara must commit to a response.

### 10–20 minutes — The hairline crack

**Purpose:** prove work as gameplay.

The player removes a wheel, cleans the assembly, marks a seam, rotates the hub, and identifies the crack.

The player can:

- reinforce the damaged part,
- ask another worker to confirm the diagnosis,
- challenge Abel's order,
- continue under protest,
- or prepare for a likely failure.

No option is labeled as the correct moral answer.

### 20–26 minutes — Suspended load

**Purpose:** prove interruption and readable danger.

A normal salvage task becomes unstable.

The player must read chain tension, worker position, load movement, and the emergency control.

The response can protect the worker, protect the schedule, or partially achieve both.

A slow response changes the scene instead of forcing an automatic reload.

### 26–33 minutes — Mercy House

**Purpose:** prove care under uncertainty.

Ruth treats a non-graphic work injury.

The player gathers materials, listens to different explanations, and decides whether to continue home treatment, call the clinic, seek advice, or wait.

The care system must not teach unsupported medical claims as fact.

The game may show what characters believe while keeping the consequence model grounded.

### 33–42 minutes — County road and Cedar Gate

**Purpose:** prove travel, conversation, and place learning.

The player drives while Caleb talks.

Traffic, weather, road position, landmarks, and conversation compete for attention.

At Cedar Gate, the player can choose one of three useful destinations:

- Ridgeway Hardware,
- Carnegie Library,
- Cedar Gate Opera House.

Each destination offers a different resource and social consequence.

The player learns the town through repeated landmarks instead of a default minimap.

### 42–50 minutes — Supper version

**Purpose:** prove home as the consequence hub.

The family retells the day's accident.

One detail changes during the telling.

The player can correct the account, soften the correction, ask a question, remain silent, or redirect the conversation.

The result changes relationship states and which private conversation becomes available afterward.

### 50–56 minutes — Evidence journal

**Purpose:** prove interpretation as play.

The player sorts physical evidence, remembered statements, and conclusions.

The journal keeps earlier conclusions visible after revision.

The player can mark an item as unresolved without losing progress.

One unresolved item points toward the ridge signal.

### 56–60 minutes — Ridge signal threshold

**Purpose:** end on curiosity and agency.

A distant signal appears beyond a route the family discourages Mara from using.

The player can prepare, ask for help, investigate immediately, delay, or decide not to pursue it yet.

The prototype ends after the decision becomes clear.

Do not end with a cutscene that overrides the player's choice.

## Core system slices

The prototype implements only enough of each system to test the experience.

### Work and repair

Required verbs:

- inspect,
- clean,
- loosen,
- remove,
- mark,
- compare,
- brace,
- replace,
- test.

The repair model values observation and sequence more than reflex speed.

### Live conversation

Conversation can begin while the player works, drives, walks, or prepares care.

The player can continue the current activity while another character speaks.

A response can be verbal or behavioral.

Silence is a valid response when the situation supports it.

### Relationship state

Track these dimensions separately:

- trust,
- respect,
- fear,
- loyalty,
- dependence,
- clarity.

Do not expose raw numbers to the player.

Use behavior, access, hesitation, help, remembered statements, and tone as feedback.

### Evidence and memory

Store three evidence classes:

- observed,
- reported,
- interpreted.

A statement can move between certainty states as new information appears.

The system must preserve revision history.

### Place knowledge

The player gains route familiarity through travel and landmarks.

The paper map can become more useful as Mara learns the region.

Do not reveal every location at the start.

### Home consequences

The home scene reads the day's state.

Inputs include:

- work outcome,
- injury outcome,
- time used,
- town visit,
- promises kept or broken,
- information disclosed,
- relationship changes.

The system selects a limited set of consequences that can be read clearly.

Do not surface every stored variable in one scene.

## Starting player tendency

The prototype uses one of three starting tendencies.

### HANDS

The player notices tool states, material condition, and repair alternatives sooner.

### EYES

The player notices environmental evidence, body language, routes, and contradictions sooner.

### VOICE

The player receives more opportunities to de-escalate, explain, perform, or ask a precise question.

The starting tendency changes available information and approach speed.

It does not block the other play styles.

## Fail-forward contract

Failure must usually create a new situation.

Examples:

- A rushed repair creates later vibration and a harder roadside fix.
- A missed emergency stop changes injury severity and household labor.
- Getting lost costs time and creates a new conversation.
- A poor social read closes one route while opening another source of information.
- An uncertain journal conclusion delays certainty but can unlock a question.

Reserve hard reloads for unrecoverable technical states or player death in later builds.

The first prototype should rarely need them.

## Save-state contract

Save at these boundaries:

- before breakfast,
- before the hairline-crack decision,
- before the suspended-load event,
- before the Cedar Gate destination choice,
- before supper,
- before the ridge-signal decision.

A review build should support rapid restart from each boundary.

## Accessibility minimum

The first prototype must include:

- scalable subtitles and interface text,
- speaker labels,
- high-contrast interaction cues,
- controller remapping,
- hold or toggle options for repeated inputs,
- reduced camera shake,
- camera sensitivity control,
- sound-direction indicators,
- content warning and skip-with-summary for selected intense scenes.

Skipping an intense scene must not reduce progression or relationship access.

## Instrumentation

Record review events without collecting unnecessary personal information.

Required events:

- first voluntary interaction,
- time to first meaningful choice,
- repair approach chosen,
- emergency-stop response time,
- care approach chosen,
- Cedar Gate destination,
- supper response intent,
- number of journal revisions,
- ridge-signal decision,
- voluntary quit point,
- continuation intent after the session.

Do not infer mental health, religion, family trauma, or other sensitive traits from gameplay behavior.

## Prototype green-light

The prototype can expand when youth review shows all of these together:

- Hook passes.
- Agency passes.
- Activity Clarity passes.
- Character Pull passes.
- Curiosity passes.
- Consequence Legibility passes.

The build must also have no unresolved critical accessibility, rights, faith-representation, or content-care issue.

## Stop conditions

Redesign before expansion when:

- players like the story but do not enjoy the main verbs,
- the repair sequence feels like hidden-answer guessing,
- conversations stop active play too often,
- town navigation feels like empty travel,
- the journal feels like homework,
- the family reduces to heroes and villains,
- or the educational purpose is more visible than the game purpose.
