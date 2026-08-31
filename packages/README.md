# Canonical Packages

## Purpose

This directory groups the project’s stable design packages.

Each package README identifies its canonical sources, review assets, current state, and change rules.

## Packages

| Package | Purpose |
|---|---|
| [`foundation/`](foundation/) | Define the world, characters, art, sound, interface, and accessibility targets |
| [`playable-vision/`](playable-vision/) | Define chapter transformation, gameplay systems, and the opening slice |
| [`fidelity/`](fidelity/) | Define dialogue, memory, locations, routes, and small details |
| [`card-library/`](card-library/) | Define the modular game-design reference set |
| [`persistence/`](persistence/) | Define Redemption Windows, Second Roads, and Legacy Chapters |
| [`player-record/`](player-record/) | Define score, mastery, Living History, replay, and campaign legacy |
| [`previsualization/`](previsualization/) | Define the active trailer and gameplay-preview production package |

## Previsualization entry point

Use [`previsualization/README.md`](previsualization/README.md) before video editing.

It links the active V3 edits, asset manifest, output contract, source records, and review gates.

The repository does not contain a rendered MP4 file.

## Source rule

An accepted decision or canonical design document controls implementation.

A source contract controls data fields and player-facing behavior.

A preview image supports review.

Generated image text does not override a canonical term.

## Review export rule

The project stores repository-native Markdown, CSV, and approved PNG assets.

It does not require PPTX or PDF files for the current video workflow.

## Change rule

Update linked records when a change affects timing, dialogue, interface, sound, rights, or source fidelity.

Do not change one production surface while leaving conflicting copies unchanged.