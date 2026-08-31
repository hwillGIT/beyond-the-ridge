# Source Register and Implementation Contracts

## Purpose

This directory records source relationships and implementation contracts.

It does not store protected source copies.

## Primary literary source

Tara Westover, *Educated: A Memoir*. Random House, 2018.

## Storage rule

Do not commit the uploaded book PDF.

Do not commit an audiobook, page scan, publisher image, or long quotation.

Use chapter references and concise detail notes.

## Source and fidelity files

| File | Purpose |
|---|---|
| `source-register.csv` | Record high-level source relationships |
| `canon.csv` | Record the fictional cast and source influences |
| `forms-of-address.csv` | Record pet names, kinship names, and state changes |
| `voice-profiles-family.csv` | Define family speech registers |
| `voice-profiles-world.csv` | Define town, mentor, faith, civic, and peer speech |
| `memory-triggers-01-18.csv` | Record early and middle memory anchors |
| `memory-triggers-19-36.csv` | Record later memory and educational anchors |
| `locations-01-29.csv` | Record mountain, family, town, work, and early academic places |
| `locations-30-58.csv` | Record regional, college, Cambridge, Harvard, Rome, and Jordan places |
| `objects-01-21.csv` | Record home, work, care, survival, and history objects |
| `objects-22-41.csv` | Record performance, academic, travel, safety, and late-game objects |
| `opening-source-map-01-14.csv` | Map source details to opening beats 1 through 14 |
| `opening-source-map-15-28.csv` | Map source details to opening beats 15 through 28 |
| `usage-rules.csv` | Define transformation, dialogue, and review rules |

## Gameplay implementation records

| File | Purpose |
|---|---|
| `control-contract.csv` | Define stable controller and keyboard meanings |
| `gameplay-feedback-contract.csv` | Define practical, capability, evidence, and relationship feedback |
| `gameplay-keyframe-ui-spec.csv` | Define required controls and feedback for each keyframe |
| `loss-state-contract.csv` | Define defeat, persistent loss, campaign loss, and difficulty |
| `redemption-window-ledger.csv` | Define Redemption Seeds, activation, cost, and Second Roads |
| `player-record-contract.csv` | Define score, mastery, map, replay, archive, and Legacy Card behavior |
| `living-history-event-schema.csv` | Define competing accounts, causality, branches, loss, and endings |
| `video-asset-manifest.csv` | Record every active video-production asset and required correction |
| `video-deliverable-contract.csv` | Define output names, state, duration, format, captions, and approval gates |

## Source record fields

A source record can identify:

- source identifier,
- chapter or section,
- detail category,
- concise source note,
- game transformation,
- rights class,
- and review state.

## Implementation record fields

An implementation record can identify:

- input or state,
- player-facing result,
- hidden system rule,
- accessibility requirement,
- persistent consequence,
- production use,
- and review condition.

## Video record use

Use `video-asset-manifest.csv` before picture editing.

The manifest distinguishes approved previsualization from review drafts.

Use `video-deliverable-contract.csv` before rendering.

The contract records both planned MP4 files as `not-rendered`.

Do not change that state until a real media file passes review.

## Authority rule

Treat source records as adaptation notes.

Do not treat them as substitute copies of the memoir.

Write original dialogue and original mission structure.

Treat implementation records as design contracts until a playable prototype validates or revises them.

Generated image text never overrides a source contract.