# Player Record and Gamer Satisfaction Prototype Addendum

## Status

This document defines the minimum proof for score, mastery, history, completion, and replay satisfaction.

It does not describe an implemented engine build.

## Prototype question

Does the player feel rewarded for skill, consequence, discovery, and replay without reading the score as a morality judgment?

## Required proof sequence

The prototype adds one complete record loop to the opening slice.

```text
Perform
-> receive world feedback
-> resolve the encounter
-> review the Canon Mark
-> see the consequence
-> record the history
-> gain a mastery proof
-> unlock a challenge replay
-> choose whether to continue or improve
```

## Proof 1: encounter scorecard

Use The Hairline Crack as the first scored encounter.

The scorecard shows:

- Precision,
- Safety,
- Resourcefulness,
- Verification,
- a total from zero to twelve,
- the encounter rank,
- and the factual outcome.

The scorecard appears after the work and immediate danger settle.

It does not freeze the emergency sequence.

### Pass signal

The player can explain why each measure received its mark.

### Fail signal

The player believes the score judges obedience, loyalty, or the dialogue choice.

## Proof 2: Canon Mark and Best Mark

The first story result becomes the Canon Mark.

The Challenge Board offers a replay after the story moves forward.

The replay can change:

- available tools,
- weather,
- time,
- companion,
- load condition,
- or HUD density.

The Best Mark remains separate from the story.

### Pass signal

The player understands that replay improves mastery but does not rewrite the accident or supper scene.

### Fail signal

The player expects a better replay score to repair the canon outcome.

## Proof 3: capability advancement

The first build tracks Repair and Fieldcraft.

Each track shows:

- current tier,
- completed mastery proofs,
- next proof,
- and the next verb or information benefit.

The prototype does not require all six capability tracks.

### Repair proof example

- Practice: mark and rotate the hub.
- Pressure: respond while Abel interrupts.
- Transfer: use the same diagnostic habit during a roadside problem.
- Verification: test the repair under load.

### Pass signal

The player can name one ability that improved and one proof still needed.

### Fail signal

The player describes the system as a hidden experience bar.

## Proof 4: tool familiarity

Track one wrench set and one vehicle.

The player should notice:

- faster tool selection,
- steadier placement,
- clearer feedback,
- or a new alternate technique.

Do not display a large numerical familiarity bar.

### Pass signal

The player notices the handling change before reading the Roadbook entry.

## Proof 5: Living History entry

The suspended-load event creates one complete history entry.

The entry includes:

- Mara saw,
- Mara heard,
- Mara concluded,
- household account,
- public account if one exists,
- practical outcome,
- relationship milestones,
- and unresolved questions.

The player can revise the conclusion later.

The earlier conclusion remains visible.

### Pass signal

The player can explain the difference between observation, testimony, and conclusion.

### Fail signal

The history entry reveals the hidden correct answer.

## Proof 6: known causal link

The prototype connects one supported cause and consequence.

Example:

```text
Temporary repair
-> vibration during rain
-> harder vehicle control
```

The link appears only after the later vibration becomes observable.

### Pass signal

The player understands why the later problem happened.

### Fail signal

The link appears as an unexplained punishment or a future spoiler.

## Proof 7: map and discovery state

The County Road sequence records one route source.

The map distinguishes:

- a route Mara discovered,
- a route another person described,
- and a route from a public record.

The player advances one place from Located to Visited or Understood.

### Pass signal

The player can recall how the route became known.

## Proof 8: relationship milestone

One earlier action changes a later behavior.

Examples include:

- Eliza repeats Mara's account,
- Caleb offers transport,
- Ruth changes a form of address,
- or Abel requests Mara's diagnosis while resisting her conclusion.

The Roadbook records the moment after the behavior appears.

### Pass signal

The player notices the behavior before opening the relationship record.

## Proof 9: act Journey Score

The end of the prototype displays an optional base score.

Use these categories:

- Mastery,
- Discovery,
- Record,
- Stewardship,
- Challenges.

Do not apply an online leaderboard.

Do not score the player's faith, family loyalty, medical choice, or ridge-signal decision.

### Pass signal

The player reads the score as a performance and completion summary.

### Fail signal

The player reads it as the game's judgment of Mara's life.

## Proof 10: Legacy Card mockup

The session ends with a prototype Legacy Card.

The card can show:

- what the player built,
- what the player lost,
- what the household says,
- what Mara knows,
- and what remains possible.

The card does not need a complete campaign ending.

It can summarize the vertical slice as a sample run record.

## Roadbook prototype tabs

The first implementation uses six tabs.

- Current
- Mastery
- Map
- People
- Record
- Challenges

Archive and Run can appear as locked or preview tabs.

Do not build the full account-wide Archive before the interaction loop passes.

## Instrumentation

Record these events without collecting unnecessary personal information.

- `encounter_score_seen`
- `score_details_opened`
- `challenge_replay_offered`
- `challenge_replay_started`
- `canon_mark_compared`
- `capability_proof_viewed`
- `capability_goal_pinned`
- `history_entry_opened`
- `history_revision_made`
- `causal_link_viewed`
- `map_source_viewed`
- `relationship_milestone_viewed`
- `journey_score_hidden`
- `journey_score_viewed`
- `legacy_card_viewed`
- `session_continue_intent`

Do not infer intelligence, morality, religion, family trauma, or mental health from these events.

## Youth test gates

The system passes when:

- At least 80 percent can state the current objective.
- At least 75 percent can explain the encounter marks.
- At least 70 percent can name a capability they want to improve.
- At least 70 percent can describe one action-to-consequence link.
- At least 60 percent voluntarily choose a replay.
- At least 70 percent want to continue the game.
- Fewer than 15 percent interpret the Journey Score as morality.
- Fewer than 20 percent describe the Roadbook as homework.
- No player believes accessibility lowered the score.
- Most players can distinguish canon history from replay performance.

## Gamer satisfaction questions

Ask the player these questions after play.

1. What did you get better at?
2. Which score felt fair or unfair?
3. What changed because of your action?
4. Which route, person, or mystery do you want to pursue?
5. Would you replay a task to improve your mark?
6. Did the history feel like your history?
7. Did any score feel like the game judged your character?
8. What would make you play for another hour?

## Stop conditions

Redesign before expansion when:

- the player cannot predict what the score measures,
- a dialogue choice appears to control a work score,
- the player farms injury or loss for points,
- the capability system encourages empty repetition,
- the history system reveals more than Mara knows,
- the replay board weakens story consequence,
- the player ignores the Roadbook because it is too dense,
- or the player enjoys the story but not the main verbs.

## Green-light rule

Expand the Player Record only after score fairness, mastery pull, history legibility, and replay interest pass together.

A polished menu does not compensate for weak gameplay.
