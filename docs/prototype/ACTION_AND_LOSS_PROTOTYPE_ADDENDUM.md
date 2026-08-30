# Action and Loss Prototype Addendum

## Purpose

This addendum updates the first interaction prototype after ADR-0007.

The original blueprint remains the source for region, sequence, character, and review scope.

This addendum controls hard failure, persistent defeat, and expanded action tests.

## Prototype correction

The prototype must no longer prove only fail-forward outcomes.

It must prove all three of these states:

1. A recoverable setback.
2. A persistent defeat that autosaves.
3. An encounter defeat that reloads.

The review build does not require campaign permadeath.

It must include a simulated Iron Ridge loss screen so reviewers can judge the rule.

## Required action tests

### Heavy-load balance

The player carries or guides a suspended engine.

Test:

- left and right grip,
- stance,
- center of mass,
- carried weight,
- handoff,
- safe set-down,
- and emergency release.

Possible outcomes:

- clean delivery,
- dropped engine,
- damaged part,
- hand injury,
- or fatal crush in the hard-loss test.

### Horse route

The player crosses loose or windy ground with a loaded horse.

Test:

- approach,
- calm,
- tack check,
- load distribution,
- rein control,
- route choice,
- and voluntary retreat.

Possible outcomes:

- safe crossing,
- lost cargo,
- horse refusal,
- rider injury,
- or horse loss in Frontier simulation.

### Vehicle skid

The player drives during rain after a repair decision.

Test:

- speed,
- braking,
- handbrake,
- traction,
- seatbelt,
- conversation distraction,
- and route choice.

Possible outcomes:

- controlled recovery,
- damaged cargo,
- broken axle,
- passenger injury,
- or encounter defeat.

### Nonlethal escape

The player must leave a confrontation without turning the game into a combat sequence.

Test:

- guard,
- dodge,
- break grip,
- shove,
- use of terrain,
- call for help,
- surrender,
- and escape.

Possible outcomes:

- clean escape,
- injury,
- property damage,
- legal consequence,
- relationship severance,
- or incapacitation.

### Timed investigation

The player can pursue only two of four leads.

Test:

- time awareness,
- route cost,
- witness availability,
- evidence preservation,
- and accusation under uncertainty.

Possible outcomes:

- supported claim,
- disputed claim,
- wrong accusation,
- lost witness,
- or unresolved case.

## Save rules

### Review setting

Use rapid checkpoints before each system test.

This setting supports iteration and comparison.

### Standard simulation

Death reloads the current encounter.

Persistent injury, asset loss, opportunity loss, evidence loss, and relationship loss autosave.

### Frontier simulation

Death reloads the start of the day.

Resources, injuries, contracts, tools, vehicles, and horse state remain persistent.

### Iron Ridge simulation

Show chapter, act, and campaign permadeath choices.

Run one short reviewer test with chapter permadeath.

Do not require youth reviewers to complete a long permadeath run.

## Instrumentation additions

Record:

- first hazard noticed,
- first voluntary retreat,
- grip correction count,
- dropped-load cause,
- vehicle speed at skid,
- emergency response selected,
- death cause,
- retry choice,
- time to retry,
- persistent loss understood,
- and willingness to continue after loss.

Do not infer personality, trauma history, or risk preference from these events.

## Loss readability questions

After each failure, ask:

- What killed or defeated Mara?
- Which warning did the player notice?
- Which warning did the player miss?
- Which control did the player expect to use?
- Did the result feel fair?
- Did the player know another approach was available?
- Did the player want to retry?

## Pass conditions

The action and loss model passes when:

- at least 80 percent of reviewers identify the main cause of defeat,
- at least 80 percent identify one alternative action,
- most reviewers describe the result as fair,
- persistent defeat changes the next scene visibly,
- safe retreat is understood as a valid action,
- and most target youth reviewers choose to retry at least one hard-loss encounter.
