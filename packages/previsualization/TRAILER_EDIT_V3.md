# 90-Second Concept Trailer Edit V3

## Status

This is the active trailer edit specification.

The V2 file remains as a historical reference.

No rendered trailer exists yet.

## Purpose

The trailer must sell a playable promise.

It must show work, choice, danger, consequence, memory, score, loss, and a wider world.

It must not explain the complete system.

## Target

| Property | Target |
|---|---|
| Duration | 90 seconds |
| Frame size | 1920 by 1080 pixels |
| Frame rate | 30 frames per second |
| Audio | 48 kHz stereo |
| Captions | English SRT companion |
| Output | H.264 MP4 |

## Active cut

| Time | Picture | Audio | Player promise |
|---|---|---|---|
| 0:00–0:05 | Ridge Dawn low-interface draft | Wind, distant bus brakes, railcar creak | The world invites attention |
| 0:05–0:10 | Breakfast Pressure | Plates, phone ring, Abel gives a deadline | Home creates pressure |
| 0:10–0:16 | Hairline Crack | Wrench, metal tick, Mara notices movement | Work rewards observation |
| 0:16–0:20 | Encounter Scorecard fragment | Four marks resolve, then the outcome appears | Craft and outcome differ |
| 0:20–0:27 | Suspended Load | Chain strain, engine change, warning shout | Danger remains playable |
| 0:27–0:33 | Mercy House | Glass, mortar, breath, phone-line hum | Care contains uncertainty |
| 0:33–0:40 | County Road | Engine, rain, tires, Caleb speaks | Travel and conversation overlap |
| 0:40–0:47 | Cedar Gate | Door bell, hammer, traffic, radio | The town has practical life |
| 0:47–0:54 | Supper Version | Fork, room tone, Abel retells the event | Action becomes contested memory |
| 0:54–1:00 | Living History fragment | Pencil, page turn, one account changes | The game records disagreement |
| 1:00–1:07 | Ridge Signal low-interface draft | Static, wind, distant tower relay | Curiosity opens another route |
| 1:07–1:14 | College Threshold low-interface draft | Bus brakes, footsteps, paper, crowd | New institutions change the rules |
| 1:14–1:21 | Wider World low-interface draft | Stone echo, bicycles, distant bells | The map becomes larger |
| 1:21–1:27 | Four rapid loss flashes | Load drop, skid, wind, courthouse stamp | The player can lose |
| 1:27–1:29 | Legacy Card and Redemption Seed fragments | Music falls away, page scrape | The world remembers what remains |
| 1:29–1:30 | Final title | Wind only | End with an invitation |

## Picture grammar

Start with space and stillness.

Move toward hands, tools, faces, and immediate risk.

Let the first score fragment arrive after visible work.

Let the Living History fragment arrive after the supper retelling.

Use loss frames as consequences, not spectacle.

Return to stillness for the final title.

## Spoken lines

Use no more than five complete spoken lines.

Suggested lines:

- Abel: “Truck before noon.”
- Mara: “The mark moved.”
- Caleb: “You always this quiet in town?”
- Eliza: “That is not how I remember it.”
- Mara: “I know what I saw. I do not know what it means yet.”

Use original game dialogue only.

Do not quote the memoir.

## Title cards

Use no more than three title cards.

1. `WORK TEACHES YOU WHAT HOLDS.`
2. `THE WORLD REMEMBERS WHAT CHANGED.`
3. `BEYOND THE RIDGE`

The final card can add:

`What lies beyond the world you were given?`

## Score and record inserts

The Encounter Scorecard appears for four seconds.

Show the mark categories before the rank.

Show the practical outcome after the rank.

Do not imply that a high mark guarantees a safe story result.

The Living History insert appears for six seconds.

Show one direct observation.

Show one household account.

Show one known consequence.

Do not show a complete tutorial.

## Loss montage

Use these four frames:

1. Engine-load imbalance.
2. Rain-road crash.
3. Ridge exposure.
4. Wrong-accusation consequence.

Keep each image readable for at least one second.

Do not use rapid injury close-ups.

Show the decision pressure before the worst outcome.

## Persistence fragment

The trailer can show one ordinary object or background character.

Do not label it as redemption.

Do not add a glow, icon, rarity frame, or magical sound.

The fragment should reward a second viewing.

## Low-interface draft corrections

Replace every temporary person name.

Replace every temporary place name.

Remove direct university branding.

Replace temporary college and route copy.

Use fictional names from the canonical source records.

Verify final text at full resolution before export.

## Sound design

Build the trailer from world sounds.

Use music as structure, not emotional instruction.

Let chain strain, road noise, and radio static carry narrative information.

Reserve silence for danger, memory, and the final invitation.

Do not use a villain cue for Abel, religion, or the mountain.

## Interface treatment

Keep interface fragments brief and legible.

Do not show a morality meter.

Do not show relationship hearts.

Do not place several system panels on screen at once.

Use player-facing labels from canonical design records.

## Accessibility

Caption every spoken line.

Caption important off-screen sounds.

Avoid caption placement over score or journal text.

Review flashes and camera motion.

Provide a reduced-motion trailer review export when needed.

## Acceptance gates

The trailer passes when most viewers can name:

- one action they want to perform,
- one danger they understand,
- one relationship they want to examine,
- and one unanswered question.

The trailer fails when viewers praise only the images.

It also fails when viewers cannot describe the player’s role.

## Source files

Use:

- [`video-asset-manifest.csv`](../../source/video-asset-manifest.csv)
- [`trailer-shots.csv`](trailer-shots.csv)
- [`dialogue-and-vo.csv`](dialogue-and-vo.csv)
- [`sound-cues.csv`](sound-cues.csv)
- [`ui-overlays.csv`](ui-overlays.csv)
- [`video-deliverable-contract.csv`](../../source/video-deliverable-contract.csv)

## Output

Create:

```text
deliverables/video/Beyond_the_Ridge_Concept_Trailer_90s_v1.mp4
deliverables/video/Beyond_the_Ridge_Concept_Trailer_90s_v1.srt
```

Do not add either file before a real render exists.