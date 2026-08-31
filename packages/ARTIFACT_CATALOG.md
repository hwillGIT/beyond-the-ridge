# Artifact Catalog

## Purpose

This catalog identifies canonical records, review assets, optional external binaries, and planned outputs.

## Repository-first rule

The current workflow uses repository-native Markdown, CSV, and PNG files.

The video production package does not require a PPTX or PDF file.

An older editable deck can remain an external reference.

It does not block current design, editing, or review work.

## Foundation and fidelity artifacts

| Artifact | Canonical repository record | Visual or data mirror | State |
|---|---|---|---|
| World Bible | `packages/foundation/01-world-bible/README.md` | Approved review assets | Defined |
| Character Bible | `packages/foundation/02-character-bible/README.md` | Character boards and references | Defined |
| Art Bible | `packages/foundation/03-art-bible/README.md` | Keyframes and visual boards | Defined |
| Chapter Adaptation Matrix | Act CSV files | Forty chapter-poster PNGs | Complete |
| Gameplay Systems | Package README and design records | System and encounter boards | Defined |
| Opening Storyboard | Package README and source maps | Cinematic keyframes | Defined |
| Dialogue and Memory | Fidelity package and CSV records | Selected scene visuals | Defined |
| Locations and Routes | Fidelity package and CSV records | Location and map boards | Defined |

## Gameplay and consequence artifacts

| Artifact | Canonical repository record | Review assets | State |
|---|---|---|---|
| Gameplay Interaction | `docs/design/GAMEPLAY_INTERACTION_AND_HUD_BIBLE.md` | Three gameplay-interface families | Defined |
| Action and Loss | `docs/design/ACTION_AND_LOSS_SYSTEMS.md` | Four loss-scenario PNGs | Defined |
| Persistence System | `docs/design/REDEMPTION_WINDOWS_AND_SECOND_ROADS_BIBLE.md` | Three bibles and two montages | Defined |
| Player Record | `docs/design/PLAYER_RECORD_MASTERY_HISTORY_AND_LEGACY_BIBLE.md` | Seven Player Record PNGs | Defined |

## Video previsualization artifacts

| Artifact | Repository path | State |
|---|---|---|
| Master package README | `packages/previsualization/README.md` | Complete |
| Production brief | `docs/production/VIDEO_PREVIEW_PRODUCTION_PACKAGE.md` | Complete |
| Trailer edit V3 | `packages/previsualization/TRAILER_EDIT_V3.md` | Active |
| Gameplay preview edit V3 | `packages/previsualization/GAMEPLAY_PREVIEW_EDIT_V3.md` | Active |
| Video asset manifest | `source/video-asset-manifest.csv` | Complete |
| Video deliverable contract | `source/video-deliverable-contract.csv` | Complete |
| Visual source assets | `assets/` | Present |
| Approved output location | `deliverables/video/README.md` | Defined |
| 90-second MP4 | `deliverables/video/` | Not rendered |
| Three-minute MP4 | `deliverables/video/` | Not rendered |
| SRT captions | `deliverables/video/` | Not created |

## Review-draft rule

Files with `draft` in the name contain unresolved generated content.

The four low-interface drafts require text and branding correction.

They remain useful for layout, density, and pacing review.

## Optional binary rule

Do not add a PPTX or PDF only because an earlier process created one.

Add an optional binary snapshot only when it has a clear review or archival purpose.

Use a tagged release or approved storage when a binary exceeds normal Git limits.

Do not create duplicate snapshot files on the main branch.

## Output rule

Do not add empty MP4 or SRT files.

Do not mark a deliverable complete before the real file passes its approval gate.