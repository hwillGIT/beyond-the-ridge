# Video Previsualization Package

## Purpose

This package defines two review videos for *Beyond the Ridge*.

The videos must prove the game promise before engine production expands.

They combine action, consequence, character, place, score, history, loss, and persistence.

## Current state

All repository-native production inputs are present.

The repository does not contain a rendered MP4 file.

Four low-interface frames are review drafts.

Their generated names, brands, and interface text require correction before public use.

## Primary deliverables

| Deliverable | Purpose | Target length | Current state |
|---|---|---:|---|
| Concept trailer | Establish action, character, danger, mystery, and scale | 90 seconds | Edit-ready, not rendered |
| Gameplay preview | Prove continuous player action and visible consequence | 180 seconds | Edit-ready, not rendered |

Use the output names in [`source/video-deliverable-contract.csv`](../../source/video-deliverable-contract.csv).

Place approved renders in [`deliverables/video/`](../../deliverables/video/).

## Read first

Review these files in order:

1. [`VIDEO_PREVIEW_PRODUCTION_PACKAGE.md`](../../docs/production/VIDEO_PREVIEW_PRODUCTION_PACKAGE.md)
2. [`TRAILER_EDIT_V3.md`](TRAILER_EDIT_V3.md)
3. [`GAMEPLAY_PREVIEW_EDIT_V3.md`](GAMEPLAY_PREVIEW_EDIT_V3.md)
4. [`video-asset-manifest.csv`](../../source/video-asset-manifest.csv)
5. [`video-deliverable-contract.csv`](../../source/video-deliverable-contract.csv)
6. [`dialogue-and-vo.csv`](dialogue-and-vo.csv)
7. [`sound-cues.csv`](sound-cues.csv)
8. [`ui-overlays.csv`](ui-overlays.csv)

The V2 edit files remain as historical design references.

V3 is the active edit specification.

## Source hierarchy

Use this order when two artifacts conflict:

1. Accepted design decisions.
2. Canonical design bibles.
3. Implementation contracts in `source/`.
4. Active V3 edit specifications.
5. Approved visual assets.
6. Generated review drafts.
7. Rendered review videos.

A rendered video cannot silently change a canonical rule.

Generated image text never overrides the control, interface, character, place, or rights records.

## Repository map

| Area | Repository path | Production role |
|---|---|---|
| Cinematic keyframes | `assets/gameplay-keyframes/` | Tone, continuity, location, and character framing |
| Full-interface frames | `assets/gameplay-ui/full-ui/` | Repair, danger, care, and evidence interactions |
| Contextual-interface frames | `assets/gameplay-ui/contextual-ui/` | Conversation, driving, town, and home scenes |
| Low-interface drafts | `assets/gameplay-ui/low-ui/` | Exploration and transition pacing |
| Loss scenarios | `assets/persistence-system/loss-scenarios/` | Defeat, persistent consequence, and risk |
| Persistence visuals | `assets/persistence-system/bibles/` | Redemption Window and Second Road grammar |
| Player Record screens | `assets/player-record-ui/` | Score, mastery, history, replay, and legacy |
| Motion studies | `assets/motion-studies/` | Camera, hand, vehicle, and transition reference |
| Card boards | `assets/previews/` | Design navigation and production review |
| Output directory | `deliverables/video/` | Approved video, captions, and review notes |

## Editorial promise

The trailer creates desire.

The gameplay preview creates belief.

The trailer can compress time and place.

The gameplay preview must feel like one playable sequence.

Both videos must show that the player acts before the story explains the result.

## Production sequence

1. Lock the active V3 edit.
2. Confirm every source asset in the manifest.
3. Replace temporary names, brands, and generated interface text.
4. Confirm character, location, prop, and era continuity.
5. Assemble the picture edit.
6. Add temporary dialogue and voice-over.
7. Build the sound bed from world sounds.
8. Add interface inserts after the action becomes readable.
9. Create captions and an audio-description review script.
10. Run the review gates.
11. Render review candidates.
12. Publish only the approved files.

## Visual rules

Show hands, tools, terrain, vehicles, faces, and consequences.

Keep Mara recognizable across every location and time period.

Use the mountain as orientation, not decoration.

Show hazards before failure.

Keep interface prompts close to the active object or decision.

Do not present concept images as engine capture.

Do not use copied publisher art, scanned pages, or protected source media.

## Interface rules

Show the current task.

Show at least two meaningful actions during active gameplay.

Show only information that Mara can know.

Keep score separate from story outcome.

Keep Canon Marks separate from Best Marks.

Do not display a morality bar.

Do not display relationship hearts.

Use normal contextual verbs for Redemption Windows.

## Sound rules

Use wind, metal, engines, chain strain, tires, radio static, room tone, paper, boots, and distant voices.

Let sound reveal danger before the interface confirms it.

Do not score every emotion.

Do not assign a villain theme to religion or rural life.

Keep dialogue sparse enough for world sounds to remain legible.

## Accessibility rules

Provide captions for dialogue, important sounds, and radio speech.

Identify speakers when the image does not make identity clear.

Protect caption space during picture composition.

Avoid rapid text that cannot be paused or replayed.

Do not use color as the only warning.

Review flashes, camera shake, and intense sound transitions.

## Youth engagement target

A viewer should name one action they want to perform.

A viewer should also name one unresolved question.

The gameplay preview should produce a specific replay idea.

The viewer should understand that loss can persist.

The viewer should not describe the experience as a sequence of cutscenes.

## Review gates

The package must pass these gates:

- Action is readable.
- Character motivation is readable.
- Place has identity.
- Risk is attributable.
- Consequence remains visible.
- Score measures craft.
- History records disagreement.
- Persistence does not erase loss.
- Accessibility support remains available.
- Source influence remains transformed.
- A youth viewer wants to continue.

## Output contract

Create these primary files:

```text
deliverables/video/
├── Beyond_the_Ridge_Concept_Trailer_90s_v1.mp4
├── Beyond_the_Ridge_Concept_Trailer_90s_v1.srt
├── Beyond_the_Ridge_Gameplay_Preview_3min_v1.mp4
├── Beyond_the_Ridge_Gameplay_Preview_3min_v1.srt
└── REVIEW_NOTES.md
```

Do not add empty media files.

Do not add a file that only renames a slideshow export as gameplay.

## Definition of done

The concept trailer runs between 89 and 91 seconds.

The gameplay preview runs between 178 and 182 seconds.

Both videos use 1920 by 1080 pixels and 30 frames per second.

Both videos use H.264 video and 48 kHz stereo audio.

Captions match spoken dialogue and meaningful sound cues.

All temporary brands and legacy names are removed.

Every visible interface label matches a canonical source.

The gameplay preview provides a meaningful input opportunity at least every 20 seconds.

The review notes record all accepted exceptions.

The project owner approves picture, sound, interface, source fidelity, and content care.

## Boundary

This package proves design intent.

It does not prove engine performance, controller feel, animation quality, or final player satisfaction.

Those claims require a playable build and observed playtests.