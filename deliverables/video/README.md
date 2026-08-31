# Video Deliverables

## Purpose

This directory receives approved review renders for the *Beyond the Ridge* previsualization package.

Do not add placeholder media.

Do not add a renamed slideshow and describe it as gameplay.

## Current state

No rendered MP4 file exists.

No caption file exists.

The production package and all repository-native source inputs are available.

## Required files

```text
Beyond_the_Ridge_Concept_Trailer_90s_v1.mp4
Beyond_the_Ridge_Concept_Trailer_90s_v1.srt
Beyond_the_Ridge_Gameplay_Preview_3min_v1.mp4
Beyond_the_Ridge_Gameplay_Preview_3min_v1.srt
REVIEW_NOTES.md
```

Use the exact names in [`source/video-deliverable-contract.csv`](../../source/video-deliverable-contract.csv).

## Primary specifications

### Concept trailer

- Target duration: 90 seconds.
- Allowed duration: 89 through 91 seconds.
- Frame size: 1920 by 1080 pixels.
- Frame rate: 30 frames per second.
- Video codec: H.264.
- Audio: 48 kHz stereo AAC.
- Caption companion: English SRT.

### Gameplay preview

- Target duration: 180 seconds.
- Allowed duration: 178 through 182 seconds.
- Frame size: 1920 by 1080 pixels.
- Frame rate: 30 frames per second.
- Video codec: H.264.
- Audio: 48 kHz stereo AAC.
- Caption companion: English SRT.

## Active edit sources

Use:

- [`TRAILER_EDIT_V3.md`](../../packages/previsualization/TRAILER_EDIT_V3.md)
- [`GAMEPLAY_PREVIEW_EDIT_V3.md`](../../packages/previsualization/GAMEPLAY_PREVIEW_EDIT_V3.md)
- [`VIDEO_PREVIEW_PRODUCTION_PACKAGE.md`](../../docs/production/VIDEO_PREVIEW_PRODUCTION_PACKAGE.md)
- [`video-asset-manifest.csv`](../../source/video-asset-manifest.csv)

## Review notes

Create `REVIEW_NOTES.md` beside the rendered files.

Record:

- render date,
- source commit,
- editor,
- duration,
- codec,
- caption status,
- temporary-copy status,
- rights status,
- accessibility findings,
- youth-review result,
- known defects,
- accepted exceptions,
- and approval decision.

Do not use review notes to hide an unresolved critical defect.

## Acceptance checks

A video can enter this directory after these checks pass:

1. The file opens from a clean checkout.
2. The duration meets the contract.
3. The frame size and frame rate meet the contract.
4. Spoken dialogue is intelligible.
5. Captions match dialogue and meaningful sounds.
6. Temporary names and direct brands are removed.
7. Interface text matches canonical terminology.
8. Source and rights boundaries are satisfied.
9. The video does not claim engine capture.
10. Review notes identify the approving version.

## Version rule

Increase the version number after an approved editorial change.

Do not use filenames such as `final`, `final2`, `latest`, or `new`.

Keep rejected renders outside the approved output path.

## Repository rule

The repository stores approved review renders only.

It does not store source-book media, copied audiobook material, or protected publisher art.