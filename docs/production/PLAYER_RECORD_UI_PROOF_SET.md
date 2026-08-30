# Player Record UI Proof Set

## Status

The six-screen PNG set is complete.

The images are previsualization targets.

They do not represent an engine build.

## Purpose

The set proves how the game rewards skill and records consequence.

It also shows how replay mastery stays separate from canon history.

The interface must answer these player questions:

1. How well did I perform?
2. What changed because of my action?
3. What did I unlock?
4. What history did this run create?
5. Why should I continue or replay?

## Visual set

Open the [complete overview](../../assets/player-record-ui/00-player-record-ui-overview.png).

### 1. Encounter scorecard

Open the [encounter scorecard](../../assets/player-record-ui/01-encounter-scorecard.png).

The screen shows four craft measures:

- Precision.
- Safety.
- Resourcefulness.
- Verification.

Each measure receives zero to three marks.

The screen also shows the practical outcome and world response.

A strong score does not erase a costly result.

The first resolved story result becomes the Canon Mark.

### 2. Capability mastery

Open the [capability mastery screen](../../assets/player-record-ui/02-mastery-roadbook.png).

The screen shows six capabilities:

- Repair.
- Fieldcraft.
- Care.
- Research.
- Performance.
- Voice.

The selected capability shows its current tier and mastery proofs.

The player advances through practice, pressure, transfer, and verification.

The system does not use empty repetition or generic experience points.

### 3. Living History

Open the [Living History entry](../../assets/player-record-ui/03-living-history-entry.png).

The screen keeps several accounts visible at the same time.

It can show:

- What Mara saw.
- What Mara heard.
- What Mara concluded.
- What Mara revised.
- What the household says.
- What the public record says.
- What visibly changed.

The interface can add a causal link after the relationship becomes observable.

It must not reveal future consequences before Mara can know them.

### 4. Challenge Board

Open the [Challenge Board](../../assets/player-record-ui/04-challenge-board.png).

The screen separates the Canon Mark from the Best Mark.

Replay can improve the player's skill record.

Replay does not rewrite Mara's story state.

Challenge variants can change tools, time, weather, help, load, or route conditions.

The screen also shows personal bests and a useful mastery reward.

### 5. Journey Score

Open the [Journey Score screen](../../assets/player-record-ui/05-journey-score.png).

The optional score uses five categories:

- Mastery.
- Discovery.
- Record.
- Stewardship.
- Challenges.

The screen shows the difficulty modifier and act record.

It also shows the player's run signature and next pressure.

The player can hide the Journey Score during a first story run.

The score does not determine a good ending.

### 6. Legacy Card

Open the [Legacy Card](../../assets/player-record-ui/06-legacy-card.png).

The card summarizes one completed run.

It uses five human headings:

- What You Built.
- What You Lost.
- What the World Says.
- What Mara Knows.
- What Remains Possible.

The card also records the chosen path, difficulty, score, capabilities, and Second Roads.

The game never labels one card as the correct life.

## Stable visual rules

### Score craft, not worth

The interface can score observable craft.

It cannot score belief, obedience, trauma, forgiveness, loyalty, or personal worth.

### Separate score from outcome

The player can perform well and still face a costly consequence.

Luck can also protect a weak action for a short time.

The record keeps both facts.

### Preserve canon history

A later Best Mark cannot replace the original Canon Mark.

A Challenge Board replay cannot remove an injury, loss, or accusation.

### Keep history plural

The Roadbook can contain several incompatible accounts.

The game does not invent certainty when the evidence remains incomplete.

### Reward useful mastery

Progress must unlock verbs, information, reliability, shared actions, access, or new work.

It must not reward empty repetition.

### Keep accessibility independent

Control assistance does not reduce the score.

The player can use larger text, remapped controls, longer response windows, and simplified balance.

Difficulty and accessibility remain separate settings.

## Gamer-satisfaction test

A target player should understand the reward loop without reading the design bible.

The player should be able to answer:

- What did I do well?
- What did I do poorly?
- What changed in the world?
- What capability improved?
- What can I attempt next?
- Which result belongs to canon history?
- Which result belongs only to replay mastery?
- What makes my completed run distinct?

## Visual acceptance gates

The set passes visual review when:

- The score does not resemble a morality meter.
- Score and outcome appear as separate information.
- The Canon Mark and Best Mark cannot be confused.
- Mastery shows a useful next proof.
- Living History keeps conflicting accounts readable.
- Journey Score remains optional and understandable.
- Legacy Card feels personal without declaring a true ending.
- Text remains readable at normal television distance.
- Color is not the only carrier of state.
- Every screen supports controller and keyboard navigation.

## Prototype proof

The first interactive proof should implement six slices:

1. One complete encounter scorecard.
2. Repair and Research mastery tracks.
3. One Living History event.
4. One Challenge Board replay.
5. One act-level Journey Score.
6. One sample Legacy Card.

The prototype must record the player's first reaction before explaining the system.

A polished menu cannot compensate for weak main gameplay.

## Video integration

The three-minute gameplay preview should show three short interface moments:

1. The encounter scorecard after the Hairline Crack.
2. The Living History update after supper.
3. The Challenge Board after the preview ends.

The 90-second trailer should show only brief fragments.

The trailer must not pause for a full score explanation.

## Canonical references

- [Player Record, Mastery, History, and Legacy Bible](../design/PLAYER_RECORD_MASTERY_HISTORY_AND_LEGACY_BIBLE.md).
- [Player Record contract](../../source/player-record-contract.csv).
- [Living History event schema](../../source/living-history-event-schema.csv).
- [Player Record prototype addendum](../prototype/PLAYER_RECORD_AND_GAMER_SATISFACTION_PROTOTYPE_ADDENDUM.md).
- [ADR-0009](../decisions/ADR-0009-layered-score-living-history-and-legacy.md).
