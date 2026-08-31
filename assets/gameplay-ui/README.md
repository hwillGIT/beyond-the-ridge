# Gameplay Interface Proof Frames

## Purpose

This directory contains interaction-focused previsualization for *Beyond the Ridge*.

The frames test whether a viewer can identify the task, action, pressure, and state change.

They do not represent an engine build.

## Interface families

### Full interface

The [`full-ui/`](full-ui/) set supports complex actions.

It covers:

1. Hairline Crack repair.
2. Suspended Load danger response.
3. Mercy House care and referral.
4. Memory Journal evidence review.

These frames show tools, known facts, risk, alternate actions, and verification.

### Contextual interface

The [`contextual-ui/`](contextual-ui/) set supports live movement and conversation.

It covers:

1. Breakfast Pressure.
2. County Road.
3. Cedar Gate.
4. Supper Version.

These frames keep the world active while the player listens, moves, drives, or responds.

### Low interface

The [`low-ui/`](low-ui/) set supports exploration and transition.

It covers:

1. Ridge Dawn.
2. Ridge Signal.
3. College Threshold.
4. Wider World.

These four images are review drafts.

They contain temporary generated names, brands, places, routes, and interface copy.

Correct that text before a public video render.

## Density rule

Use the lowest interface density that keeps the action readable.

Low density supports exploration, arrival, and mystery.

Contextual density supports driving, conversation, town activity, and home scenes.

Full density supports repair, danger, care, score, and evidence analysis.

## Acceptance rule

A frame passes when a viewer can identify:

- the controlled character,
- the current task,
- the active tool or capability,
- two meaningful actions,
- the present pressure,
- and one visible state change.

A frame fails when it reads only as a movie still.

It also fails when generated text conflicts with a canonical design record.

## Canonical sources

Use:

- [`GAMEPLAY_INTERACTION_AND_HUD_BIBLE.md`](../../docs/design/GAMEPLAY_INTERACTION_AND_HUD_BIBLE.md)
- [`control-contract.csv`](../../source/control-contract.csv)
- [`gameplay-feedback-contract.csv`](../../source/gameplay-feedback-contract.csv)
- [`gameplay-keyframe-ui-spec.csv`](../../source/gameplay-keyframe-ui-spec.csv)

The source records override generated interface text.

## Video use

The active video edit uses selected frames from all three interface families.

See:

- [`packages/previsualization/README.md`](../../packages/previsualization/README.md)
- [`VIDEO_PREVIEW_PRODUCTION_PACKAGE.md`](../../docs/production/VIDEO_PREVIEW_PRODUCTION_PACKAGE.md)
- [`video-asset-manifest.csv`](../../source/video-asset-manifest.csv)