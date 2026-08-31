# Three-Minute Gameplay Preview Edit V3

## Status

This is the active gameplay-preview edit specification.

The V2 file remains as a historical reference.

No rendered gameplay preview exists yet.

## Purpose

The preview must prove that the player performs meaningful actions between story beats.

It must feel like one continuous playable sequence.

The viewer must see control, pressure, consequence, score, history, and replay.

## Target

| Property | Target |
|---|---|
| Duration | 180 seconds |
| Frame size | 1920 by 1080 pixels |
| Frame rate | 30 frames per second |
| Audio | 48 kHz stereo |
| Captions | English SRT companion |
| Output | H.264 MP4 |

## Active cut

| Time | Sequence | Required player evidence |
|---|---|---|
| 0:00–0:15 | Ridge Dawn | Look, move, inspect, and reveal the first objective |
| 0:15–0:30 | Breakfast Pressure | Move during dialogue and select one intention |
| 0:30–1:05 | Hairline Crack | Inspect, mark, select a tool, brace, act, and verify |
| 1:05–1:10 | Encounter Scorecard | Separate the Canon Mark from the practical outcome |
| 1:10–1:35 | Suspended Load | Hear danger, choose a response, and accept a consequence |
| 1:35–1:55 | Mercy House | Carry, report, inspect, and choose a care action |
| 1:55–2:15 | County Road and Cedar Gate | Drive, listen, select a route, and enter town |
| 2:15–2:32 | Supper Version | Correct, soften, support, or remain silent |
| 2:32–2:47 | Living History | Compare accounts and revise one conclusion |
| 2:47–2:55 | Ridge Signal | Read weather, inspect equipment, and choose a route |
| 2:55–3:00 | Challenge Board | Reveal the Canon Mark and one replay condition |

## Continuous-play rule

Do not use a cinematic cut to hide every interaction change.

Use doors, carrying, walking, driving, and camera turns as transitions.

The viewer should understand where Mara is and why she moved.

Camera motion alone does not count as meaningful input.

Provide a meaningful action at least every 20 seconds.

## Sequence details

### 0:00–0:15 — Ridge Dawn

Open behind Mara on the railcar.

Let the player move the camera before an objective appears.

The player can inspect the yard, road, bus, mountain, or distant smoke.

Looking toward the work area reveals the first objective.

Use the low-interface draft only after correcting temporary names and places.

### 0:15–0:30 — Breakfast Pressure

Mara enters the kitchen under player control.

Conversation continues while the player can sit, inspect the telephone, or keep moving.

Abel assigns the truck repair.

The player chooses one intention:

- answer,
- joke,
- ask about the call,
- or remain silent.

Do not freeze the room for the choice.

### 0:30–1:05 — Hairline Crack

The player removes the wheel and reads visible wear.

The fault should not appear as a glowing target.

The player can:

- inspect the hub,
- make a chalk mark,
- compare the service manual,
- ask Eli to watch,
- reinforce the part,
- replace the part,
- continue,
- or stop the work.

Abel pressures Mara while tool control remains active.

The chosen method produces a factual condition and verification state.

### 1:05–1:10 — Encounter Scorecard

Use the Encounter Scorecard as a brief overlay.

Show four work marks.

Show the Canon Mark.

Then show the practical outcome.

Do not show the Best Mark yet.

Do not pause long enough to break the scene.

### 1:10–1:35 — Suspended Load

Return to the yard before the scorecard fully fades.

The chain sound changes before the load moves.

The player can:

- cut power,
- stabilize the load,
- pull Eli clear,
- warn Abel,
- or move back.

Earlier preparation changes the response window.

The result can include injury, equipment loss, delay, or encounter defeat.

Do not use a slow-motion selection wheel.

### 1:35–1:55 — Mercy House

Mara carries supplies through the door.

Ruth asks what happened while preparing treatment.

The player can report accurately, soften the account, inspect the injury, or reach the telephone.

The room remains interactive.

Show one care action and one social consequence.

### 1:55–2:15 — County Road and Cedar Gate

Mara drives while Caleb speaks.

The player controls speed, route, attention, and response.

Show road condition and vehicle state without filling the screen.

Let one route choice change arrival time or available access.

Enter Cedar Gate without a title-card interruption.

### 2:15–2:32 — Supper Version

The family retells the yard event.

Abel changes one important detail.

Eliza notices Mara’s reaction.

The player can correct, soften, support, or remain silent.

Show body language before any record update.

Do not show relationship numbers.

### 2:32–2:47 — Living History

Open the Roadbook through a player action.

Show these views:

- Mara Saw,
- Mara Heard,
- Household Account,
- Public Account,
- Mara Concluded,
- Known Consequence.

Move one claim between evidence states.

Revise one conclusion.

Keep the earlier conclusion visible beneath the revision.

### 2:47–2:55 — Ridge Signal

A distant radio signal interrupts the quiet.

The player closes the Roadbook and returns to the world.

Show weather, equipment, and one route choice.

Use the low-interface draft after correcting temporary route names.

### 2:55–3:00 — Challenge Board

Reveal the resolved encounter in the Challenge Board.

Show:

```text
CANON MARK     9 / 12
BEST MARK      —
```

Add one replay condition.

Example:

`Verify the repair before the quarry deadline.`

End before the replay begins.

The final feeling should be, “I can do that better.”

## Interface integration

Use three interface densities.

Low density supports Ridge Dawn and Ridge Signal.

Contextual density supports breakfast, driving, town, and supper.

Full density supports repair, danger, care, score, and Living History.

Do not place every system on screen at once.

Let physical feedback arrive before score feedback.

## Audio plan

Use continuous world sound to join locations.

Carry one sound across selected transitions.

Examples include:

- a telephone ring into a tool strike,
- an engine idle into road noise,
- a fork scrape into a pencil line,
- and radio static into the final replay reveal.

Dialogue must remain intelligible.

World sounds must still carry mechanical and environmental information.

## Player Record integration

The preview uses three Player Record moments.

1. Encounter Scorecard after the repair.
2. Living History after the supper account.
3. Challenge Board before the end.

Do not show the Journey Score or Legacy Card in this preview.

Reserve those systems for the trailer, later previews, or campaign review.

## Low-interface draft corrections

Replace legacy person names.

Replace temporary place and route names.

Remove direct university branding.

Replace temporary objective text.

Verify every label against the canonical source records.

## Accessibility

Caption spoken dialogue and meaningful off-screen sounds.

Keep captions away from action prompts.

Avoid rapid interface changes during emergency input.

Review camera shake, rain contrast, flashing hazards, and text duration.

Provide pause-and-review access for the scorecard and Living History screens.

## Review question

Ask immediately after viewing:

> What would you do differently if you could play that sequence?

A strong answer names an action, route, conversation, tool, or evidence choice.

A weak answer describes only the plot.

## Acceptance gates

The preview passes when viewers can identify:

- the main objective,
- at least four player verbs,
- one practical consequence,
- one social consequence,
- the Canon Mark,
- one disputed account,
- and one reason to replay.

The preview fails when it feels like a montage.

It also fails when interface inserts replace player action.

## Source files

Use:

- [`video-asset-manifest.csv`](../../source/video-asset-manifest.csv)
- [`gameplay-sequences.csv`](gameplay-sequences.csv)
- [`dialogue-and-vo.csv`](dialogue-and-vo.csv)
- [`sound-cues.csv`](sound-cues.csv)
- [`ui-overlays.csv`](ui-overlays.csv)
- [`video-deliverable-contract.csv`](../../source/video-deliverable-contract.csv)

## Output

Create:

```text
deliverables/video/Beyond_the_Ridge_Gameplay_Preview_3min_v1.mp4
deliverables/video/Beyond_the_Ridge_Gameplay_Preview_3min_v1.srt
```

Do not add either file before a real render exists.