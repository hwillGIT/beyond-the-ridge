# Design Index

## Foundation

The foundation package defines the world, cast, and presentation language.

- [World Bible](../../packages/foundation/01-world-bible/README.md)
- [Character Bible](../../packages/foundation/02-character-bible/README.md)
- [Art Bible](../../packages/foundation/03-art-bible/README.md)

## Playable vision

The playable-vision package defines what the player does and how the world responds.

- [Adaptation Matrix](../../packages/playable-vision/adaptation-matrix/README.md)
- [Gameplay Systems](../../packages/playable-vision/gameplay-systems/README.md)
- [Opening Storyboard](../../packages/playable-vision/opening-storyboard/README.md)
- [Gameplay Interaction and HUD Bible](GAMEPLAY_INTERACTION_AND_HUD_BIBLE.md)
- [Action and Loss Systems](ACTION_AND_LOSS_SYSTEMS.md)
- [Redemption Windows and Second Roads Bible](REDEMPTION_WINDOWS_AND_SECOND_ROADS_BIBLE.md)
- [Player Record, Mastery, History, and Legacy Bible](PLAYER_RECORD_MASTERY_HISTORY_AND_LEGACY_BIBLE.md)

## Visual proofs

- [Gameplay interface proofs](../../assets/gameplay-ui/)
- [Persistence System proofs](../../assets/persistence-system/)
- [Player Record and Roadbook proofs](../../assets/player-record-ui/)
- [Player Record production review](../production/PLAYER_RECORD_UI_PROOF_SET.md)

## Interaction source records

These records support implementation and visual review.

- [`source/control-contract.csv`](../../source/control-contract.csv)
- [`source/gameplay-feedback-contract.csv`](../../source/gameplay-feedback-contract.csv)
- [`source/gameplay-keyframe-ui-spec.csv`](../../source/gameplay-keyframe-ui-spec.csv)
- [`source/loss-state-contract.csv`](../../source/loss-state-contract.csv)
- [`source/redemption-window-ledger.csv`](../../source/redemption-window-ledger.csv)
- [`source/player-record-contract.csv`](../../source/player-record-contract.csv)
- [`source/living-history-event-schema.csv`](../../source/living-history-event-schema.csv)

## Core loops

The game uses this loop:

```text
Notice -> Choose -> Act -> Interpret -> Return
```

The expanded action loop is:

```text
Prepare -> Venture -> Work -> Survive disruption -> Decide -> Pay the cost -> Return -> Live with the result
```

The Persistence System uses this loop after selected losses:

```text
Lose -> Linger -> Notice -> Reach -> Accept the cost -> Repair what remains -> Choose a second road
```

The Living Record uses this satisfaction loop:

```text
Perform -> receive feedback -> resolve -> record history -> gain mastery -> unlock -> choose the next risk
```

## Prototype test

The opening prototype succeeds when:

- A non-reader wants to continue.
- A reader recognizes the memoir's tensions without seeing a reenactment.
- Three approaches feel valid in each major encounter.
- Relational consequences matter more than point totals.
- The player understands what Mara saw, heard, and concluded.
- A viewer can identify the task, controls, alternatives, pressure, and feedback from each gameplay frame.
- Lethal and persistent risks are readable before failure.
- A hard loss feels attributable rather than random.
- A safe withdrawal remains a legitimate action.
- A Redemption Window preserves the loss while offering a credible Second Road.
- An encounter score measures observable craft rather than morality.
- The player can distinguish a Canon Mark from a Best Mark.
- Capability growth creates a desired next goal.
- The Living History explains consequence without inventing certainty.
- The player wants to replay at least one encounter or pursue one more route.
